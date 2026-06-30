# Resource packs

A collection of highly customized resource packs using the latest pack formats.

See the [wiki](https://minecraft.wiki/w/Pack_format#List_of_pack_formats) for more details on pack format numbering. Currently the following format numbers are used.

- `88` for 26.2
- `84` for 26.1.x
- `69` - `75` for 1.21.9 - 1.21.11

As of version 25w31a (first 1.21.9 snapshot; July 29, 2025), the recommended `pack.mcmeta` configuration is:

```mcmeta
{
  "pack": {
    "min_format": 69,
    "max_format": 88,
    "description": "Pack description"
  }
}
```

Pack descriptions now all use the `\u00A7` color notation instead of `§`. See the [wiki](https://minecraft.wiki/w/Formatting_codes) for more information about formatting codes.

## ~~brighter-dark-mode-text~~

*Deprecated:* No need for this pack anymore, replaced by **better-dark-mode**.

Replaces `.fsh` fragment shaders with `.vsh` vertex shaders to fix the text visibility in the
[Default Dark Mode](https://modrinth.com/resourcepack/default-dark-mode) resource pack. Uses the [VanillaTweaks](https://vanillatweaks.net/picker/resource-packs) implementation. The color I chose is `0xe0e0e0` and can be modified in `assets\minecraft\shaders\core\rendertype_text.vsh`.

## better-dark-mode

My customized version of the [Default Dark Mode](https://modrinth.com/resourcepack/default-dark-mode) resource pack.

- Changed the text color to `0xe0e0e0` for better visibility. This can be modified in `assets\minecraft\shaders\core\rendertype_text.fsh`.
- Removed `rendertype_text_intensity.vsh`.
- Removed every mod I don't use.

## visible-hopper-state

Adds visual indicators (red lines) to locked hoppers. Uses textures from:

- [VanillaTweaks](https://vanillatweaks.net/picker/resource-packs) for the arrow design
- [Redstone Tweaks](https://modrinth.com/resourcepack/redstone-tweaks) by [RexxStone](https://www.youtube.com/@RexxStone) for some locked state textures

## menu-colors

Adds color to some UI elements (buttons, menu options, etc.) for some better readability. Inspired by [ColorCraft](https://modrinth.com/resourcepack/textcolorcraft).
