

# 🐈 FLOOB'S KEYCAST

### A customizable keyboard, mouse, and controller input overlay for Windows.

Display your inputs with a clean, customizable overlay built for gaming, streaming, recording, and more.

<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b078cdee-c990-497f-815f-b1bf856fec73" width="800" alt="Floob's KeyCast preview">
</p>

<br>

## 📥 [Download Latest Release](../../releases/latest)

**Latest Version: v0.0.91**

</div>

---

## ✨ Features

| ⌨️ Keyboard & Mouse | 🎮 Controller | 🎨 Customization | 💾 Profiles |
|---|---|---|---|
| Select displayed keys | Xbox and PS5 overlays | Colors and glow | Save and favorite setups |
| Keyboard presets | Live button visualization | Themes and textures | Quick profile switching |
| Mouse buttons and movement | Stick and trigger visualization | Custom backgrounds | Link profiles to games |
| Key animations | Separate appearance settings | Live desktop editing | Import and export `.keycast` files |

### ⌨️ Keyboard & Mouse Overlay

Choose which keys appear and customize your keyboard layout, scale, spacing, colors, glow, and animations. Display mouse buttons and movement alongside your keyboard. Changes appear on the desktop overlay as you edit.

### 🎮 Controller Overlay

Switch to an Xbox or PlayStation 5 / DualSense overlay to display controller input. Customize its appearance independently from your keyboard and mouse setup.

### 🎨 Make It Yours

Customize your overlay with:

- Key, outline, and pressed-input colors
- Glow effects and animations
- Application themes
- Custom backgrounds and device textures
- Adjustable scale and positioning
- Separate Keyboard & Mouse and Controller appearance settings

### 💾 Profiles & Game Linking

Save setups as profiles, then activate, rename, duplicate, favorite, or delete them from the **Profiles** page. You can also switch profiles from the system tray.

Link a saved profile to a game or application and optionally have KeyCast switch to it when that window is focused. The redesigned game library searches Steam, Epic, and common installation locations without freezing the editor.

### 📤 Share Your Setup

Export your current Keyboard & Mouse or Controller setup as a portable `.keycast` file. Import the file into another KeyCast installation to use that setup there.

Each export contains one mode. Local custom-image paths are excluded because those files will not exist on another computer.

### 🎥 OBS Capture

To show your overlay in OBS Studio, add a **Window Capture** source and select **Floob's KeyCast Overlay**.

---

## 📥 Installation

1. Go to the **[latest release](../../releases/latest)**.
2. Download `FloobsKeyCast-Setup-X.X.X.exe`.
3. Run the installer and follow the setup wizard.
4. Launch **Floob's KeyCast**.
5. Follow the built-in tutorial, then select **Show on Desktop** to display your overlay.

> **Windows SmartScreen:** Floob's KeyCast is not currently digitally signed, so Windows may display an “Unknown Publisher” warning when you run the installer.

**No Python installation is required** when using the Windows installer.

---

## 🔄 Updating

KeyCast checks for new public GitHub Releases and can show the release notes inside the editor. Select **Install Update** to download and install an available update through the app.

You can also download the newest installer from [GitHub Releases](../../releases) and install it over your existing version. You do **not** need to uninstall KeyCast first.

Your settings, saved profiles, and imported images are stored separately in `%APPDATA%\FloobsKeyCast` and are preserved between updates.

---

## 🛠️ Recovery & Diagnostics

KeyCast saves configuration changes automatically and keeps recent configuration history. If you need to undo a saved change, open **Settings** and select **Restore Previous Configuration** to choose from up to five recent versions.

If you encounter a problem, **Export Diagnostic Report** creates a ZIP containing app and system details, controller status, recent startup logs, and a configuration with selected file paths redacted. Review the report before sharing it.

---

## 🖥️ Requirements

- Windows 10 or Windows 11
- 64-bit Windows recommended

---

## 🐛 Bugs & Suggestions

Found a bug or have an idea for Floob's KeyCast? Open an **Issue** on this repository.

When reporting a bug, please include:

- Your Floob's KeyCast version
- What you were doing when the problem occurred
- What you expected to happen
- A screenshot, if possible
- A diagnostic report, if relevant and after reviewing its contents

---

## 🗺️ Development

Floob's KeyCast is actively being developed. Future releases will continue improving customization, usability, performance, and the overall overlay experience.

⭐ **Star the repository** if you'd like to follow the project.

---

<div align="center">

### 🐈 Floob's KeyCast

**Your keys. Your mouse. Your overlay.**

</div>
