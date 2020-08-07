![attiny85 VLC media player logo](attiny85-vlc-player-logo.png)


# VLC/Media player IR Remote - homemade usb stick

 This project for `ATtiny85` USB stick + `TL1838` IR Receiver Module or compatible.  
 The stick can be controlled from the `Skyline TV` remote control and others with a similar remote control, VLC player or standard Media Player on Windows 10.  
 No software required for Windows 10 or special drivers.  
 IR Remote for **PC**, **Linux**, **Android**, **Mac**(?), tested on Windows 10.

## Features and Capabilities:

- `rewind` in both directions,
- `previous`/`next` track,
- `play`/`pause`/`stop`,
- PAD support: `right`, `left`, `up`, `down`, `ok`
- change volume, `mute`,
- menu - Menu button,
- change player type: `VLC` or `Media player` (`BLUE` button), `VLC` is default,
- print screen (`YELLOW` button) or `On`/`Off` `IR` receive command,
- PC wakeup (`GREEN` button),
- PC sleep (`RED` button),
- exit full screen mode (`ESC`)

## Required:

- `ATtiny85` USB stick - 1 pcs.
- `TL1838` IR Receiver Module - 1 pcs.  
- [TrinketHidCombo Adafruit library](https://github.com/CloneTV/VLC-Media-player-IR-Remote-ATtiny85/tree/master/lib)  
- [TrinketKeyboard Adafruit library](https://github.com/CloneTV/VLC-Media-player-IR-Remote-ATtiny85/tree/master/lib)  
- `TrinketKeyboard` library required only for build [`IR Scanner`](https://github.com/CloneTV/VLC-Media-player-IR-Remote-ATtiny85/blob/master/src/IR-Scanner-ATtiny85.ino) part.
- IR Remote control from TV or another, required `NEC` protocol.

## Skyline TV remote:

![screenshot Skyline remote](remote-skyline.png)

## VLC advanced settings:

![screenshot VLC settings](vlc-interfaces.png)

## LICENSE

MIT
