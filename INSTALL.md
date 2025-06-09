# 🦊 Fruity Fox Installation Guide

Welcome to the installation guide for **Fruity Fox** — a clean and modern Firefox UI skin inspired by Arc and Zen.

Follow these steps to install and activate the theme.

---

> ■ **Transparency Support Notice**
>
> - Windows 11: Mica blur effect supported  
> - macOS 12+: Native transparency supported  
> - Windows 10 & Linux: Transparency not supported  
> - Linux: Currently unstable with this theme

---

## ■ Step 1: Download the Theme Files

- Download or clone the latest version of **Fruity Fox** from [GitHub](https://github.com/your-repo-link)
- Locate the `chrome` folder in the source
- Download the [user.js](https://github.com/rakhalfps/gwfox-css/blob/4acbdc5bb66f731b2c1df80dc7412e889317521e/user.js) file

---

## ■ Step 2: Open Your Firefox Profile Directory

1. Open Firefox  
2. Type `about:profiles` into the address bar and press **Enter**  
3. Locate the profile marked **default** or your current profile  
4. Click **Open Folder** next to **Root Directory**

---

## ■ Step 3: Install Theme Files

- Copy the `chrome` folder into your Firefox **root directory**
- Copy the `user.js` file into the **root directory** as well
- Ensure that both `chrome/` and `user.js` are now inside the **root directory**

---

## ■ Step 4: Enable Required Firefox Settings

To enable theming features, go to `about:config` and apply the following:

| Preference                                      | Value   |
|------------------------------------------------|---------|
| `toolkit.legacyUserProfileCustomizations.stylesheets` | `true`  |
| `svg.context-properties.content.enabled`       | `true`  |
| `widget.windows.mica` *(Windows only)*         | `true`  |
| `browser.urlbar.scotchBonnet.enableOverride`   | `false` |
| `sidebar.animation.enabled`                    | `false` |
| `widget.macos.native-context-menus` *(macOS)*  | `false` |

---

## ■ Step 5: Restart Firefox

- Close **all Firefox windows**
- Reopen Firefox — the Fruity Fox theme should now be active

---

## ■ Optional Customization Tips

- Right-click the toolbar → **Customize Toolbar** to adjust button layout  
- Enable or reposition the **Bookmarks Toolbar**  
- Modify `userChrome.css` inside the `chrome/` folder to adjust style  
- Toggle your OS's **light/dark mode** to switch theme appearance

---

## ■ If It's Not Working...

- Double-check that both `chrome/` and `user.js` are inside the **Firefox root directory**
- Revisit `about:config` and ensure all required settings are applied correctly
- Make sure Firefox is fully restarted
- If issues persist, try downloading the fallback config:  
  [user.js fallback file](https://github.com/rakhalfps/gwfox-css/blob/4acbdc5bb66f731b2c1df80dc7412e889317521e/user.js)  
  Move it into your **Firefox root directory**

---

## ■ Done!

You're now running **Fruity Fox 🦊**, a modern, distraction-free Firefox theme. Enjoy!
