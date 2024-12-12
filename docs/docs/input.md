Built with SDL2, xemu supports virtually all gamepads. Connect up to 4
controllers at any time, just like a real Xbox.

!!! note "Notes & FAQ"
    * There is currently no interface within xemu to adjust the keybindings.
    * Hot plugging works on Windows and Linux. It is broken on macOS.
    * USB passthru is not supported yet, but it will be coming.
    * Only the Xbox controller is emulated. There is not (yet) support for other controllers like the Steel Batallion.

!!! bug "Input not functional on early BIOS revisions"
    Emulated gamepads may be non-functional when using early BIOS revisions
    (<4627). It is recommended to not use these early BIOS revisions,
    until this bug is fixed.


## Popular Gamepads

### Xbox One, Xbox 360 controllers

On Windows and Linux they should be supported out of the box. On macOS you will
need to install an additional driver.

* macOS: [360Controller](https://github.com/360Controller/360Controller)

### Original Xbox controllers

The original Xbox controllers are USB-compatible and can be connected to a PC
with an adapter. Please don't cut original Xbox controller cables to make an
adapter. Quality adapters [can be purchased on Amazon](https://www.amazon.com/Mcbazel-Replacement-Xbox-Controller-Adapter-Microsoft/dp/B000RT2868)
for about $12 USD or from eBay for about $8 USD, shipped globally.

Depending on your platform, you may also need to install additional drivers:

* Windows: [Xb2XInput](https://github.com/emoose/Xb2XInput)
* macOS: [360Controller](https://github.com/360Controller/360Controller)
* Linux: Usually supported out of the box (xpad).

### DualShock 4 controllers

Sony DualShock 4 controllers work, out of the box, on all platforms. No
additional installation of drivers or configuration is required.

## Keyboard as Gamepad

The keyboard layout for the gamepad is:

| Keyboard  | Gamepad       | Keyboard  | Gamepad       |
|-----------|---------------|-----------|---------------|
| A         | A             | BACKSPACE | BACK          |
| B         | B             | RETURN    | START         |
| X         | X             | 1         | WHITE         |
| Y         | Y             | 2         | BLACK         |
| LEFT      | DPAD_LEFT     | 3         | LSTICK        |
| UP        | DPAD_UP       | 4         | RSTICK        |
| RIGHT     | DPAD_RIGHT    | 5         | GUIDE (xemu Nav) |
| DOWN      | DPAD_DOWN     |           |               |

```
      Left                 Right

    W = LTrig                   O = RTrig
       E                     I
    S     F               J     L
       D                     K
```
