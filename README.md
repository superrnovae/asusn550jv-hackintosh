**macOS version:** 10.8 - 11.2.3

**OpenCore version**: [0.6.8](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.6.8)

## Specifications
| **Component** | **Model** |
| ------------- | ------------- |
| CPU | i7  4700HQ  Processor |
| iGPU | HD 4600 |
| dGPU | NVIDIA GT 750M |
| RAM | 16 GB DDR3L 1600 MHz |
| STORAGE | SAMSUNG 840 EVO |
| WLAN CHIPSET | Broadcom BCM94352 |
| LAN CHIPSET | RTL8168 Gigabit-LAN |
| BLUETOOTH | BT 4.0 |
| AUDIO CHIPSET | Realtek ALC668 |

## What works

- Hardware Acceleration
- Audio          
- WiFi
- Ethernet
- Bluetooth
- USB ports
- Keyboard backlight (16 levels)
- Monitor brightness (smooth increase/decrease)
- Fn keys (except Fn + F9)
- Battery Readings
- Sleep
- Trackpad
- CPU Power Management
- CPU Temperature Readings
- Disabled dGPU
- iServices

## Issues
 - Fn + F9 doesn't work
 - Card Reader doesn't work
 - Cursor jumps to top corner on double touch

## How to use

This repository is meant to be used as a reference. I recommend you [**follow the official guide**](https://dortania.github.io/OpenCore-Install-Guide/), that in details explains the process of creating a bootable USB to installing macOS and finally fixing issues that have occurred during install or post-install phase.

In case you don't have enough time to read the docs, proceed as follows:

  1. [**Create bootable USB**](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/).  
  2. Clone this repository, copy and paste "EFI" directory onto your USB drive.
  3. [**Generate SMBIOS for MacBookPro11,2**](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#generate-a-new-serial) and [**fix ROM**](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#fixing-rom).  
  4. Set BIOS settings according to the [**guide**](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/haswell.html#intel-bios-settings).  
  5. [**Install macOS**](https://dortania.github.io/OpenCore-Install-Guide/installation/installation-process.html#booting-the-opencore-usb). 

## Other Guides

In case you are experiencing issues during installation or boot, kernel panics or other system related issues — check OC configuration guides:  

- [**OpenCore and Big Sur**](https://dortania.github.io/OpenCore-Install-Guide/extras/big-sur/#table-of-contents)
- [**Post-Install**](https://dortania.github.io/OpenCore-Post-Install/)
- [**Troubleshooting**](https://dortania.github.io/OpenCore-Install-Guide/troubleshooting/troubleshooting.html)
- [**Fixing iServices**](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html)
- [**ACPI Patching**](https://dortania.github.io/Getting-Started-With-ACPI/)

If you have any other questions or issues, feel free to ask on [**Hackintosh Discord**](https://discord.com/invite/Wxam8aH) or [**Forum**](https://www.insanelymac.com/forum/)  

## Credits

- [**acidanthera**](https://github.com/acidanthera) for [OpenCore](https://github.com/acidanthera/OpenCorePkg), [AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup), [AppleALC](https://github.com/acidanthera/AppleALC), [BrcmPatchRAM](https://github.com/acidanthera/BrcmPatchRAM), [CPUFriend](https://github.com/acidanthera/CPUFriend), [Lilu](https://github.com/acidanthera/Lilu), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [**hieplpvip**](https://github.com/hieplpvip) for [AsusSMC](https://github.com/hieplpvip/AsusSMC) and [AppleBacklightSmoother](https://github.com/hieplpvip/AppleBacklightSmoother)
- [**Mieze**](https://github.com/Mieze) for [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X)
- [**dortania**](https://github.com/dortania) for amazing [documentation](https://dortania.github.io/OpenCore-Install-Guide/)
