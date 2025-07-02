# Emphase — Translucent, Minimal Windows 11 Setup

![Windows 11](https://img.shields.io/badge/OS-Windows%2011-blue?style=flat-square)
![Firefox](https://img.shields.io/badge/Browser-Firefox-orange?style=flat-square)
![Minimal](https://img.shields.io/badge/Style-Minimal-green?style=flat-square)
![Mica Effect](https://img.shields.io/badge/Effect-Mica-purple?style=flat-square)

A clean, glassy Windows 11 rice with Mica effects, transparent terminals, and a Firefox setup styled to match WinUI design principles.

> **Wallpaper**: [View on Wallhaven](https://wallhaven.cc/w/o5ly2l)

---

<p align="center">
  <img src="https://github.com/rakhalfps/emphase-rice/blob/main/MEDIA/1.png" width="48%" style="margin-right:4%"/>
  <img src="https://github.com/rakhalfps/emphase-rice/blob/main/MEDIA/3.png" width="48%"/>
</p>

---

## Installation

Install these tools and mods in the following order:

| Tool / Mod                                                       | Description                                       |
|------------------------------------------------------------------|---------------------------------------------------|
| [Firefox-WinUI](https://github.com/Lockframe/Firefox-WinUI)     | WinUI-style Firefox theme                         |
| [Zen Internet (Extension)](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/) | Refreshes Firefox styles                          |
| [Windhawk](https://windhawk.net/)                                | Runtime Windows UI modifier                       |
| [DWMBlurGlass](https://github.com/Maplespe/DWMBlurGlass)        | Adds blur and transparency system-wide            |
| *MicaForEveryone* (optional)                                     | Adds advanced Mica effects (optional)             |
| [ExplorerBlurMica](https://github.com/Maplespe/ExplorerBlurMica)| Blur & Mica for File Explorer                     |
| [gemini-cli](https://github.com/google-gemini/gemini-cli)       | Terminal tool for Gemini protocol                 |
| [Cursor Pack (DeviantArt)](https://www.deviantart.com/jimmyxd2/art/1208233550) | Custom modern cursor theme                        |

> **Note:** MicaForEveryone is optional — the setup works fine without it.

---

## Firefox Setup

1. **Open Firefox Profile Folder**
   - Go to `about:support` and open your **Profile Folder**

2. **Apply Theme**
   - Download [Firefox-WinUI](https://github.com/Lockframe/Firefox-WinUI)
   - Install `spinner-font.ttf`
   - Copy `chrome/` and `user.js` to the profile folder

3. **Enable Transparency**
   - Open `about:config` and set the following to `true`:
     ```
     widget.windows.mica
     widget.windows.mica.popups
     browser.tabs.allow_transparent_browser
     ```

4. **Activate Zen Internet**
   - Install [Zen Internet](https://addons.mozilla.org/en-US/firefox/addon/zen-internet/)
   - Use it to reload styles

---

## Windhawk Mods

1. Launch [Windhawk](https://windhawk.net/)  
2. For each mod, go to **Details → Advanced** and paste the code:

| Mod               | Pastebin Link                              |
|-------------------|--------------------------------------------|
| Taskbar Styler    | [View Code](https://pastebin.com/qM0WLtch) |
| Start Menu Styler | [View Code](https://pastebin.com/834WW7me) |

---

## DWMBlurGlass Setup

1. Move `DWMBlurGlass` to `C:\Program Files\DWMBlurGlass`  
2. Run the executable and install required symbol files  
3. *(Optional)* Use MicaForEveryone for deeper tweaks  
4. Install [ExplorerBlurMica](https://github.com/Maplespe/ExplorerBlurMica) for blur in File Explorer

---

## Terminal Appearance

1. Open **Windows Terminal → Settings → Defaults → Appearance**  
2. Enable **Acrylic material**  
3. Set **Background opacity** to `30`

---

## Gemini Terminal

Install and use [gemini-cli](https://github.com/google-gemini/gemini-cli) for browsing Gemini protocol sites from the terminal.

---

## Credits

Thanks to:

- [JimDoe](https://www.reddit.com/user/Historical-Dirt-294/)
- [NikitaPZ](https://www.reddit.com/user/NikitaPZ/)
- [iiGiovanni](https://www.reddit.com/user/iiGiovanni/)
