# s3amm3r's Optimizer (v1)

An extreme performance engine & Fluent UI toolkit for Roblox.  
Turns high‑graphics games into smooth, 144+ FPS experiences with the click of a button.

## ⚡ What It Does

- Overhauls lighting, shadows, post‑processing, and audio to reduce CPU/GPU load.
- Dynamically hides far‑away objects (particles, beams, decals, etc.) based on distance.
- Auto‑Mode scales graphics down when your FPS drops below a set threshold.
- Quick presets for “Balanced” and “Maximum Overdrive”.
- Integrated **Fluent UI** with multiple tabs for full control.
- Real‑time FPS & engine status overlay.

## 📂 UI Tabs

| Tab | Contents |
|-----|----------|
| **Dashboard** | Real‑time metrics, master boost toggle |
| **Quick Presets** | One‑click Balanced / Maximum Overdrive |
| **Core Settings** | Lighting, post‑processing, camera FOV, auto‑mode, FPS cap |
| **Visual & Audio** | CastShadow removal, audio range limiter |
| **Distance Rules** | Per‑class distance culling (11 classes, adjustable ranges) |
| **Danger Zone** | Destructive options (potato graphics, clear debris, strip terrain) |
| **Settings** | Theme saving, UI configs, watermark toggle |

## 🔧 Features

- **Simplify Lighting** – kills global shadows, sets fixed brightness.
- **Disable Post Processing** – removes all bloom, blur, sun rays, etc.
- **Stabilize Camera FOV** – locks FOV to a lower, performance‑friendly angle.
- **Remove Part CastShadow** – strips shadow rendering from every part.
- **Reduce Audio Range** – caps sound distance to prevent distant audio processing.
- **Auto Mode** – dynamically lowers FOV / shadows when average FPS drops.
- **Distance Yielding Engine** – 11 object types are toggled off when too far from the camera.
- **Overdrive Preset** – max distance culling + all visual features on.
- **Danger Zone** – one‑click potato graphics (destroys decals, textures, sets plastic material), clears loose debris, and strips terrain grass/water details (requires `sethiddenproperty`).

## 🚀 How to Use

1. **Inject** your favourite Roblox executor (tested on Potassium,NOT TESTED ON OTHERS).  
2. **Run** the script.  
3. The GUI will appear. Check **Dashboard** and toggle the master boost **ON**.  
4. Experiment with **Presets** or fine‑tune individual settings.  
5. The FPS overlay shows real‑time numbers.

## ⚠️ Warnings

- The **Danger Zone** options are **permanent** – they delete objects and can’t be undone without rejoining.
- Auto‑Mode may conflict with some games that rely on dynamic lighting.
- This script does **not** bypass anti‑cheat; use at your own risk.

## 📜 License

**All Rights Reserved.**  
You may not copy, modify, distribute, or re‑use this code without explicit written permission from the author.

## 🙏 Credits

- UI built with [Fluent](https://github.com/dawid-scripts/Fluent) by dawid‑scripts.
- Save & Interface managers from Fluent ecosystem.
- Original engine concept by s3amm3r.
 
## Info about the script
- The whole script was just tested in baseplate games in roblox
- if you find problems or want me to improve/update it DM me
---

**Enjoy smooth gameplay.**
