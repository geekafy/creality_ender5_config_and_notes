#Documentation/notes on things relating to my Creality Ender 5 3D printer setup


Included are my config files for Marlin. The include multiple tweaks I found all over the Interwebs, including, but likely not limited to:

- [Teaching Tech: Ender 3 BLtouch vanilla Marlin guide](https://www.youtube.com/watch?v=sUlqrSq6LeY&t=324s)
- [Teaching Tech: BLtouch advanced guide: Fully automated bed homing and levelling](https://www.youtube.com/watch?v=BV11-VOQjMc)
- [Marlin 2.0 program memory usage by feature on AVR 8Bit boards](https://www.crosslink.io/marlin-2-0-memory-usage-by-feature/)

### My current setup:

- Creality Ender 5
- Creality 1.1.4 stock controller board (8-bit)

#### Mods:

- [Genuine BL Touch w/ mounting kit](https://www.creality3dofficial.com/products/creality-bl-touch)
- [Creality glass bed](https://www.creality3dofficial.com/products/creality-new-upgraded-heated-bed-build-plate-surface)
- [Capricorn bowden tubing](https://www.amazon.ca/gp/product/B07XXRVGP9/ref=ppx_yo_dt_b_search_asin_title)
- [Simple hot end fix](https://www.youtube.com/watch?v=7tCxO17XZtw)
- [Super Struts Remixed](https://www.thingiverse.com/thing:3661405)

### Coming soon:
- BigTreeTech SKR 1.4 w/ TMC2209
- BigTreeTech TFT35
- [Hero Me Gen 3](https://www# My Ender 5 Config and Notes

Included are my config files for Marlin. The include multiple tweaks I found all over the Interwebs, including, but likely not limited to:

- [Teaching Tech: Ender 3 BLtouch vanilla Marlin guide](https://www.youtube.com/watch?v=sUlqrSq6LeY&t=324s)
- [Teaching Tech: BLtouch advanced guide: Fully automated bed homing and levelling](https://www.youtube.com/watch?v=BV11-VOQjMc)
- [Marlin 2.0 program memory usage by feature on AVR 8Bit boards](https://www.crosslink.io/marlin-2-0-memory-usage-by-feature/)

### My current setup:

- Creality Ender 5
- Creality 1.1.4 stock controller board (8-bit)

#### Mods:

- [Genuine BL Touch w/ mounting kit](https://www.creality3dofficial.com/products/creality-bl-touch)
- [Creality glass bed](https://www.creality3dofficial.com/products/creality-new-upgraded-heated-bed-build-plate-surface)
- [Capricorn bowden tubing](https://www.amazon.ca/gp/product/B07XXRVGP9/ref=ppx_yo_dt_b_search_asin_title)
- [Simple hot end fix](https://www.youtube.com/watch?v=7tCxO17XZtw)
- [Super Struts Remixed](https://www.thingiverse.com/thing:3661405)

### Coming soon:
- BigTreeTech SKR 1.4 w/ TMC2209
- BigTreeTech TFT35
- [Hero Me Gen 3](https://www.thingiverse.com/thing:3182917)


### Tuning:

- Z-Offset should be calculated and configured. See: [Calibrating Z-Offset With A BLTouch Bed Levelling Probe](https://www.youtube.com/watch?v=y_1Kg45APko) -- Use [zoffset-calibrate.gcode](gcode/zoffset-calibrate.gcode)
- Esteps and flow rate should be calibrated. See: [Esteps and Flow Rate using Octoprint and Free Air Method](https://www.youtube.com/watch?v=HVljfDVPp3o) or [3D Printer Extruder Calibration](https://www.youtube.com/watch?v=xzQjtWhg9VE)
- [Acceleration & Junction Deviation Tuning](https://www.youtube.com/watch?v=Mnvj6xCzikM)
- X/Y/Z Step Calibration. See: [STEP Calibration Piece (X, Y and Z axis)](https://www.thingiverse.com/thing:195604)
- Best bed leveling file. See: [Thingiverse: Ender 3 Bed Level Test](https://www.thingiverse.com/thing:2987803)
- Best misc calibration files. See: [Thingiverse: Ender 3 Calibration Files](https://www.thingiverse.com/thing:3071464)

### Latest Tuning Values:

- Z Probe Offset: -1.4
- Esteps/mm: 95.3
- Flow: 1.14285


### Notes:

- Fantastic guide: [3D Printer Help Guide Creality & Others](https://www.th3dstudio.com/knowledgebase/3d-printer-help-guide-creality-others/)
- [CHEP Cura profiles](https://www.chepclub.com/cura-profiles.html)
.thingiverse.com/thing:3182917)


### Tuning:

- Z-Offset should be calculated and configured. See: [Calibrating Z-Offset With A BLTouch Bed Levelling Probe](https://www.youtube.com/watch?v=y_1Kg45APko) -- Use [zoffset-calibrate.gcode](gcode/zoffset-calibrate.gcode)
- Esteps and flow rate should be calibrated. See: [Esteps and Flow Rate using Octoprint and Free Air Method](https://www.youtube.com/watch?v=HVljfDVPp3o) or [3D Printer Extruder Calibration](https://www.youtube.com/watch?v=xzQjtWhg9VE)
- [Acceleration & Junction Deviation Tuning](https://www.youtube.com/watch?v=Mnvj6xCzikM)
- X/Y/Z Step Calibration. See: [STEP Calibration Piece (X, Y and Z axis)](https://www.thingiverse.com/thing:195604)
- Best bed leveling file. See: [Thingiverse: Ender 3 Bed Level Test](https://www.thingiverse.com/thing:2987803)
- Best misc calibration files. See: [Thingiverse: Ender 3 Calibration Files](https://www.thingiverse.com/thing:3071464)

### Latest Tuning Values:

- Z Probe Offset: -1.4
- Esteps/mm: 95.3
- Flow: 1.14285


### Notes:

- Fantastic guide: [3D Printer Help Guide Creality & Others](https://www.th3dstudio.com/knowledgebase/3d-printer-help-guide-creality-others/)
- [CHEP Cura profiles](https://www.chepclub.com/cura-profiles.html)
