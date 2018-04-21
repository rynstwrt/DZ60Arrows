# QMKFirmwareForCode
Love 60% keyboards that use the QMK firmware? Need media controls and arrow keys? Feel free to use my custom solution!

## QMK-Firmware
This is a keymap for the DZ60 PCB written in C for QMK. You must install QMK Firmware from [here](https://github.com/qmk/qmk_firmware) first. 

## The Layout
A standard 60% layout with the POK3R's arrow key functionality. Caps lock is now a function key, meaning you can use CAPSLOCK + I/J/K/L to move the cursor up, left, down, and right respectively.

## Kinda finicky?
Keys swapped or just not working? You might have your keyboard in the wrong behavior. To reset this (not the firmware, just the behavior) hold SPACE + BACKSPACE while you plug in your keyboard.

#### Firmware Keys
CAPSLOCK + \ = RESET

#### Function Keys
CAPSLOCK + 1 = F1

CAPSLOCK + 2 = F2

CAPSLOCK + 3 = F3

CAPSLOCK + 4 = F4

CAPSLOCK + 5 = F5

CAPSLOCK + 6 = F6

CAPSLOCK + 7 = F7

CAPSLOCK + 8 = F8

CAPSLOCK + 9 = F9

CAPSLOCK + 0 = F10

CAPSLOCK + - = F11

CAPSLOCK + + = F12

#### Media Controls
CAPSLOCK + Q = Last media track

CAPSLOCK + W = Pause media track

CAPSLOCK + E = Next media track

#### PCB Underglow Controls
CAPSLOCK + Z = Toggle LEDs on/off

CAPSLOCK + X = Change LED modes

CAPSLOCK + SHIFT + X = Change LED modes backwards

CAPSLOCK + C = Increase hue 

CAPSLOCK + V = Decrease hue

CAPSLOCK + B = Increase saturation

CAPSLOCK + N = Decrease saturation

CAPSLOCK + M = Increase brightness

CAPSLOCK + , = Decrease brightness

### Misc Controls
CAPS + ESC = \`

SHIFT + ESC = ~

CAPS + P = PrintScr

CAPS + H = Home

## Where do I put this folder?
Put it under your keyboard's directory in your QMK folder. For example, mine is: `C:\Users\Ryan\Desktop\qmk-qmk_firmware-4cb7907\keyboards\dz60\keymaps\QMKCode`.

## What if I just want the .hex file?
Put the QMKCode.hex into your QMK folder's main directory and flash it to your keyboard.

## How do I build the folder?
In your favorite environment (like MSYS2), run `make <yourkeyboard/PCB>:QMKCode:<PCBType>`. For a DZ60, for instance, you would run `make dz60:QMKCode:dfu`. 
