<p align="center">
  <img src="https://raw.githubusercontent.com/kgsherman/Witcher-Kings-CKIII/main/thumbnail_inverted.png" alt="Witcher Kings Logo">
</p>

## Installation

1. Clone this repo into your mod folder.
2. Move `Witcher Kings.mod` into the `mod\` folder.
3. Change the `path` line in `Witcher Kings.mod` with the mod's full file path.

## Committing TGAs
After editing terrain, the game generates two files: `detail_index.tga` and `detail_intensity.tga`. These are used for displaying terrain properly outside of the map editor, however they are not compressed, resulting in large file sizes. Instead of using LFS or zipping the files, open them in an image editor (i.e GIMP) and export with RLE compression.
