# Metro Exodus SDK Substance Painter Export Presets

Welcome to this collection of **Substance Painter presets** crafted to adapt your textures for **Exodus SDK**! 

## Preset Overview

### Exodus SDK (Standard material)

This preset configuring the _bump (**bump map**) with the following channel setup:

- 🟥 **Red**: `User1` (White)
- 🟩 **Green**: Glossiness
- 🟦 **Blue**: `User1` (White)
- ⬛ **Alpha**: Height

It will export the following maps:
  - `$TextureSet` (Color map)
  - `$TextureSet_bump` (Bump map)
  - `$TextureSet_nm` (Normal map)

> **Tips:**
> 
> Ignore the warning "`User1` channel is missing in your texture set"` for this preset.
> 
>  `_nm` is combined normal map in DirectX format of the baked normal and the Texture Set's normal channel.
>
>  In `User1` you can draw Detail mask, Material mask. (not verified)
---

### Other Presets

### Exodus SDK (Standard material + f0)

This preset configuring the _bump (**bump map**) with the following channel setup:

- 🟥 **Red**: `User1` (White)
- 🟩 **Green**: Glossiness
- 🟦 **Blue**: f0 (Reflectivity)
- ⬛ **Alpha**: Height

It will export the following maps:
  - `$TextureSet` (Color map)
  - `$TextureSet_bump` (Bump map)
  - `$TextureSet_nm` (Normal map)

## How to Import Presets

### Option 1: Import via Substance Painter

1. Clone this repository and copy all files to your system.
2. Open **Substance Painter**.
3. Go to **File > Import Resources**, then select `.spexp` file.
4. Choose **Shelf** as the destination and click **Import**.

You can also drag & drop it directly into the software. 

---

### Option 2: Add Files Manually

1. Locate your Substance Painter **shelf** directory:
   - **Windows**: `C:\Users\[username]\Documents\Adobe\Adobe Substance 3D Painter\assets\export-presets`
2. Copy all `.spexp` files into the appropriate folder.

---

## Contributing

Have ideas or improvements? Feel free to contact me on Discord: **shemich**.  
Your contributions to these export presets are always welcome!
