# Resource packs

A collection of highly customized 1.21.11 resource packs using the latest pack formats (`69` for 1.21.9 and `75` for 1.21.11).

As of version 25w31a (first 1.21.9 snapshot; July 29, 2025), the recommended `pack.mcmeta` configuration is:

```mcmeta
{
  "pack": {
    "min_format": 69,
    "max_format": 75,
    "description": "Pack description"
  }
}
```

Pack descriptions now all use the `\u00A7` color notation instead of `§`. See the [wiki](https://minecraft.wiki/w/Formatting_codes) for more info about formatting codes.

## brighter-dark-mode-text

Replaces `.fsh` fragment shaders with `.vsh` vertex shaders to fix the text visibility in the
[Default Dark Mode](https://modrinth.com/resourcepack/default-dark-mode) resource pack. Uses the [VanillaTweaks](https://vanillatweaks.net/picker/resource-packs) implementation. The color I chose is `0xe0e0e0` which can be modified in `assets\minecraft\shaders\include\brighter_text\main.vsh`.

## visible-hopper-state

Adds visual indicators (red lines) to locked hoppers. Uses textures from:

- [VanillaTweaks](https://vanillatweaks.net/picker/resource-packs) for the arrow design
- [Redstone Tweaks](https://modrinth.com/resourcepack/redstone-tweaks) by [RexxStone](https://www.youtube.com/@RexxStone) for some locked textures

## menu-colors

Adds color to some UI elements (buttons, menu options, etc.) for some better readability. Inspired by [ColorCraft](https://modrinth.com/resourcepack/textcolorcraft).
