# OpenCore EFI for Dell Latitude 7290/7390 (KabyLake)
![img](https://i.imgur.com/wiWFtLQ.png)

# Specs
| Component          | Specs                                    |
| ------------------ | ---------------------------------------- |
| **Model**          | Dell Latitude 7290/7390                  |
| **SMBIOS**         | MacBookPro15,2                           |
| **macOS**          | Sonoma (14)      	                    	|
| **CPU**            | Intel Core i5-7300U                      |
| **GPU**            | Intel HD Graphics 620                    |
| **Display**        | 1366x768                                 |
| **Wi-Fi**          | Intel Dual Band Wireless-AC 8265         |
| **Ethernet**       | Intel Ethernet I219                      |
| **Touchpad**       | ELAN Touchpad                            |
| **Soundcard**      | Realtek ALC3246/ALC256 (layout-id: `17`) |
| **SD Card Reader** | Realtek RTS525A                          |

# Working
- Graphics acceleration
- Wi-Fi, Bluetooth, Ethernet
- Audio (speakers, headphone jack)
- Multi display with HDMI/VGA/DisplayPort
- Keyboard, Touchpad
- Brightness keys (FN + S and FN + B, not arrow keys)
- USB (Type-C and Type-A)
- Camera, Microphone
- SD Card
- Sleep (S3 Sleep)
- iServices
- DRM (Apple Music, ...)
- OpenCore GUI
- Boot Chime
- You tell me

# Not working
- AirDrop (Intel wifi)
- Fingerprint (No Apple T2 chip)
- You tell me

# How to use?
- Clone this repo
- Copy EFI folder to your USB/EFI partition
- [Follow this guide](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html) to generate SMBIOS and fix iServices
- Install [BlueSnooze](https://github.com/odlp/bluesnooze) to fix Bluetooth not working after sleep
- Install []() to fix headphone jack cracking after sleep
```
git clone https://github.com/hackintosh-stuff/ComboJack
cd ComboJack/ComboJack_Installer
./install.sh
