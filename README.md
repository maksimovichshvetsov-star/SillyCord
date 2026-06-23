# SillyCord 🚀

A lightweight, RAM-optimized, and minimalist Discord client built with **.NET 8 (Windows Forms)** and the **WebView2 (Chromium)** engine.

The official Discord client (built on Electron) often bloats up to 500+ MB of RAM and strains your system with background processes. **SillyCord** was created as an ultra-light alternative for users who want to stay connected without sacrificing PC performance.

## ✨ Features

* 🔋 **Extreme RAM Savings:** Consumes on average **half the memory** of the official client or a standard Chrome tab, thanks to a strict process limit constraint (`--renderer-process-limit=1`).
* 🥷 **Low-End Device Mode:** The engine is finely tuned for weaker PCs—the image and style cache is aggressively flushed from memory when not in use.
* 📥 **Minimize to Tray:** Clicking the "X" button instantly hides the app into the system tray next to the clock and frees up RAM instead of completely closing the program.
* 🧼 **Clean Interface:** Completely removes the annoying bottom status bar that pops up with URLs when hovering over buttons, and disables default browser context menus.
* 🎭 **Chrome Masking:** Secure login via the web version made possible by a built-in full desktop browser User-Agent.
* 📦 **Fully Portable:** No hidden background installers. Download the archive, unpack it anywhere, and you're good to go!

## 🛠️ How to Run (For Users)

1. Go to the **Releases** section on the right and download the latest `SillyCord.zip` archive.
2. Unpack the archive into any folder (e.g., your Desktop or `Program Files`).
3. Run the `SillyCord.exe` file.

> 📌 *Note:* This application requires the [WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/) to be installed on your system (usually built-in by default on Windows 10 and Windows 11).

## 💻 Building from Source (For Developers)

If you want to compile the project yourself, you will need the **.NET 8 SDK** and VS Code / Visual Studio.
