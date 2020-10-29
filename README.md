# ASUS-X550VC-Hackintosh

![Screenshot](https://i.imgur.com/hZhX70d.png)

## Notes
Clover Version: 5100
<br>
macOS Version: 10.15.7 19H2
<br>
<br>
(IMPORTANT!!!) If you can't adjust brightness or sound via FN keys, try to use [Karabiner](https://karabiner-elements.pqrs.org/) to fix it.

## Hardware
* Model: ASUS X550VC
* CPU: Intel(R) Core(TM) i5-3230M CPU @ 2.60GHz
* Storage: SSD TEAML5Lite3D1T 1TB
* Video: Intel HD Graphics 4000
* Audio: Realtek ALC269
* LAN: Qualcomm Atheros, AR8161 Gigabit Ethernet
* Wifi: Originally AR9485 (work but really slow... ), replaced with DW1550/BCM94352HMB (miniPCI-e)
* RAM: 4GB + 8GB DDR3

## BIOS
* Advanced - USB Configuration - XHCI Pre-Boot Mode {Enabled}  
* Advanced - USB Configuration - Legacy USB Support {Enabled}  
* Boot - Launch CSM {Disabled}  
* Security - Secure Boot Control {Disabled}

## What's working
* CPU power management
* Wi-Fi
* HDMI (video & audio) / VGA
* Brightness control
* Sound
* Touchpad (+gestures)
* USB Ports
* Ethernet
* Battery percentage
* Sleep & Wake (It takes me about 30 secs to completely sleep, slow but it did work)
* Microphone
* FN keys
* 3.5mm jack
* iCloud, iMessage, FaceTime
* Camera
* Airdrop, HandOff (Need to replace WLAN chip)

## Bugs/not working
* NVIDIA GPU
* Mic via combined jack (Haven't fix yet)


## References
* https://www.imacpc.net/archives/1617
* https://applelife.ru/threads/asus-x550vc-i-asus-x550cc.41752/
