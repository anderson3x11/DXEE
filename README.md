# Deus Ex Enhanced Edition

A drag'n'drop enhancement pack for *Deus Ex (GOTY)* that modernizes graphics, compatibility, and visuals — without altering any of the original gameplay or places.

## ✅ What's Included

- **Kentie’s Launcher** – widescreen/resolution support, raw input, FOV fixes, etc.
- **Direct3D 10 Renderer** – modern GPU compatibility and visual improvements.
- **New Vision** – high-resolution environmental textures.

---

## 🔧 Requirements

Before launching the game, make sure your system has the following installed:

- **Microsoft Visual C++ 2015 Redistributable** (required by Kentie’s Launcher)  
  🔗 [Download from Microsoft](https://www.microsoft.com/en-us/download/details.aspx?id=48145)

- **Microsoft Visual C++ 2010 Redistributable** (required by Direct3D 10 Renderer)  
  🔗 [Download from Microsoft](https://www.microsoft.com/en-us/download/details.aspx?id=5555)

- **DirectX End-User Runtime (June 2010)** (needed for proper D3D10 renderer support)  
  🔗 [Download from Microsoft](https://www.microsoft.com/en-us/download/details.aspx?id=8109)

✅ These only need to be installed once, most modern systems already have them, but it doesn't hurt to make sure.

---

## 📦 Installation

1. [Download the ZIP](https://github.com/YOUR-USERNAME/DeusEx-Enhanced-Edition/releases/latest).
2. Unzip it.
3. Drag and drop the contents (`System/`, `New Vision/`) into your *Deus Ex* install folder.
4. Overwrite when prompted.
5. Launch the game using the new `deusex.exe` (Kentie’s launcher).

---

## 🛠 Recommended Kentie's Launcher Configuration

After launching `deusex.exe`, you’ll see a configuration button. I recommend the following settings for the best experience:

### Video Options
- **Renderer**: `Direct3D 10 Support`
- **FPS Limit**: Set to your screen refresh rate (Set to `0` if using an NVIDIA card; see NVIDIA note below)
- **Quality**: `32 bit color`
- **Check**: `Detail textures`

### Viewport
- Choose between:
  - `Fullscreen`
  - `Borderless fullscreen window` *(recommended for alt-tabbing)*
- **Resolution**: Set to your native screen resolution (You might have to select fullscreen first to set your resolution)

### Field of View
- ☑ `Custom`: `91`

---

## ⚠️ NVIDIA Users

1. **Right-click desktop → NVIDIA Control Panel**
2. Go to **Manage 3D Settings → Program Settings**
3. Select or add `deusex.exe`
4. Set **Max Frame Rate** to your monitor's refresh rate (e.g. `60`, `120`, `144`, etc.)
5. Back in Kentie's launcher, set **FPS Limit** to `0`

This prevents stutter and heavy lags.

---

## 🙏 Credits

- [Kentie’s Launcher](https://kentie.net/)
- [New Vision Mod](https://www.moddb.com/mods/new-vision)
- [Direct3D 10 Renderer](https://kentie.net/article/d3d10drv/)

> This modpack is unofficial. All rights belong to their respective creators. Support the original devs and modders!

## 💡 Contributing

Have ideas for other essential mods, fixes, or improvements? Feel free to open an issue or submit a pull request — contributions and suggestions are always welcome!