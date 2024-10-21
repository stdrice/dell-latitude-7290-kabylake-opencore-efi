# OpenCore EFI for Dell Latitude 7290 (7th)
![img](https://i.imgur.com/wiWFtLQ.png)

# Specs
| Component          | Specs                                    |
| ------------------ | ---------------------------------------- |
| **Model**          | Dell Latitude 7290                       |
| **SMBIOS**         | MacBookPro 15,2                          |
| **macOS**          | Sonoma (14) or higher                    |
| **CPU**            | Intel Core i5-7300U                      |
| **GPU**            | Intel HD Graphics 620                    |
| **Display**        | 1366x768                                 |
| **Wi-Fi**          | Intel Dual Band Wireless-AC 8265         |
| **Ethernet**       | Intel Ethernet I219                      |
| **Touchpad**       | Alps Touchpad                            |
| **Soundcard**      | Realtek ALC3246/ALC256 (layout-id: `17`) |
| **SD Card Reader** | Realtek RTS525A                          |

# Working
- Graphics acceleration
- Wi-Fi, Bluetooth, Ethernet
- Audio (speakers, headphone jack)
- Keyboard, Touchpad
- Brightness keys (FN + S and FN + B, not arrow keys)
- USB (Type-C and Type-A)
- Camera, Microphone
- SD Card

# Not tested
- Multi display with HDMI/VGA/DisplayPort
- iServices (i don't have an iphone)

# Not working
- AirDrop (Intel wifi)
- You tell me

# How to use?
- Clone this repo
- Copy EFI folder to your USB/EFI partition
- [Follow this guide](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html) to generate SMBIOS and fix iServices
