<img align="right" src="https://github.com/acidanthera/OpenCorePkg/raw/master/Docs/Logos/OpenCore_with_text_Small.png" alt="OpenCore 0.6.3" width="225">

# ASUS-X550VC-Hackintosh
The repo aims to provide EFI files for ASUS X550VC laptop. Tested working on Big Sur.
<br>
please give it a star if you find it helpful !
<br>
![Last Commit](https://img.shields.io/github/last-commit/FawenYo/ASUS-X550VC-Hackintosh.svg?color=green&label=last-commit)
![OpenCore](https://img.shields.io/badge/OpenCore-v0.6.3-green)
![MacOS](https://img.shields.io/badge/Mac%20OS-v11.0.1%20(20B29)-blue)
![Screenshot](https://i.imgur.com/UTejby1.png)
## Notes
Consider the trend and future of hackintosh, the project has been shifted to OpenCore and won't update Clover anymore.
<br>
(IMPORTANT!!!) If you can't adjust brightness or sound via FN keys, try to use [Karabiner](https://karabiner-elements.pqrs.org/) to fix it.

## Hardware
|     Name     |        Model        |
| :----------: | :-----------------: |
|     CPU      |      Intel(R) Core(TM) i5-3230M CPU @ 2.60GHz      |
|     IGPU     |      Intel HD Graphics 4000      |
|     GPU      |      NVIDIA 720M      |
|     RAM      |      4GB onboard + 8GB DDDR3      |
|     Storage  |      SSD TEAML5Lite3D1T 1TB      |
|     Network  |      Originally AR9485 (work but really slow... ), replaced with DW1550/BCM94352HMB|
|     Display  |      15.6" HD 60Hz, 1366 x 768      |
|     Sound    |      Realtek ALC270      |
|     Ethernet |      Qualcomm Atheros, AR8161 Gigabit Ethernet      |

## BIOS Configur
* `Advanced - USB Configuration - XHCI Pre-Boot Mode` **Enabled**
* `Advanced - USB Configuration - Legacy USB Support` **Enabled**
* `Boot - Launch CSM` **Disabled**
* `Security - Secure Boot Control` **Disabled**

## What's working
* CPU power management
* Wi-Fi & Bluetooth & Ethernet
* HDMI (video & audio) / VGA
* Sound
* Touchpad (+gestures)
* USB Ports
* Battery percentage
* Sleep & Wake (It takes me about 30 secs to completely sleep however)
* Microphone
* FN keys
* 3.5mm jack
* iCloud, iMessage, FaceTime
* Camera
* Airdrop, HandOff (May need to replace WLAN chip)

## Bugs/not working
* NVIDIA GPU, Apple has removed NVIDIA support since 10.13, so it won't be fixed.


## References
* https://www.imacpc.net/archives/1617
* https://applelife.ru/threads/asus-x550vc-i-asus-x550cc.41752/
