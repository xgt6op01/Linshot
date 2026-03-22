# Linshot

**Linshot** is a Greenshot-inspired, lightweight, and incredibly fast screenshot application designed natively for Linux distributions. 

It provides a rich set of capture modes and a fully-featured annotation editor to quickly mark up your screenshots before saving or copying them.

## Features

- **Capture Modes:** Region (Drag), Target Window (Click), Fullscreen, and Repeat Last Region.
- **Rich Annotation Editor:** Draw shapes (Rectangle, Ellipse, Line, Arrow), Freehand, add Text, Highlight, Blur/Pixelate, or add Step-Counter stamps.
- **High-DPI Support:** Crisp text and images on scaled monitors.
- **Global Hotkeys:** Works instantly, even when the application is minimized to the system tray.
- **Exports:** Save to file (PNG, JPG, BMP), Copy to Clipboard, open in external applications, or instantly upload.

## Installation

Linshot is distributed as a single Debian package (`.deb`). You do not need to compile any code or worry about build dependencies.

### Requirements
You must be running a **64-bit Debian-based Linux distribution**:
- Ubuntu (or Kubuntu, Xubuntu, etc.)
- Linux Mint
- Kali Linux
- Pop!_OS
- Debian

### 1. Download the Latest Release
Go to the [Releases page](../../releases/latest) and download `linshot_0.1.0-1_amd64.deb`.

### 2. Install
Open your terminal and run the following command in the directory where you downloaded the file:

```bash
sudo apt install ./linshot_0.1.0-1_amd64.deb
```
> *Using `apt install` ensures that any underlying dependencies (like Qt5 and X11 Extras) are automatically downloaded and installed natively by your system.*

### 3. Run
You can launch **Linshot** directly from your system's Application Menu, or by typing `linshot &` in your terminal. 

The application sits quietly in your system tray, ready whenever you press your capture hotkeys (e.g., `PrintScreen`).

---
*Created for the Linux community as a lightweight, native alternative to Windows screenshot utilities.*
