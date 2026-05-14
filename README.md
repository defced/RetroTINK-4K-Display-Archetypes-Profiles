# RetroTINK-4K-Display-Archetypes-Profiles
A personal collection of Retrotink 4K Pro profiles designed to emulate a wide range of historical display technologies — from professional broadcast CRT monitors and consumer televisions to arcade cabinets, PC monitors, handheld screens, and early flat panels.


**PHILOSOPHY**
These profiles are artistic recreations built from research, archival references, period photography, video documentation, and personal experience growing up with these displays throughout the 80s, 90s, and early 2000s.
They are not laboratory-calibrated reproductions. Instead, they aim to recreate the feeling, atmosphere, and visual identity of the original displays rather than strict scientific accuracy.

Due to technical limitations of the RetroTINK 4K (for example, the inability to reproduce LCD motion trailing), some characteristics cannot be perfectly replicated.

The goal of these profiles is to capture the spirit and personality of the original hardware as faithfully as possible within the capabilities of the device.

**HOW TO INSTALL**
Installing the profiles:
Copy the folder located inside the "profile" directory into the "profile" folder of your RetroTINK 4K SD card.

You may rename the profile folder if you want.

Installing the required masks:
Copy the "defced_archetypes" folder into the "mask" folder of your RetroTINK 4K SD card.

Do not rename this folder, otherwise the profiles will not be able to locate and load the masks correctly.

The "Mono Masks" and "RGB Masks" folders contain masks used by some profiles, but these should already be included by default on the RetroTINK 4K.

If they are missing, simply copy both folders into the "mask" folder of the RetroTINK 4K SD card.


**REQUIRED SETUP**
These profiles were created and tuned using a MiSTer FPGA connected to an LG C1 OLED in 4K HDR with Black Frame Insertion (BFI) enabled.

They should still work well on most OLED displays, but for the intended rendering, the following setup is recommended:

MiSTer FPGA:
In mister.ini, set:
direct_video=1

This is highly recommended for optimal image quality and signal accuracy.

TV Setup:
- Enable Game Mode or Game Optimizer
  (On LG TVs: All Settings → General → Game Optimizer)

- Enable Black Frame Insertion (BFI)
  (On LG TVs: set OLED Motion Pro to High)

- Disable VRR (Variable Refresh Rate)

These profiles are specifically optimized for HDR usage with BFI enabled, which significantly darkens the image.
If you are not using BFI, you can lower the SMPTE 2084 (PQ) value in the RT4K Color Correction menu to around 1000 nits for a more balanced brightness level.

All profiles were created and tested using RetroTINK 4K firmware version 1.9.6.


