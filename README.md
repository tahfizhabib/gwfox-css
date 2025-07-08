# Firefox Custom Theme (macOS & Windows)  
*For Firefox 138+*

---

## How to Install

1. **Copy Files**  
Place the downloaded `chrome` folder into your Firefox **profile folder**.

2. **Change Settings**  
Go to `about:config` in Firefox and update these preferences:

- Set to `true`:
  - `toolkit.legacyUserProfileCustomizations.stylesheets`
  - `svg.context-properties.content.enabled`
  - `widget.windows.mica` *(Windows only)*
  - `widget.windows.mica.toplevel-backdrop` → set to `2` *(Windows only)*

- Set to `false`:
  - `sidebar.animation.enabled`
  - `widget.macos.native-context-menus` *(optional, macOS)*

3. **Restart Firefox**

---

## Optional Feature

To enable extra style tweaks (like bottom bookmarks toolbar and sidebar address bar), create a new Boolean preference in `about:config`:

- Name: `gwfox.plus`  
- Value: `true`

---

## Notes

- *Windows/macOS only* features are marked.  
- Backup your Firefox profile before changing settings.

---

Enjoy your cleaner Firefox UI!
