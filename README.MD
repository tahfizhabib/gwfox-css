# GWFOX 🦊
Lightweight, transparent, and modern Firefox UI compatible with Firefox 143+ on macOS, Linux & Windows

![GWFOX Preview Light/Dark](https://github.com/user-attachments/assets/204bffdb-d37f-4a3e-98f6-c21e84b3b46d)

---

## Features
- Windows 11 transparency (Mica & Acrylic)  
- Optional macOS-style toolbar layout  
- Lightweight, distraction-free, and fast  
- Stripped fork for clean performance  

---

## Installation
1. [Download the theme ZIP](https://github.com/akkva/gwfox/archive/refs/heads/main.zip)  
2. Open Firefox → `about:support` → click **Open Folder** next to your profile  
3. Copy the `chrome` folder from the ZIP into your profile directory  
4. Close Firefox completely and restart  

> **Note:** Always copy files when Firefox is fully closed.  
> **Tip:** Install [Zen Internet](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/) for full-page transparency.  

---

## Configuration (`about:config`)

**Set to true:**  
- `toolkit.legacyUserProfileCustomizations.stylesheets`  
- `svg.context-properties.content.enabled`  
- _Linux:_ `widget.gtk.rounded-bottom-corners.enabled`  
- _Windows:_ `widget.windows.mica`  

**Set to false:**  
- `sidebar.animation.enabled`  
- _macOS:_ `widget.macos.native-context-menus` (optional)  

**Windows-specific:**  
- `widget.windows.mica.toplevel-backdrop = 2`  

---

## Optional Customizations
- macOS-style toolbar & compact mode: `gwfox.plus = true`  
- System-style window controls: `gwfox.plus_sc = true`  
- Bookmark toolbar at top: `gwfox.plus_tb = true`  
- Remove window border with horizontal tabs: `gwfox.noborder = true`  
- Adaptive Tab Bar Colour: `gwfox.atbc = true` ([Add-on link](https://addons.mozilla.org/firefox/addon/adaptive-tab-bar-colour))  
- Blur effects (GNOME): `gwfox.bms = true` ([Blur my Shell](https://extensions.gnome.org/extension/3193/blur-my-shell))  

---

## Transparency Settings
- `widget.windows.mica.popups = 1 or 2`  
- `browser.tabs.allow_transparent_browser` (may affect websites)  

---

Forked and modified from [akkva/gwfox](https://github.com/akkva).
