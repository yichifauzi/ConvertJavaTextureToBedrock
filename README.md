THIS PROJECT IS NO OFFICIAL MINECRAFT PRODUCT - NOT AUTHORIZED OR ASSOCIATED BY MOJANG

---

# Convert Minecraft Java texture packs to Bedrock texture packs

## Description
It supports the follow Minecraft versions:

| Minecraft | Version |
|-----------|---------|
| Java | v1.13.x, v1.14.x or v1.15.x |
| Bedrock | v1.14.x |

This project is inspired by the no longer continued [PCTexture2PE](https://github.com/rodrigojxd/PCTexture2PE)

It supports to convert blocks, items, entities, paintings, particles, map icons, mob effects and hotbar

Some conversions of HD texture packs may takes a while

You need a device with corresponding enough RAM (like the file size and content of the texture pack), because the convert it is not stored in a temporary storage, but in the RAM memory

Shaders or OptiFine or 3d textures or mods or datapacks are not supported, only classic Vanilla textures

Snapshots versions may are also not supported

Please reopen Minecraft after selecting the converted texture pack, because in the current version it seems to be a bug to reload the texture cache (Otherwise it's possible that you will have a mix between your previous and new texture pack, which can lead to appearance bugs that would not occur)

If it crashed, it doesn't necessarily have to do with the texture pack and this converter can't do much if it should be a bug in Minecraft

Some experimental conversions are disabled by default, but can be enabled if you want to try, but please be warned, it contains many bugs and may are not beautiful and may not usable:
- UI
    - Buttons
    - Tabs
    - Dialogs
    - Inventory / Recipe book
    - Crafting tables

## Web app
Look at https://ozelot379.github.io/ConvertJavaTextureToBedrock

Works in a current browser.

Tested browsers:
- Desktop:
  - Chrome (General Chromium based browsers should work, like Opera, new Edge, ...)
  - Firefox
  - Safari
- Mobile:
  - iOS (Safari)
  - Android (Chrome)

Internet Explorer or old Edge are not supported!

## CLI
Look at https://github.com/ozelot379/ConvertJavaTextureToBedrockCli

## API
Look at https://github.com/ozelot379/ConvertJavaTextureToBedrockApi

## Report issue
Use github repo issues (https://github.com/ozelot379/ConvertJavaTextureToBedrock/issues/new/choose)
