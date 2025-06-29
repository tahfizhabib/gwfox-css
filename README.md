<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/d7699474-d17b-4560-a9d6-9e1ecaac0ba5">
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/90f88774-2886-4a02-aae8-6814f3199adb">
  <img width="1495" alt="GWfox UI Preview">
</picture>

<br>

# GWfox UI – Custom Firefox Theme (Minimal / System Native)

A refined user interface for Firefox 138+, inspired by native OS styling.
Supports Windows and macOS.\*

---

## Installation Guide

> Place the `chrome` folder into your Firefox profile directory and configure the required preferences below.

### Windows Setup

```bash
1. Go to: about:profiles
2. Click "Open Folder" for your current profile
3. Copy the `chrome` folder into that location
```

```text
Open about:config and set the following:

[Enable]
toolkit.legacyUserProfileCustomizations.stylesheets → true
svg.context-properties.content.enabled             → true
widget.windows.mica                               → true
widget.windows.mica.toplevel-backdrop             → 2

[Disable]
sidebar.animation.enabled                          → false
```

Then restart Firefox.

---

### macOS Setup

```bash
1. Go to: about:profiles
2. Click "Show in Finder" for your current profile
3. Copy the `chrome` folder into that location
```

```text
Open about:config and set the following:

[Enable]
toolkit.legacyUserProfileCustomizations.stylesheets → true
svg.context-properties.content.enabled             → true

[Disable]
sidebar.animation.enabled                          → false
widget.macos.native-context-menus                  → false (optional)
```

Then restart Firefox.

---

## Optional Features

To enable additional tweaks like:

* Vertical address bar in sidebar
* macOS-style window buttons
* Hidden bookmark bar

Open `about:config` and:

```text
Add Boolean → gwfox.plus → true
```

---

## Notes

* Firefox 138+ required (Nightly or Developer Edition recommended)
* Windows visual effects depend on system theme and GPU support
* macOS features may vary slightly depending on OS version
