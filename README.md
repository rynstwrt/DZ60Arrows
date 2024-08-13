# DZ60 Arrows

Custom DZ60 Keyboard PCB Firmware written by Ryn.

<br>

## How to Use:
- Layer 0 (regular keyboard use) is standard except that the Caps Lock key and the key to the right of the OS key are function keys.
- Layer 1 is accessed by pressing and holding a function key. 
- For example, to use the arrow keys you could press and hold the Caps Lock key and use I, J, K, and L as your arrow keys.

<br>

## How to Navigate This Repository:
Each folder contains:
- The .hex file needed to flash the firmware
- A .json file to be used with [QMK Configurator](https://config.qmk.fm/#/dz60/LAYOUT_60_ansi) to make edits
- A folder of screenshots for each layer of the firmware.
- A CHANGELOG.md file to see the updates made in that version.
- A README.md file that displays the screenshots of the firmware.

<br>

## How to Flash the Firmware:
1. **Download a version of the firmware.** You only need the .hex file to install, but can upload the .json file to [QMK Configurator](https://config.qmk.fm/#/dz60/LAYOUT_60_ansi) to make edits to the firmware.
2. **Download QMK Toolbox.** You can get it [from here](https://github.com/qmk/qmk_toolbox/releases).
3. Click **Tools > Install Drivers...** in QMK Toolbox.
4. **Click the Open button** and select the downloaded .hex file.
5. **Put your keyboard into DFU mode.** On DZ60s this is usually done by pressing and holding the button on the back.
6. **Click the Flash button.** The firmware will begin to flash to your DZ60.