# LoL-Blender-Tools
Blender plugin for working on League of Legends models

Imports:
 - .skn (+ associated .skl)
 - .bin

Exports:
 - .skn + .skl


Additionally supports **Import** only of **".bin"** files.

You will need:
- [lol2gltf](https://github.com/Crauzer/lol2gltf/releases/latest/)
- [ritobin](https://github.com/moonshadow565/ritobin/releases/latest/)
- [tex2dds](https://github.com/Morilli/Ritoddstex/releases/latest/)

To install inside of blender:
 1) Install lol_blender_tools.zip and the above programs
 2) Inside of blender Edit > Preferences > Add-ons > Install...
 3) Navigate to and select lol_blender_tools.zip
 4) Setup the paths to lol2gltf, ritobin and tex2dds in the addon preferences

Notes for Usage:
 - Importing a .skn will automatically use the associated .skn
 - Animations can be imported alongside the .skn and .skl by enabling a setting in the import menu.
 - Importing a .bin will additionally import associated textures
   - Note: Textures for VFX parts may not work properly
