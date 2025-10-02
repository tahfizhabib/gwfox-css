# GWFOX: Reinventing Firefox with Glass 🦊
Lightweight, transparent, and modern Firefox UI compatible with Firefox 143+ on macOS, Linux & Windows

<p align="center">
  <img src="https://github.com/rakhalfps/gwfox-css/blob/a48c59d71b99a00244582478ce7df9ab29cbfebe/Media/PREVIEW.png?raw=true" alt="GWFOX Preview" width="750">
</p>

---

## Features
- Windows 11 transparency (Mica & Acrylic)  
- Optional macOS-style toolbar layout  
- Lightweight, distraction-free, and fast  
- Stripped fork for clean performance  

---

## Installation
1. [Download the theme ZIP](https://github.com/rakhalfps/gwfox-css/releases)  
2. Open Firefox → `about:support` → click **Open Folder** next to your profile  
3. Copy the `chrome` folder and `user.js` file into your profile directory  
4. Close Firefox completely and restart  

> **Tip:** Install [Zen Internet](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/) to enable transparency on all websites.  

---

## Configuration (`about:config`)

**Set to true:**  
- `toolkit.legacyUserProfileCustomizations.stylesheets`  
- `svg.context-properties.content.enabled`  
- _Windows:_ `widget.windows.mica`  
- _Windows:_ `widget.windows.mica.toplevel-backdrop = 2`  

**Set to false:**  
- `sidebar.animation.enabled`  
- _macOS:_ `widget.macos.native-context-menus` (optional)  

**Optional macOS-style layout:**  
- `gwfox.plus = true`  

> Restart Firefox after changing configuration values.

---

## Transparency Settings
- `widget.windows.mica.popups = 1 or 2`  
- `browser.tabs.allow_transparent_browser` (may affect websites)  

---

## Optional Customizations
- macOS-style toolbar & compact mode: `gwfox.plus = true`  
- System-style window controls: `gwfox.plus_sc = true`  
- Bookmark toolbar at top: `gwfox.plus_tb = true`  
- Remove window border with horizontal tabs: `gwfox.noborder = true`  
- Adaptive Tab Bar Colour: `gwfox.atbc = true` ([Add-on](https://addons.mozilla.org/firefox/addon/adaptive-tab-bar-colour))  
- Blur effects (GNOME): `gwfox.bms = true` ([Blur my Shell](https://extensions.gnome.org/extension/3193/blur-my-shell))  

---

## Demo
[![GWFOX Demo](https://github.com/rakhalfps/gwfox-css/blob/a48c59d71b99a00244582478ce7df9ab29cbfebe/Media/PREVIEW.png?raw=true)](https://github.com/user-attachments/assets/193190a8-9bbe-4c23-818b-508e9927f636)

---

Forked and modified from GWFOX.
