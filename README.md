# Jafo 3 Pro

An Ender 3 Pro upgraded with:

- SKR Mini E3 V2.0
- Creality Sprite Hotend/Extruder
- CR-Touch

This repo includes a Klipper config for this printer.



CONFIG STUFF:


Added custom G-CODE to the PETG filament settings in my slicer:

```
G1 Z0.02 F500 ; Go to the level of 0.2 mm + your paper thickness
G92 Z0       ; This redefines the zero Z level
```
