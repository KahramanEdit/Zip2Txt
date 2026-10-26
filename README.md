<div align="center">

# 📦 Zip2Txt
### Extract, Select, and Copy Magisk Module Scripts Instantly.

[![Android](https://img.shields.io/badge/Android-9.0%2B-green?style=for-the-badge&logo=android)](https://www.android.com/)
[![Java](https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk)](https://openjdk.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](https://opensource.org/licenses/MIT)

An Android utility designed for modders and developers. It allows you to extract text-based files (like `.sh`, `.prop`, `.xml`, `.json`) from any ZIP file (specifically Magisk/KernelSU modules) and copy them directly to your clipboard with a single tap.

[Features](#-features) • [Requirements](#-requirements) • [Installation](#-installation) • [How to Use](#-how-to-use) • [Disclaimer](#-disclaimer)

</div>

---

## 📖 The Problem
If you are developing a Magisk module or trying to reverse-engineer a system tweak, you often need to feed the module's code (`service.sh`, `module.prop`, etc.) to an AI assistant (like ChatGPT or Claude) for debugging or enhancement. 

Manually unzipping the file, opening multiple text editors, and copying files one by one is a tedious process.

## 💡 The Solution
**Zip2Txt** solves this. It uses Android's native Storage Access Framework (SAF) to read any ZIP file, filters out images and binary files, and presents a clean list of text-based files. You can select which files you want, and the app compiles them into a single, well-formatted text block and copies it directly to your clipboard. Paste it into your AI chat, and you're good to go.

## ✨ Features
- **Native File Picker:** Uses Android's default SAF document picker. No unnecessary storage permissions required.
- **Smart Filtering:** Automatically ignores `.dex`, images, and binary files. Only lists `.sh`, `.prop`, `.xml`, `.json`, `.txt`, `.conf`, `.md`, and `.rule` files.
- **Selective Copying:** Checkboxes allow you to select exactly which files you want to include in the output.
- **Clipboard Integration:** Copies the formatted text directly to your clipboard. No file saving required.
- **Clean Output:** Formats the copied text with clear file headers (`FILE: service.sh`) so the AI understands the context.

## 📱 Requirements
- **Android 9.0 (Pie)** or higher.
- **No Root Required.** This app operates safely within the standard Android user space.
- Any standard ZIP file (especially Magisk/KernelSU modules).

## 🚀 Installation
1. Go to the [Releases](../../releases) tab.
2. Download the latest `Zip2Txt_vX.X.apk`.
3. Install it on your Android device. (You may need to allow "Install from unknown sources").
4. Open the app.

## 📖 How to Use
1. Tap **"📂 ZIP Dosyası Seç" (Select ZIP File)** and choose your Magisk module ZIP using the native file picker.
2. Wait a second for the app to parse the archive.
3. Review the list of text files. By default, all files are checked. 
4. Uncheck any files you don't want to copy.
5. Tap **"📋 Seçilenleri Panoya Kopyala" (Copy Selected to Clipboard)**.
6. A success message will appear. 
7. Open your AI chat (ChatGPT, Claude, etc.) and **paste**. The entire module code is now ready for analysis!

## ⚠️ Disclaimer
- This application is provided "as is" without warranty of any kind.
- The developer is not responsible for any data loss, corrupted ZIP files, or issues arising from the use of the extracted code.
- This tool is intended for educational and development purposes only.

## 👨‍💻 Author
**Clenix / Kahraman**
- Feel free to open an issue if you encounter any bugs or have feature requests!

---
<div align="center">
If this tool saved you time from manually copying scripts, feel free to give the repo a ⭐!
</div>
