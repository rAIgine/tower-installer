# Raigine Tower Installer

This repository contains public release files for the **Raigine Tower Desktop App** built using Electron.

> 🛠️ This is not the source code. The actual application code is maintained in a private repository.

---

## 🚀 Download Latest Version

You can always find the latest release installer here:

👉 [Download the Latest Release](https://github.com/rAIgine/tower-installer/releases/latest)

The installer includes:
- 🪟 Windows `.exe` (NSIS setup)
- 📦 `latest.yml` and `.blockmap` for auto-updates

---

## 🔄 Auto-Update Support

The Raigine Tower app supports over-the-air (OTA) updates using GitHub Releases. When a new version is available:

- The app will check the latest version from this repo
- It will download and install the update automatically on restart

> Electron auto-updates are powered by [`electron-updater`](https://www.electron.build/auto-update).

---

## 📄 Release Structure

Each release includes:

| File                          | Purpose                          |
|------------------------------|----------------------------------|
| `Raigine Tower Setup x.x.x.exe` | Main Windows installer            |
| `latest.yml`                 | Metadata used for auto-updating |
| `.blockmap`                 | Differential update support     |

---

## 🧪 Check Current Version

You can verify the current version installed by:

1. Opening the app
2. Clicking `Help → About` or `Settings → Version Info` *(depending on your UI)*

---

## 📣 Need Help?

If you encounter problems with the installer or updates, please contact the Raigine support team.

---

© 2025 Raigine. All rights reserved.
