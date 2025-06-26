# GWFox – A Minimal Firefox UI Theme

<picture>
<source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/d7699474-d17b-4560-a9d6-9e1ecaac0ba5">
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/90f88774-2886-4a02-aae8-6814f3199adb">
<img width="1495" alt="01">
</picture>
<br><br>

- This theme supports Firefox 138+ on **Mac** and **Windows**

## How to Use

- Place the downloaded `chrome` folder into your Firefox **profile directory**

- Go to `about:config` and set these values:

  - Set to `true`:
    - `toolkit.legacyUserProfileCustomizations.stylesheets`
    - `svg.context-properties.content.enabled`
    - `widget.windows.mica` *
    - `widget.windows.mica.toplevel-backdrop` → `2`
    - `gwfox.plus` *(to enable extra tweaks)*

  - Set to `false`:
    - `browser.urlbar.scotchBonnet.enableOverride`
    - `sidebar.animation.enabled`
    - `widget.macos.native-context-menus` *(optional)*

- Restart Firefox

## Style Tweaks

- Bookmarks bar moved to bottom  
- Address bar moved to sidebar  
- Minimal UI and macOS-style window buttons *
