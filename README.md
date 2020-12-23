**macOS version:** 11.1

**OpenCore version**: [0.6.4](https://github.com/acidanthera/OpenCorePkg/releases)

## Specifications
| **Component** | **Model** |
| ------------- | ------------- |
| CPU | Intel Core™ i7  4700HQ  Processor |
| iGPU | Intel HD Graphics 4600 |
| dGPU | NVIDIA GeForce® GT 750M |
| RAM | 16 GB DDR3L 1600 MHz |
| STORAGE | SAMSUNG 840 EVO 250GB |
| WLAN CHIPSET | Broadcom BCM94352 |
| LAN CHIPSET | Realtek RTL8168/8111 Gigabit-LAN |
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
 - Cursor jumps to top corner when touched by 2 fingers

## How to use
  1. [**Create bootable USB**](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/).  
  2. Clone this repository, copy and paste "EFI" directory onto your USB drive.
  3. [**Set up SMBIOS and MAC address info**](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#platforminfo).  
  4. Set BIOS settings according to the [**guide**](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/haswell.html#intel-bios-settings).  
  5. [**Install macOS**](https://dortania.github.io/OpenCore-Install-Guide/installation/installation-process.html#booting-the-opencore-usb).

## Other Guides
**If you have any problems with installation or booting your macOS, kernel panics or another system related issues check OC configuration guide**  
**If something else isn't working properly (for example USB ports, iServices, DRM/Netflix) check Post-Install guide**
 - [Post-Install](https://dortania.github.io/OpenCore-Post-Install/)
 - [Multiboot](https://dortania.github.io/OpenCore-Post-Install/#multiboot)
 - [Troubleshooting](https://dortania.github.io/OpenCore-Post-Install/)
 - [ACPI Patching](https://dortania.github.io/Getting-Started-With-ACPI/)
 - [USB Mapping](https://dortania.github.io/OpenCore-Post-Install/usb/)

If you have any other questions or issues, feel free to ask on [**Hackintosh Discord**](https://discord.com/invite/Wxam8aH) or [**Forum**](https://www.insanelymac.com/forum/)  

## Credits

- [**acidanthera**](https://github.com/acidanthera) for [OpenCore](https://github.com/acidanthera/OpenCorePkg), [AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup), [AppleALC](https://github.com/acidanthera/AppleALC), [BrcmPatchRAM](https://github.com/acidanthera/BrcmPatchRAM), [CPUFriend](https://github.com/acidanthera/CPUFriend), [Lilu](https://github.com/acidanthera/Lilu), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [**hieplpvip**](https://github.com/hieplpvip) for [AsusSMC](https://github.com/hieplpvip/AsusSMC) and [AppleBacklightSmoother](https://github.com/hieplpvip/AppleBacklightSmoother)
- [**Mieze**](https://github.com/Mieze) for [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X)
- [**dortania**](https://github.com/dortania) for documentation
