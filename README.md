# macOS BigSur 11.7.10 on Lenovo ThinkPad X230
  with OpenCore 0.9.5
  ![picture](https://github.com/agensosis/thinkpad-x230-macOS/blob/main/capture.png)
##  Whats working
 - Intel HD4000
 - Audio + Mircophone with Apple ALC
 - Brightness including fn key
 - Sleep, Shutdown/Restart
 - Battery status
 - Wlan + Bluetooth (Intel Centrino Advance-N 6205 + BCM20702)
 - Intel Gigabit LAN 82579LM
 - Stock Touchpad with gesture
 - USB 2.0 + USB 3.0
 - iMessage
 - Facetime
## Known issues
 - SD Card reader (Too lazy to fix. Didn't use it)
 - DRM (Use Chrome instead)

## UEFI Configuration
 - Config > Network > Wake on LAN : Disabled
 - Config > USB > USB 3.0 Mode : Automatic
 - Config > Serial ATA > Mode : AHCI
 - Config > Intel (R) Smart Connect Technology : Disable
 - Security - Security Chip : Disabled
 - Security - Virtualization : Enabled
 - Intel VT-d : Disabled
 - Security - IO Port Access > Fingerprint : dDisabled
 - Security - Internal Device Access : Disabled
 - Security - Anti theft : Disable all including Computrace
 - Security - Secure Boot : Disabled
 - Startup > UEFI/Legacy Boot : UEFI Only

## To Do List
 - Monterey update

Note : You should generate your own SMBIOS. Use MacBookPro 11,1 (instruction: https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/ivy-bridge.html#platforminfo)

## How To Install:
 - Copy EFI folder into your bootable
