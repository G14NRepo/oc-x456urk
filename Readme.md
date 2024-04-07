💻 Spesifikasi Laptop Asus X456URK
- Processor: Prosesor Intel Core i5-7200U, KabyLake-U
- iGPU: Intel UHD Graphics 620
- dGPU: NVIDIA 930MX 2GB (Will disable)
- Min RAM: 4Gb
- Audio: Intel HD Audio Sunrise
- Trackpad: ELAN
- Storage: SSD MIDAS 512 GB
- Usb: 2 Port
- Type C: 1 Port
- Wireless: Intel AX210
- Bluetooth: Intel AX210
- Bootloader: Opencore 0.9.9
- OS: Ventura 13.6.4
- Installer: Dortania

Requirement :
1. Machintos Ventura [Link Here](https://www.olarila.com/topic/6278-olarila-vanilla-images-macos-installer/)
2. Balena Etcher [Link Here](https://etcher.balena.io/#download-etcher)
3. Opencore Configurator [Link Here](https://mackie100projects.altervista.org/download/occ/)
4. Hackintool [Link Here](https://github.com/benbaker76/Hackintool/releases)
5. Flash Drive Min 16Gb

Step :
1. Download raw file of Machintosh Ventura
2. Download "balena etcher"
    - Linux : etcher-bin / etcher / balena-etcher
    - Windows : Balena Etcher 
    - MacOS : Balena Etcher
3. Git clone this repo
4. Put flash drive and running "balena etcher"
5. Select flash drive wanna format it, then choose where file Machintos Ventura was download it, Flash it
6. After Flash, mount EFI folder in flash drive
    - Linux : sudo mkdir /mnt/efi && sudo mount /dev/[sd??] /mnt/efi
    - MacOS : Use EFI Mounter / Opencore Configurator
    - Windows : ???
7. Remove "EFI" folder in mounted EFI
8. Copy "EFI" Folder in cloned Folder to mounted EFI Folder
9. Eject Mounted "EFI" Folder
    - Linux : cd / && sudo umount /dev/[sd??]
    - MacOS : Use EFI Mounter / Opencore Configurator
    - Windows : ???
10. Eject Flash Drive and Use it...
11. Happy Flash 😘

Thanks To :
- Dortania [Link Here](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html)
- Indonesian Telegram Group [Link Here](https://t.me/HackintoshLover)
