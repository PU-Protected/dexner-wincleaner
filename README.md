# ⚡ Dexner Ultimate Tool

> A complete tool for repairing, cleaning, and optimizing Windows 10/11.

[![Version](https://img.shields.io/badge/version-v2.0-00d4ff?style=flat-square)](https://github.com/PU-Protected/dexner-wincleaner/releases)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-blue?style=flat-square)]()
[![Python](https://img.shields.io/badge/python-3.10%2B-yellow?style=flat-square)]()

---

## 🚀 Features

### 📊 Dashboard
- 🪟 Windows info (version + build)
- 🔥 Live CPU monitoring
- 🧠 Live RAM monitoring
- 💾 Disk info (free space)
- ⚡ Quick actions (clean, network reset, performance boost)

### 🧹 Deep Cleaner (9 tools)
- 🗑️ Clean TEMP files
- ♻️ Empty Recycle Bin
- 📦 Prefetch cache
- 🌐 DNS cache
- 🖼️ Thumbnail cache
- 📥 Windows Update cache
- 🌐 Browser cache (Chrome, Edge, Firefox)
- 💾 Create Restore Point
- 🔄 Restart Explorer

### 📦 Debloat
- 30+ preinstalled bloatware apps
- Bulk selection (Select all / Deselect all)
- Safe removal via PowerShell

### ⚡ Performance Boost
- 🔥 High Performance power plan
- 🚫 Disable telemetry (DiagTrack)
- 🔄 Disable SysMain (Superfetch)
- 🔍 Disable Windows Search
- 📈 Disable animations
- 🚀 Startup Manager
- 🎮 Game Mode
- 🧠 RAM test

### 🌐 Network Tools (7 tools)
- 🌐 Flush DNS
- 🔌 Reset Winsock
- 📡 Reset TCP/IP
- 🔄 Renew IP
- 📊 Ping test
- 🌍 IP Config
- 📶 Wi-Fi Profiles

### 💻 System Info
- Detailed PC information
- CPU, RAM, GPU, Disk
- Uptime, Last boot

### 👤 Profile + 👑 Admin Panel
- Cloud login (Firebase)
- IP address, country, city, ISP
- Admin roles (Owner/Admin)
- User management (Ban, Delete, Reset)

### 🔄 Auto-updater
- Checks for new versions from GitHub
- Silent check on startup
- Manual check in Settings

### 🌍 Multi-language
- 🇨🇿 Čeština
- 🇸🇰 Slovenčina
- 🇬🇧 English
- 🇷🇺 Русский
- 🇩🇪 Deutsch
- 🇵🇱 Polski

---

## 📥 Download

**Latest version:** [Download from Releases](https://github.com/PU-Protected/dexner-wincleaner/releases/latest)

### System Requirements
- **Windows 10 / 11** (64-bit)
- **Python NOT REQUIRED** (everything is bundled in the `.exe`)
- **Admin rights required** (for system operations)

---

## 🛠️ Run from Source

If you prefer to run from source (safer, no `.exe` false positives):

```bash
# 1. Clone repository
git clone https://github.com/PU-Protected/dexner-wincleaner.git
cd dexner-wincleaner

# 2. Install dependencies
pip install customtkinter requests firebase-admin packaging

# 3. Run
python wincleaner.py

🏗️ Build from Source
To build your own .exe:

bash
python -m PyInstaller --onefile --windowed --name WinCleaner --uac-admin --icon=icon.ico --collect-all customtkinter --collect-all packaging --hidden-import updater --hidden-import update_window --hidden-import auth --hidden-import login_window --hidden-import admin --hidden-import i18n --add-data "auth.py;." --add-data "login_window.py;." --add-data "updater.py;." --add-data "update_window.py;." --add-data "admin.py;." --add-data "i18n.py;." --add-data "firebase_admin_key.json;." wincleaner.py
Result: dist/WinCleaner.exe

🎯 Roadmap
✅ v2.0 (Current)
Login + Profile + Admin Panel

Dashboard (live monitoring)

Deep Cleaner (9 tools)

Debloat

Performance Boost

Network Tools (7 tools)

System Info

Multi-language

Auto-updater

🔜 v2.1 (Planned)
🔧 Auto-Fix (VC++ Redistributable, .NET, DirectX)

🛡️ System Repair (SFC, DISM)

📊 Error Fixer (Event Viewer analysis)

🔮 v3.0 (Future)
🎮 Game Booster

📱 Mobile companion app

☁️ Cloud backup

🐛 Report a Bug
Found a bug? Report it at GitHub Issues.

Please include:

Windows version (10 / 11)

What you were doing

Screenshot (if possible)

Console output (if any)

📜 License
MIT License — free to use, modify, and distribute.

See LICENSE for details.

👨‍💻 Author
Dexner — dexner.xyz

🔗 GitHub: @PU-Protected

🌐 Website: dexner.xyz

⭐ Support
If you find this tool useful:

⭐ Star the repository

🐛 Report bugs you find

💡 Suggest features via Issues

📢 Share with friends

<div align="center">
⚡ Made with ❤️ by Dexner

</div> ```
