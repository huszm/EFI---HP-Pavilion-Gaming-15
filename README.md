# Opencore-HP-Pavilion-Gaming-15-dk0010nr

<B>OpenCore Hackintosh - HP Pavilion Gaming 15-dk0010nr</B>

## Specifications

| Specifications      | Detail                                      |
| ------------------- | ------------------------------------------- |
| Computer model      | HP Pavilion Gaming 15-dk0010nr              |
| CPU                 | Intel Core i5-9300H                         |
| Memory              | 8GB/8GB Crucial / SK Hynix                  |
| SSD		              | Samsung SSD 970 EVO 500GB (PM981)		        |
| HDD		              | Seagate ST2000LM007-1R817 2TB			 	        |
| Integrated Graphics | Intel® UHD Graphics 630                     |
| Dedicated Graphics  | NVIDIA GeForce GTX 1050 Ti                  |
| Monitor             | FHD 1920x1080 (15.6 inch)                   |
| Sound Card          | Realtek ALC285 (0x285		                    |
| Wireless Card       | Realtek 802.11b/g/n/a/ac (2x2).             |
| Ethernet/LAN        | Realtek RTL8168/8111 PCI-E Gigabit Ethernet |


## Working
- Intel UHD 630 Acceleration
- CPU Power Management
- IGPU Power Management
- Battery Status / Time
- Ethernet LAN
- NVMe Storage
- Realtek Audio & F7/F8 keys
- Audio Combo Jack
- Keyboard & Media/Function Keys
- Trackpad & Gestures support
- USB Type-A & Type-C ports
- HP Webcam
- Screen Brightness & F2/F3 Keys
- And pretty much everything not listed below

## Not Working
- Intel Wireless & Bluetooth
- - DRM (No HD playback on Netflix etc.)
- SDXC Card Reader (Not supported in MacOS)
- Dedicated GPU (Disabled in SSDT)
- HDMI Port output (Seems to be hooked to the dedicated GPU)

## Not Tested
- Type-C HDMI does not have Audio


## Credits
- @1Revenger1 for ECEnabler
- @acidanthera for bootloader, VirtualSMC, NVMeFix, Lilu and other kexts
- @Apple for macOS
- @dortania for guides
- @OpenIntelWireless for WiFi & Bluetooth
- @SkyrilHD for massive help and tips / fixes
- @TECHNIKVERBOT for Monterey patches
- @USBToolBox Team for USB mapping
- @Voodoo Team for TrackPad
