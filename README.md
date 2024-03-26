# Hackintosh Project for Asus Tuf Gaming FX705GD

**Disclaimer:**
Applying Hackintosh on your Asus Tuf Gaming FX705GD (or any laptop for that matter) can lead to an unstable system, and unexpected issues may occur. I take no responsibility for any damage, data loss, or malfunction caused by the use of this project. Proceed at your own risk.

# Showcase
![Image](https://media.discordapp.net/attachments/652541086870274058/1221572382565597295/Capture_decran_2024-03-24_a_22.32.25.png?ex=661310ef&is=66009bef&hm=92eef4d4e6e57fcc4f4d8db4404e6735fb57eb2a7988ab8655c635ba5a62ac96&=&format=webp&quality=lossless&width=1609&height=905)

## Version Info
| V.I.       | Type                                           |
| --------------- | ------------------------------------------------ |
| OC Version             | OC 0.9.8             |
| MacOS supported            | Tested with Monterey           |
| Status           | some broken stuff lol                           |


## Components and Compatibility

- ✅ - Works
- ⚠️ - In development, or fix in progress
- ❌ - Broken
- ⛔ - Incompatible, won't be fixed

| Component       | Model                                           | Status             |
| --------------- | ------------------------------------------------ | --------------- |
| `CPU`             | Intel Core i5-8300H (Coffee Lake)             | ✅             |
| `GPU`             | NVIDIA Mobile 1050Ti                        | ⛔             |
| `eGPU`            | Intel Graphics UHD 630                       | ✅             |
| `Audio`           | Realtek ALC233                                | ⚠️             |
| `Ethernet`        | Realtek RTL8168/8111                         | ✅             |
| `Wi-Fi`          | Intel Wireless-AC 9560                  | ⚠️ Works, but quirks may occur |
| `Bluetooth`      | Intel Bluetooth                              | ⚠️ Works, but quirks may occur |
| `Touchpad`       | Trackpad ELAN1200 I2C-HID                    | ✅             |
| `Keyboard`       | Keyboard PS2                                 | ✅             |
| `Battery`        | Asus Default Battery                         | ✅             |
| `Webcam`         | USB2.0 HD UVC WebCam Internal                                              | ✅             |
| `Microphone`     | Realtek micwopon                                            | ⚠️             |
| `USB Ports`     | 3 USB 2.0, 2 USB 3.1                                         | ✅             |
| `Fans`           | 2 Fans                                              | ⚠️             |


| Function       | Status             |
| --------------- | --------------- |
| `Sleep/Wake/Shutdown`  | ✅             |
| `AirDrop`  | ✅             |
| `FaceTime/IMessage`  | ✅             |
| `AirPlay`  | ✅             |

| Installation Drive       | Status             |
| --------------- | --------------- |
| `M.2 SSD`  | ✅           |
| `Any type of HDD`  | ✅             |


## Info about components with compatibility issues

### GPU
#### It is important to note that Apple hasn't released support for NVidia graphics and later for Higher macOS versions.

### Wi-Fi/BT
#### The Wi-Fi functionality remains partially unresolved due to the following reasons:
- Instability: macOS versions like Monterey, Ventura, and Sonoma have experienced crashes when attempting to connect to Wi-Fi, even after starting from scratch.
- Lack of Fixes: Despite attempts, there is no reliable solution to fully support the Wi-Fi card, making it unfeasible to continue debugging the issue.
- Bluetooth: The same goes to Bluetooth as it is using an Intel chip for both the WiFi and Bluetooth modules.

### Keyboard
#### Although the keyboard itself works, the main issues are with FN keys mapping and Keyboard Backlight. Efforts are ongoing to address these issues, but progress may be limited due to other commitments.

### Fans
#### While fan control and readings have not been implemented yet, efforts are underway to develop a possible solution for this functionality.

## Todo
- [ ] Disable verbose mode for a better looking boot screen
- [ ] Custom boot loader theme with OC
- [ ] Make sure everything works and release to public GitHub

## Sources/Credits

- [Dortania](https://dortania.github.io/) - For guides
- [Acidathera](https://github.com/acidanthera) - For OC and Kexts
- [RehabMan](https://github.com/RehabMan) - for ACPI Patching
- The Hackintosh community - for helping me with debugging the hackintosh.


Please note that I'm just sharing this EFI because it works successfully for me. Compatibility issues may occur, and I invite you to do more research if you have issues! :D
