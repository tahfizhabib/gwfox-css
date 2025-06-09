# Fruity Fox 🦊 Skin for Firefox (gwfox)  
*Inspired by Arc and Zen — A clean, modern, minimalistic UI skin for Firefox*




![GWFox Theme Preview](https://github.com/rakhalfps/gwfox-css/blob/c5bff073d546a7732f3fdaa048b680aadddec0a5/IMAGES/8.jpg?raw=true)
---

## Introduction

Welcome to **Fruity Fox 🦊 (gwfox)**, a sleek Firefox skin inspired by the popular Arc and Zen themes known for their minimalist and elegant user interfaces. This theme focuses on clean lines, subtle color accents, and a distraction-free browsing experience. Whether you're a macOS or Windows user, Fruity Fox enhances your Firefox interface with a modern and fresh look that adapts to your system’s light or dark mode preferences.

---

## Why Fruity Fox?

Firefox’s default interface is functional but sometimes cluttered. Many users seek a more streamlined, visually appealing design that improves usability and aesthetics. Fruity Fox answers this demand by:

- **Reducing UI clutter** with minimal toolbar buttons  
- **Hiding unnecessary elements** such as the bookmark toolbar by default  
- **Using colors and effects** inspired by Arc and Zen for a calming and consistent appearance  
- **Supporting modern Firefox features** like Mica blur on Windows for a sleek translucent background  
- **Automatically adapting** to your OS’s color scheme (light/dark)  

---

## Compatibility

| Platform | Firefox Version | Notes                                      |
| -------- | --------------- | ------------------------------------------|
| Windows  | 138+            | Supports Mica effect (Windows 11 only)    |
| macOS    | 138+            | Supports native context menu tweaks (optional)  |

> **Note:**  
> The transparent Mica effect works only on Windows 11 and macOS. It does **not** work on Windows 10 or Linux. Linux support is currently partial and untested.

---

## Features At a Glance

- **Minimal toolbar with button limit:** Supports up to 4 buttons on the left and 4 on the right to maintain balance and simplicity  
- **Bottom-positioned bookmark toolbar:** Keeps the top clean; you can re-enable or reposition if preferred  
- **Light & dark mode support:** Automatically switches based on system settings  
- **Mica effect support on Windows:** Adds modern translucency for better aesthetics (Windows 11 only)  
- **Custom SVG properties enabled:** Ensures crisp, smooth icons and UI elements  
- **Disables animations and color overrides** that conflict with the theme’s style  

---

## Installation Guide

Please refer to the [Install Guide](https://github.com/rakhalfps/gwfox-css/blob/fe6daa58bdf9acd5d6099267740c439857e53c2c/INSTALL.md) for detailed installation instructions.

---

## Configuration Guide (about:config Tweaks)

To enable the custom styles and ensure full compatibility, adjust the following settings:

| Preference                                      | Value  | Purpose                                     |
|------------------------------------------------|--------|---------------------------------------------|
| `toolkit.legacyUserProfileCustomizations.stylesheets` | `true` | Enables loading of userChrome.css and userContent.css files  |
| `svg.context-properties.content.enabled`       | `true` | Enables advanced SVG styling support        |
| `widget.windows.mica` *                         | `true` | Enables Windows Mica translucent effect (optional) |

Set the following preferences to **false** to avoid conflicts with the theme:

| Preference                                    | Value  | Purpose                                      |
|-----------------------------------------------|--------|----------------------------------------------|
| `browser.urlbar.scotchBonnet.enableOverride` | `false` | Disables URL bar color override               |
| `sidebar.animation.enabled`                    | `false` | Disables sidebar open/close animations       |
| `widget.macos.native-context-menus` (optional) | `false` | Disables native macOS context menus for uniformity |

---

## Applying the Theme

Once you’ve copied the files and set the preferences:

1. **Restart Firefox** completely (close all windows and reopen)  
2. Enjoy your new Fruity Fox skin!  

---

## Image Preview (gwfox)

<div style="border: 1px solid #ccc; border-radius: 12px; padding: 16px; margin: 20px auto; max-width: 960px;">

### Preview 1  
<div style="display: flex; gap: 12px; justify-content: center; flex-wrap: wrap;">
<img src="https://github.com/rakhalfps/gwfox-css/raw/dc99d35b3e1aa92994f272d52f98bfea250782dd/IMAGES/1.png" alt="Fruity Fox Screenshot 1" width="460" style="border-radius: 8px; box-shadow: 0 3px 8px rgba(0,0,0,0.25);">
<img src="https://github.com/rakhalfps/gwfox-css/raw/dc99d35b3e1aa92994f272d52f98bfea250782dd/IMAGES/2.png" alt="Fruity Fox Screenshot 2" width="460" style="border-radius: 8px; box-shadow: 0 3px 8px rgba(0,0,0,0.25);">
</div>

---

### Preview 2  
<div style="display: flex; gap: 12px; justify-content: center; flex-wrap: wrap;">
<img src="https://github.com/rakhalfps/gwfox-css/raw/dc99d35b3e1aa92994f272d52f98bfea250782dd/IMAGES/3.png" alt="Fruity Fox Screenshot 3" width="460" style="border-radius: 8px; box-shadow: 0 3px 8px rgba(0,0,0,0.25);">
<img src="https://github.com/rakhalfps/gwfox-css/raw/dc99d35b3e1aa92994f272d52f98bfea250782dd/IMAGES/5.png" alt="Fruity Fox Screenshot 5" width="460" style="border-radius: 8px; box-shadow: 0 3px 8px rgba(0,0,0,0.25);">
</div>

---

### Preview 3  
<div style="display: flex; gap: 12px; justify-content: center; flex-wrap: wrap;">
<img src="https://github.com/rakhalfps/gwfox-css/raw/dc99d35b3e1aa92994f272d52f98bfea250782dd/IMAGES/6.png" alt="Fruity Fox Screenshot 6" width="460" style="border-radius: 8px; box-shadow: 0 3px 8px rgba(0,0,0,0.25);">
<img src="https://github.com/rakhalfps/gwfox-css/raw/dc99d35b3e1aa92994f272d52f98bfea250782dd/IMAGES/7.png" alt="Fruity Fox Screenshot 7" width="460" style="border-radius: 8px; box-shadow: 0 3px 8px rgba(0,0,0,0.25);">
</div>

</div>

---

## Customization Tips

- **Toolbar buttons:** Keep the number of toolbar buttons to a max of 4 on the left and 4 on the right for best visual balance.  
- **Bookmark Toolbar:** To enable or move the bookmark toolbar, right-click the toolbar area, choose **Customize Toolbar**, and toggle the bookmarks toolbar position or visibility.  
- **Color scheme:** Change your OS’s light/dark mode to see automatic theme switching.  
- **Further tweaks:** Feel free to modify the userChrome.css file inside the `chrome` folder for personal adjustments.  

---

## Troubleshooting

| Issue                         | Solution                                              |
|-------------------------------|------------------------------------------------------|
| Theme changes don’t apply     | Ensure `chrome` folder is in the correct profile folder. Restart Firefox after changes.  |
| Preferences don’t stick       | Double-check changes in `about:config`. Use the search bar to find exact names.         |
| Buttons don’t align properly  | Reduce toolbar buttons to max 4 left + 4 right. Check for any extensions affecting UI.   |
| Mica effect not visible       | Confirm Windows version supports Mica (Windows 11+). Preference must be `true`.         |
| Bookmarks toolbar missing     | Enable it via toolbar customization or modify userChrome.css accordingly.               |

---

## FAQ

**Q: Will this skin work on Linux?**  
A: It’s designed and tested mainly for Windows and macOS. Linux support may be partial and untested due to different Firefox behaviors.

**Q: Can I customize the theme colors?**  
A: Yes! By editing the CSS files inside the `chrome` folder, you can change colors, sizes, and other UI elements.

**Q: How do I revert back to the default Firefox UI?**  
A: Remove the `chrome` folder from your Firefox profile directory and set any toggled preferences back to their default values.

**Q: What if Firefox updates break the theme?**  
A: Because this skin relies on Firefox’s userChrome.css, some updates might require adjustments. Keep an eye on the repository for updates or report issues.

---

## Contributing

Your feedback and contributions are highly appreciated! Feel free to:

- Open issues for bugs or feature requests  
- Submit pull reque
