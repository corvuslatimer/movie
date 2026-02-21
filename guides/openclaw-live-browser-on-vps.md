# OpenClaw Live Browser on a VPS (Ubuntu + XRDP + Chrome)

If your agent is stuck in headless mode and failing login-heavy sites (like X), this is the setup that worked for me.

This guide gets you from:
- "browser tool exists but login keeps failing"

to:
- "I can watch my agent drive a real browser session live over RDP."

---

## Why this setup works

Headless browser automation is great for many tasks, but some sites aggressively challenge headless fingerprints.

The fix is simple: run a **real desktop session** and let OpenClaw control a **non-headless Chrome** instance.

---

## Prereqs

Recommended VPS size:
- **4 vCPU / 8 GB RAM**
- 40+ GB disk

You need:
- Ubuntu server
- sudo access
- OpenClaw already installed (or install it first)

---

## 1) Install desktop + XRDP

```bash
sudo apt update
sudo apt install -y xfce4 xfce4-goodies xrdp dbus-x11

echo xfce4-session > ~/.xsession
sudo adduser xrdp ssl-cert
sudo systemctl restart xrdp
sudo reboot
```

Notes:
- XFCE is usually more stable than GNOME over XRDP.
- After reboot, connect with your RDP client.

---

## 2) Install real Chrome (not snap Chromium wrapper)

```bash
wget -q https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb -O /tmp/google-chrome.deb
sudo apt install -y /tmp/google-chrome.deb
```

---

## 3) Configure OpenClaw browser settings

Edit `~/.openclaw/openclaw.json` and set:

```json
{
  "browser": {
    "enabled": true,
    "defaultProfile": "openclaw",
    "executablePath": "/usr/bin/google-chrome-stable",
    "headless": false,
    "noSandbox": true
  }
}
```

Then restart gateway:

```bash
openclaw gateway restart
```

If needed:

```bash
systemctl --user restart openclaw-gateway.service
```

---

## 4) Test browser control

```bash
openclaw gateway status
openclaw browser --browser-profile openclaw status
openclaw browser --browser-profile openclaw start
openclaw browser --browser-profile openclaw open https://x.com
openclaw browser --browser-profile openclaw snapshot
```

If this works, your agent can now open/click/type in a visible browser that you can watch over RDP.

---

## 5) Login flow for X

- Open `https://x.com` in the controlled browser
- Login manually once (or let agent do it)
- Keep session cookies; agent can continue from there

If a session expires, re-login and continue.

---

## Common issues

### "Can't reach the OpenClaw browser control service"
- Gateway may be up but browser controller failed to start.
- Restart gateway and re-check `openclaw browser ... status`.

### XRDP "Something has gone wrong" crash screen
- Switch to XFCE (`echo xfce4-session > ~/.xsession`) and reboot.

### Chromium snap weirdness
- Use Google Chrome `.deb` + explicit `executablePath`.

---

## What your agent can do after setup

- Scroll and interact on feed surfaces in real time
- Like/reply/bookmark based on your rules
- Take screenshots/snapshots for proof
- Keep running server-side scripts and git workflows in parallel

---

## Minimal copy/paste checklist

```bash
# desktop + rdp
sudo apt update && sudo apt install -y xfce4 xfce4-goodies xrdp dbus-x11

echo xfce4-session > ~/.xsession
sudo adduser xrdp ssl-cert
sudo systemctl restart xrdp

# chrome
wget -q https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb -O /tmp/google-chrome.deb
sudo apt install -y /tmp/google-chrome.deb

# restart openclaw gateway after config edit
openclaw gateway restart

# test
openclaw browser --browser-profile openclaw start
openclaw browser --browser-profile openclaw open https://x.com
```

---

If your agent wants to learn this setup, send it this post.
