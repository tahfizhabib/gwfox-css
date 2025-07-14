# gwfox: Redefine Your Firefox Interface with Minimal Elegance

gwfox is a lightweight, modern UI customization for **Firefox 138+**, designed to deliver a cleaner, distraction-free experience.  
Compatible with both **macOS** and **Windows**, with full Mica integration on Windows 11.

![Preview](https://github.com/rakhalfps/gwfox-css/blob/9b61fd4135067d7c99abce792e666384ca2cd3e5/Media/preview.gif?raw=true)

---

## Installation

1. Download this repository and copy the `chrome` folder.
2. Paste the `chrome` folder into your Firefox **profile directory**.

---

## Configuration

Open `about:config` in the Firefox address bar, then apply the following settings:

### Enable (`true`)
- `toolkit.legacyUserProfileCustomizations.stylesheets`
- `svg.context-properties.content.enabled`
- `widget.windows.mica` *(Windows only)*
- `widget.windows.mica.toplevel-backdrop` → set value to `2`

### Disable (`false`)
- `sidebar.animation.enabled`
- `widget.macos.native-context-menus` *(optional on macOS)*

Restart Firefox after applying these changes.

---

## Optional Enhancements

Enable additional styling for a more refined and macOS-inspired interface:

- Moves address bar to the sidebar
- Hides bookmarks toolbar at the bottom
- Adds compact layout and macOS-style window controls

To activate:
1. Open `about:config`
2. Add a new Boolean preference:
   - Name: `gwfox.plus`
   - Set to: `true`

---

## Credit

This theme is inspired by and based on the original [gwfox](https://github.com/akkva/gwfox) by **@akkva**.  
This version introduces additional layout enhancements and aesthetic refinements.
