# Contributing to Yolk Keychain

Thank you for your interest in this project! 🐣

This PCB keychain features **Yolk**, the beloved character from [_Leap Day_](https://nitrome.fandom.com/wiki/Leap_Day).  
The design was built in Figma with several layers: the outline, the yellow body, and the rest of the character.

## Open contributions

There are two areas where help would be very welcome:

### 🟡 Gold layer — yellow part

The yellow body of Yolk could benefit from a **gold (ENIG) layer** to really make it shine on the PCB.  
The challenge is creating the correct copper/mask shapes in Figma (or your EDA tool of choice) so that the yellow area is exposed as gold rather than covered by soldermask.

If you manage to get the masks right and produce a clean gold layer for the yellow part of the drawing, your contribution is more than welcome!

### ⚪ Embossed layer — head or eyes

Adding an **embossed (raised copper / exposed pad) layer** to the head or the eyes of Yolk would give the keychain a really nice tactile feel and visual depth.  
This requires proper footprint/mask work to expose the copper in those specific areas.

If you can pull this off, please open a pull request!

## How to contribute

1. **Fork** the repository and create a new branch from `main`.
2. Make your changes to the design files (Figma sources are in the `attachments/` folder; EasyEDA/PCB files are in `src/` and `production/`).
3. Document what you changed and why in your pull request description.
4. Open a **Pull Request** — describe the layer(s) you added and include screenshots or renders if possible.

## Questions

Feel free to open an **Issue** if you have questions or want to discuss an approach before starting.  
All skill levels are welcome — whether you're a PCB design veteran or just learning EDA tools! 🎉
