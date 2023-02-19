## Specification
Specification | Configuration
----------- | -----------
Processor | Intel Core i7-6500U
Integrated Graphics | Intel HD Graphics 520
Integrated Display | 1920x1080 FHD Display
Memory | SK-Hynix 8GB DDR4
Storage | 512GB Samsung SATA SSD
Wireless Card | Dell DW1560 (BCM94352Z) 802.11ac WiFi + BT Card
Bootloader | OpenCore
Bootloader Ver. | v0.9.0
System Ver. | 13.2.1 Ventura
SMBIOS | MacBookPro14,1

There a planed upgrades like 16 GB RAM, Fenvi Broadcom WiFi Card for nativ Wifi and BT (and a NVME SSD if its possible to put it in the WWAN m.2 Slot?)

### Before you start
Follow dortania guide on how to create a recovery usb for MacOS installation.
You can find the MacOS installation guide at the following link, [`click here`](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html#downloading-macos)

!!!Also Please change the Serial numbers etc. in the Property Informations i uploaded Random ones!!!

## MacOS
- Ventura (Tested, OpenCore)
- Monterey (Tested, OpenCore)
- Bigsur (Tested, OpenCore)

> The current EFI supports Ventura out of box but, for older Ones use Monterey or Older Folder.
> The Monterey or Older Folder is on OpenCore 0.8.9 and will no longer recive updates from me

## What's Working?
- QE/CI Intel HD Graphics 520 `BigSur` `Monterey` `Ventura with Spoof to 630`
- OnBord HDMI `BigSur` `Monterey` `Ventura`
- Power Management `BigSur` `Monterey` `Ventura`
- Sleep, Shutdown, Restart `BigSur` `Monterey` `Ventura`
- Audio Speaker & Earphone & Mic `BigSur` `Monterey` `Ventura`
- WiFi `BigSur`  `Monterey` `Ventura`
- Bluetooth `BigSur`  `Monterey` `Ventura`
- OnBord LAN `BigSur`  `Monterey` `Ventura`
- USB Map (inc. Dock) `BigSur`  `Monterey` `Ventura`
- Trackpad, Trackpoint, Gestures `BigSur` `Monterey` `Ventura`
- Battery Indicator (Single and Dual Battery) `BigSur` `Monterey` `Ventura`
- Camera `BigSur` `Monterey` `Ventura`
- Docking station `BigSur` `Monterey` `Ventura`
- CardReader `BigSur` `Monterey` `Ventura`
- YogaSMC (With the Helper App) `BigSur` `Monterey` `Ventura`
- Keyboard Mapp for Volume, Brightness and Mute Controll `BigSur` `Monterey` `Ventura`


## Some little Problems!!!
- Since Ventura there are sometimes graphics glitches and the brightness control is only available after a sleep cycle!
- Video Out via Docking Staion is also only available after Sleep
- Video Out via OnBoard MiniDisplayPort is also only available after Sleep
- Sometimes Laptop Wakes up from sleep and Bios is Resettet

## If you want to Help me to get to a 100% Perfect EFI i have added all my BIOS Settings in the PDF file and also a Clean ACPI and Vidio BIOS Dump
- You want to Help me and others you can do this in my Forums Thred on Hackintosh-Forum.de (Warning this is in German)
- https://www.hackintosh-forum.de/forum/thread/57946-lenovo-x260-ben%C3%B6tigt-hilfe-im-feinschliff

## Credits:
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/)
- [hackintosh-forum.de](https://hackintosh-forum.de/)
- [SuhailSherief](https://github.com/SuhailSherief/ThinkPad-x260-macOS-OpenCore/)
- [x90skysn3k](https://github.com/x90skysn3k/x260-lenovo-opencore/)
