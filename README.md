| Supported Targets | ESP32-S2 | ESP32-S3 |
| ----------------- | -------- | -------- |

### Based on TinyUSB Human Interface Device Example From Espressif
(See the README.md file in the upper level 'examples' directory of the espressif IDF for more information about examples.)



# Mylaps Orbits Control Keypad
Tested on Mylaps v5.10.13  
No known bugs

![Complete](/images/Complete.png)

Pin 1 = F5      (Green)  
Pin 2 = F9      (Yellow - NC)  
Pin 3 = F8      (Checker)  
Pin 4 = F10     (Manual Passing)

Connect one side of switch to ESP pin and the other to GND. ESP has built-in pullup resistors.

![Wiring](/images/Wiring.png)

![Internal](/images/Internal.png)

CAD models are included in this repo in STEP format so that you can edit to suit your needs.

My chosen components:  
uC: Seeed Xiao ESP32-S3   
Switches: Cherry MX Blue Keyboard Switches

