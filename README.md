# DZ60 Arrows

Custom DZ60 Keyboard PCB Firmware. Written by Ryn.

> ### Instructions on how to flash the firmware can be found in [INSTALL.md](INSTALL.md).


<br>
<br>


## How to Use:

> ### Notes:
> - **Layer 0** (regular keyboard with no modifier keys pressed) is standard, except that the Caps Lock key and the key to the right of the OS key are function keys.
> 
> 
> - **Layer 1** is accessed by pressing and holding a function key.
>   - For example, to use the arrow keys, you could press and hold the Caps Lock key and use I, J, K, and L as your arrow keys.

<br>


### Arrow Key Keybinds:
| **FUNCTION** | **KEYBIND** | 
|:-------------|:-----------:|
| Up Arrow     | Mod key + I |  
| Down Arrow   | Mod key + K |  
| Left Arrow   | Mod key + J |
| Right Arrow  | Mod key + L |


<br>

### General Keybinds:
| **FUNCTION** |             **KEYBIND**             | 
|:-------------|:-----------------------------------:|
| F[1-12]      |        Mod key + [0-9, -, =]        |
| Caps Lock    |         Mod key + Caps Lock         |  
| Delete       |         Mod Key + Backspace         |
| Print Screen |             Mod key + P             |
| Home         | Mod key + H <br>*OR*<br>Mod key + ; |  
| End          |             Mod Key + .             |
| Page Up      |             Mod key + '             |
| Page Down    |             Mod key + /             |
| ` character  |          Mod key + Escape           |
| ~ character  |      Mod key + Shift + Escape       |

<br>

### Media Keybinds:
| **FUNCTION** | **KEYBIND** | 
|:-------------|:-----------:|
| Play/Pause   | Mod key + W |  
| Previous     | Mod Key + Q |
| Next         | Mod key + E |
| Volume Up    | Mod key + ] |  
| Volume Down  | Mod Key + [ |


<br>

### LED Keybinds:
Coming soon.


<br>
<br>


## How to Navigate This Repository:

> ### Each folder contains:
> - The .hex file needed to flash the firmware
>
>
> - A .json file to be used with [QMK Configurator](https://config.qmk.fm/#/dz60/LAYOUT_60_ansi) to make edits
>
>
> - A folder of screenshots for each layer of the firmware.
>
>
> - A CHANGELOG.md file to see the updates made in that version.
>
>
> - A README.md file that displays the screenshots of the firmware.