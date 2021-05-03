# TCX-Reference
Reference design and source code for TCX low-cost general purpose computer. More than a one-off computer, it is meant to inspire the creation of other machines based on the same specification. For that purpose, the design and requirements of individual cores are clearly described. This allows not only compatible implementations (for example, emulation or hardware), but also the usage of individual cores on other projects.

## Features

- Affordable design philosophy
- TF card interface
- USB interface for controllers
- Tile-based display with sprite support
- Composite video as main output
- AY compatible audio output with additional wavetable channels.

## Models

Current models:
* TC-3004 (30Mhz Cortex M0+, 16K ROM, 4K RAM, 4K VCore, 1xSoundCortex) - Prototype (v1, v2)
![image](https://user-images.githubusercontent.com/5050761/116898799-1cb90b80-ac37-11eb-92da-44ba474c4a2c.png)

Future models:
* TC-3016 (30Mhz Cortex M0+, 64Kb ROM, 16Kb RAM, 8K VCore, 1xSoundCortex) - Production Model (in development)
* TC-3128 Plus (150Mhz Cortex M0+, 256Kb ROM, 96Kb RAM, 16K VCore, 2xSoundCortex) - Top range model (early design)
