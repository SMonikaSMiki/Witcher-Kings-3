<p align="center">
  <img src="https://raw.githubusercontent.com/kgsherman/Witcher-Kings-CKIII/main/thumbnail_inverted.png" alt="Witcher Kings Logo">
</p>

## Installation

1. Clone this repo into your `/mod/` folder.
2. Move `Witcher Kings.mod` into the `/mod/` folder.
3. Change the `path` line in `Witcher Kings.mod` with the mod's file path on your system.

## Usage
Alpha version 0.1.0 exists as a map-replacement SUBMOD of the Witcher's Realms mod project. This means in order to run the mod you will need to enable the Witcher's Realms mod above this in the load order.

## Editing Terrain
After editing terrain, the game generates two files: `detail_index.tga` and `detail_intensity.tga`. These are used for displaying terrain properly outside of the map editor, however they are not compressed, resulting in large file sizes. Instead of using LFS or zipping the files, open them in an image editor (i.e GIMP) and export with RLE compression.
