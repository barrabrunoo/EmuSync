<img width="1408" height="768" alt="EmuSync" src="https://github.com/user-attachments/assets/ad680f07-5381-46a5-b119-0bf3b743c654" />

# EmuSync 🎮☁️

**EmuSync** is a lightweight, background-running Windows system tray application designed to automatically synchronize your emulator save files (such as PCSX2 memory cards) with Google Drive. Say goodbye to manual backups and keep your game progress safe across devices!

> ⚠️ **Notice:** This project is currently in an **early testing phase (Beta)**. Because it uses Google OAuth client credentials under testing limits, new users must be manually added to the authorized testers list to complete authentication. If you want to test it, please contact the developer via email at **bb.barrabruno@gmail.com** to request access.

---

## ✨ Features

* **System Tray Integration:** Runs quietly in the system tray (`pystray`) with quick options to sync manually or open settings.
* **Bidirectional Cloud Sync:** Automatically uploads local changes or downloads newer saves from Google Drive based on modification timestamps.
* **Multi-Slot Support:** Seamlessly syncs multiple memory card files simultaneously (e.g., Slot 1 `Mcd001.ps2` and Slot 2 `Mcd002.ps2`).
* **Smart Windows Path Detection:** Automatically detects the user's real Documents folder using Windows API calls, fully compatible with **OneDrive** and redirected paths.
* **Friendly Configuration GUI:** A clean Tkinter-based settings window allowing users to select their emulator folder and configure file names without editing raw JSON files.
* **Secure OAuth 2.0:** Secure authorization flow utilizing Google Drive API.

---

## 🚀 Roadmap & Future Updates

* **Automatic File Watcher:** Real-time detection of file modification to trigger automatic upload/download without manual sync clicks.
* **Multi-Emulator Support:** Expanding compatibility to support other popular emulators beyond PCSX2 (such as DuckStation, PPSSPP, and more).

---

## 🛠️ Built With

* **Python** - Core logic
* **Tkinter** - Configuration GUI
* **pystray & Pillow** - System tray interface and icons
* **Google Drive API** - Cloud storage integration
* **PyInstaller & PyArmor** - Standalone executable compilation and protection

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
