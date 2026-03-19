# Dactyl v4

Custom split ergonomic keyboard project based on a Dactyl Manuform-style shell, adapted around a flexible main PCB, a custom thumb cluster, and trackball support.

This repository contains the KiCad design files, printable case parts, and reference images used during the build.

## Overview

This project is my own Dactyl-style keyboard design. The main board is a custom flexible PCB, while the extra keys and thumb-cluster approach were informed by an existing open hardware reference.

Design references used for this build:

- Dactyl Manuform base shape and layout:
[ryanis.cool keyboard link](https://ryanis.cool/cosmos/beta#cm:Ct0CCigSDhDwbSA7QABIAGIDRjEwEgUQgG8gJxICIBMSAiAAEgA4HkCAwuADCicSDRDwYSA7QABIAGICRjkSBRCAYyAnEgIgExICIAASAxCwOzgKQAAKKhINEPBVIDtAAEgAYgJGOBIFEIBXICcSAiATEgIgABIDELAvOAlAgPC8AgokEg0Q8EkgO0AASABiAkY3EgUQgEsgJxICIBMSAiAAEgA4HUAACiQSDRDwPSA7QABIAGICRjYSBRCAPyAnEgIgExICIAASADgxQAAKPRIKEHAYRSA7QABIABIJEIABICdiAkYxEgIgExIMCIA4IABIgPoaWIMGEg8IgDBArYDMA0iA6iJY6wVQuQUKQxIIEHAgO0AASAASCRCAASAnYgJGMRIKCIAwIBNAHlioBBIMCIAoEKCACiAAWI4EEgoIgEAQMEAdWNoEQIDKkRRQ9gMYAEDohaCu8FVI2pyKMArEAQolEhkIgEAQQBjADED2ibjaBkian9SG0bATUPICMIAoOMAMQJaKAQodEhMQwIACIChA7Ye0xIAISICAtL8BOKgUQICA0AEKJhIZCIAgEEAYkBwgKEDeiYy1wFNI0IukptCxBzCAKDiQHEC/qJwBChoSEBBAIChA6IektcAHSICAhFw4+CNAgIDgDAodEhMQQCAAMMgBQJTOkuApSICAsKwBMBY4AEC1mAYYCiIJCAAQyAEYACAAQLGfoI2QBEiEj5TWoHgKwAIKJxINEPABIDtAAEgAYgJGMRIFEIADICcSAiATEgIgABIAOB1AgMLgAwokEg0Q8A0gO0AASABiAkYyEgUQgA8gJxICIBMSAiAAEgA4CUAACicSDRDwGSA7QABIAGICRjMSBRCAGyAnEgIgExICIAASADgKQIDwvAIKJBINEPAlIDtAAEgAYgJGNBIFEIAnICcSAiATEgIgABIAOB5AAAokEg0Q8DEgO0AASABiAkY1EgUQgDMgJxICIBMSAiAAEgA4MkAACiYSChBwGEYgO0AASAASChCAbSAnYgNGMTASAiATEgIgABIAOEZAAApEEggQcCA7QABIABIOEIBtGDEgJ0hBYgNGMTASCAiAMCATWKUEEgwIgDgQoIAKIABYvwQSCQiAQBAwGDtARTgxQIDKkRQYAUDnhaCu8FVI2pqKKAqOAQofEgcQQCAOQMMNEhIIgDggBUDn3gZIgIC43wNYlAI4FAorEhIQwIACGABAgqIHSICAkP0DUHISEwiAOBBAGABAgFZIgICg7ANQhQE4AAohEhIQQEDzpItISICAkP0DUFpYlQESCQiAICAPQIKcCzgTGAMiCgjIARDIARgAIABAto/MpvA1SJuPuN6gmhwiBSCEByguggECBAJYR2gA)
  ``
- Extra key and thumb-cluster inspiration:
  `https://github.com/swanmatch/MxLEDBitPCB/blob/master/readme_en.md`

## Gallery

### 3D keyboard visualization

![3D keyboard visualization](pictures/3d_keyboard_visualization.png)

### Main flexible PCB

![Main PCB](pictures/main_PCB.png)

### Extra keys / thumb cluster reference

![MxLEDBitPCB reference for extra keys](pictures/MxLEDBitPCB_for_extra_keys.png)

## Repository Contents

- `dactyl_v4/3dForm/printfiles/` contains the printable case, plate, and holder STL files.
- `dactyl_v4/Kicad/flex/` contains the main KiCad project for the flexible PCB design.
- `pictures/` contains reference renders and PCB images used in this README.

## Hardware Summary

- Split ergonomic Dactyl-style keyboard
- Custom flexible main PCB
- Separate thumb / extra-key area inspired by MxLEDBitPCB
- Trackball support using a PMW3360 or PMW3389 sensor
- Dual RP2040 controller setup with TRRS interconnect

## Bill of Materials

Prices below reflect the sourced parts actually purchased for this build. Items not covered by that list are left blank.

| Category | Item | Qty | Notes | Total |
| --- | --- | ---: | --- | ---: |
| Keys and switches | Womier Retro Brown Gray PBT keycap set | 1 | 138-key Cherry-profile set | 51.39 PLN |
| Keys and switches | PBTfans Doppelganger 40s kit | 1 | Child kit, 40s | 77.19 PLN |
| Keys and switches | MX-compatible switches | 90 | Outemu Silent Cream Yellow Pro, bought as one 90-pack | 71.19 PLN |
| Keys and switches | 1N4148 diodes | 100 | 1N4148W T4 SOD-123, bought as one 100-pack | 5.72 PLN |
| Pointing device and mechanical parts | 34 mm trackball | 1 | GBALL34RN, purple | 47.79 PLN |
| Pointing device and mechanical parts | PMW3360 or PMW3389 sensor | 1 | PMW3389 module | 69.19 PLN |
| Pointing device and mechanical parts | 3 x 6 x 2.5 mm bearings | 5 | Bought as one 5-pack | 9.41 PLN |
| Pointing device and mechanical parts | 3 x 8 mm dowel pins | 10 | M3, bought as one 10-pack | 4.90 PLN |
| Pointing device and mechanical parts | Tindie-supported PCB for sensor assembly | 1 | Use a compatible board as required by the sensor setup |  |
| Electrical | RP2040 Black Board USB-C | 2 | Aliexpress boards |  |
| Electrical | PJ-320A TRRS connectors | 10 | Bought as one 10-pack | 6.29 PLN |
| Electrical | TRRS cable | 1 | 3.5 mm TRRS spring coiled cable, 90-degree male-to-male | 13.99 PLN |
| Electrical | Flexible PCB fabrication | 1 | Main flex PCB, converted from 30 USD | 110.61 PLN |
| Electrical | Extra PCB fabrication | 1 | Auxiliary PCB, converted from 2 USD | 7.37 PLN |
| Electrical | Kailh hot-swap sockets | 3 | 40-piece packs, CPG1511 | 45.03 PLN |
| Electrical | SK6812MINI-E LEDs | 1 | 100-piece lot | 34.89 PLN |
| Electrical | Wire-wrap or magnet wire spool | 1 | Internal wiring |  |
| Mounting | M3 x 6 mm flat head screws | 18 | Bottom plate and microcontroller holder |  |
| Mounting | M3 x 8 mm flat head screws | 2 | Microcontroller holder through bottom plate |  |
| Mounting | M3 screw inserts | 20 | Heat-set or press-fit, depending on print and process |  |
| Other parts | 3D print service | 1 | Case and related printed parts | 100.00 PLN |

**Summary price:** 654.96 PLN

## Attribution

This repository is a custom project, but it explicitly builds on ideas and references from the following sources:

- Ryanis Cosmos for the Dactyl Manuform base geometry and layout exploration
- Swanmatch MxLEDBitPCB for ideas around extra keys and thumb-cluster implementation

The main board design in this repository is my own custom flexible PCB adaptation.

## License

This repository is distributed under the license included in [LICENSE](LICENSE).
