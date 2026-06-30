# SwarmAI Messenger

A lightweight team messenger with a **Yahoo Messenger + Telegram** feel. People
chat **directly** with each other for free, and the **SwarmAI agent** rides along
as a pinned contact you can message, **BUZZ**, or get delegated tasks from.

Available for **Windows, macOS, Linux, Android**, and as an installable **PWA**.
The desktop apps **auto-update** themselves from the latest release published here.

---

## ⬇️ Download

> **[Get the latest release →](https://github.com/northpeakmalaysia/swarmai-messenger/releases/latest)**

Pick the file for your platform from the latest release:

| Platform | File | Notes |
|---|---|---|
| **Windows** (installer) | `SwarmAI-Messenger-Setup-<version>.exe` | Recommended. One-click install + auto-update. |
| **Windows** (portable) | `SwarmAI-Messenger-Portable-<version>.exe` | No install; run directly. |
| **macOS** | `SwarmAI-Messenger-<version>.dmg` | Open the `.dmg`, drag to Applications. |
| **Linux** | `SwarmAI-Messenger-<version>.AppImage` | `chmod +x` then run. |
| **Android** | `SwarmAI-Messenger-<version>-signed.apk` | Sideload (enable "install unknown apps"). |
| **PWA / web** | `SwarmAI-Messenger-PWA-<version>.zip` | Host on any static server, open in a browser, then **Install app**. |

> A `.aab` is also attached for Play Console uploads.

---

## 🖥️ Install

**Windows** — run `SwarmAI-Messenger-Setup-<version>.exe`. If SmartScreen warns
"unknown publisher", choose **More info → Run anyway** (unsigned builds).

**macOS** — open the `.dmg` and drag the app to **Applications**. On first launch
the build may be unsigned: **right-click the app → Open**, then confirm.

**Linux** — `chmod +x SwarmAI-Messenger-<version>.AppImage` and run it.

**Android** — open the `.apk`, allow **install from unknown sources** when
prompted.

**PWA** — unzip and host the contents on any static web server (or open
`index.html`), then use the browser's **Install app** option.

---

## 🚀 First launch

On first run, enter your team's **relay address**, for example:

```
http://<server-ip>:7910
```

- A plain-HTTP LAN relay works from the **desktop** and **Android** apps.
- The **PWA** served over HTTPS needs an **HTTPS** (or same-scheme HTTP) relay.

That's it — once connected, your contacts and the SwarmAI agent appear in your
contact list.

---

## 🔄 Updates

The **desktop** apps check this repository's releases and update themselves
automatically (Windows & Linux update unsigned; macOS auto-update requires a
signed + notarized build). Android and the PWA are updated by installing the
newest file from the [latest release](https://github.com/northpeakmalaysia/swarmai-messenger/releases/latest).

---

## ℹ️ About

SwarmAI Messenger is part of the **SwarmAI** platform. This repository is a
**distribution channel only** — it hosts the downloadable releases and in-app
auto-update feed. The application source code is **not** published here.

For access, support, or licensing, contact **NorthPeak Malaysia**.
