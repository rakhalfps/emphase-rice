# emphase-rice

![Windows 11](https://img.shields.io/badge/OS-Windows%2011-blue?style=flat-square)
![Firefox](https://img.shields.io/badge/Browser-Firefox-orange?style=flat-square)
![Minimal](https://img.shields.io/badge/Style-Minimal-green?style=flat-square)
![Mica Effect](https://img.shields.io/badge/Effect-Mica-purple?style=flat-square)

A translucent, minimal Windows 11 setup — clean visuals, modern styling, and a Firefox rice with true WinUI vibes.

---

## Installation Overview

| Step | Tool / Mod                   | Description                                  |
|-------|-----------------------------|----------------------------------------------|
| 1     | [Firefox-WinUI](https://github.com/Lockframe/Firefox-WinUI)               | WinUI-style Firefox theme                    |
| 2     | [Zen Internet (Extension)](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/)    | Applies and refreshes Firefox styles         |
| 3     | [Windhawk](https://windhawk.net/)                    | Runtime Windows UI modifier                  |
| 4     | [DWMBlurGlass](https://github.com/Maplespe/DWMBlurGlass)                | Adds blur and transparency effects system-wide |
| 5     | MicaForEveryone *(optional)* | Advanced Mica effects (not required)          |
| 6     | [ExplorerBlurMica](https://github.com/Maplespe/ExplorerBlurMica)            | Mica and blur effects for File Explorer      |
| 7     | [gemini-cli](https://github.com/google-gemini/gemini-cli)                  | CLI for Gemini protocol (terminal usage)     |
| 8     | [Cursor Pack (DeviantArt)](https://www.deviantart.com/jimmyxd2/art/1208233550)                 | Modern cursor style from DeviantArt        |

---

## Step 1 - Prerequisites

Install the following tools in this order:

- [Firefox-WinUI](https://github.com/Lockframe/Firefox-WinUI)
- [Zen Internet extension](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/)
- [Windhawk](https://windhawk.net/)
- [DWMBlurGlass](https://github.com/Maplespe/DWMBlurGlass)
- [ExplorerBlurMica](https://github.com/Maplespe/ExplorerBlurMica)
- [gemini-cli](https://github.com/google-gemini/gemini-cli)
- [Cursor Pack (DeviantArt)](https://www.deviantart.com/jimmyxd2/art/1208233550)

> **Note:** MicaForEveryone is optional. The rice works perfectly fine without it.

---

## Step 2 - Firefox Setup

1. **Open Firefox Profile Folder**

   - Navigate to `about:support`
   - Find **Profile Folder** and click **Open Folder**

2. **Apply the Theme**

   - Download files from [Firefox-WinUI](https://github.com/Lockframe/Firefox-WinUI)
   - Install the `spinner-font.ttf` font
   - Copy the `chrome/` folder and `user.js` file into your profile folder

3. **Enable Transparency**

   - Open `about:config`
   - Toggle the following keys to enable Mica effects and transparency:

     ```
     widget.windows.mica
     widget.windows.mica.popups
     browser.tabs.allow_transparent_browser
     ```

   > **Note:** Enabling `browser.tabs.allow_transparent_browser` extends the Mica backdrop into new tab page areas but may cause rendering issues on some web pages.

4. **Activate Zen Internet Extension**

   - Install the [Zen Internet extension](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/)
   - Use it to refresh Firefox styles
   - Firefox should now reflect the WinUI + Mica look

---

## Step 3 - Windhawk Mods

1. Open [Windhawk](https://windhawk.net/)  
2. Go to each mod’s **Details → Advanced** section  
3. Paste in the corresponding mod code from the links below:

| Mod              | Pastebin Link                                  |
|------------------|------------------------------------------------|
| Taskbar Styler   | [View Code](https://pastebin.com/qM0WLtch)    |
| Start Menu Styler| [View Code](https://pastebin.com/834WW7me)    |

---

## Step 4 - DWMBlurGlass

1. Move `DWMBlurGlass` folder to `C:\Program Files\DWMBlurGlass`  
2. Run the executable to install  
3. Download the required **symbol files** from the UI  
4. (Optional) Skip MicaForEveryone unless you want advanced mica customization  
5. For enhanced File Explorer blur effects, install [ExplorerBlurMica](https://github.com/Maplespe/ExplorerBlurMica)

---

## Step 5 - Terminal with Gemini

Use the [gemini-cli](https://github.com/google-gemini/gemini-cli) in your terminal to browse Gemini protocol sites. Follow the setup instructions in its repository.

---

## Step 6 - Terminal Appearance Setup

1. Open **Windows Terminal** → **Settings** → **Defaults** → **Appearance**.  
2. Enable **Use acrylic material**.  
3. Set **Background opacity** to `30`.

---

Thanks for checking it out!

---

**Maintained by [Miqim aka Rakhal](https://github.com/rakhalfps)**
