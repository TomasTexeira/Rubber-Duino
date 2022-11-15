# Rubber-Duino #
- Rubber-Ducky made with Arduino.
# Glossary: 
- **Rubber-Ducky**: https://www.geeksforgeeks.org/usb-rubber-ducky-penetrationtesting/
- **HID Device**: HID stands for Human Interface Devices, it includes devices like keyboard, mouse, joystick.
# But...Wath The F#ck is this?:
We use the dfu-programmer tool to configure the microcontroller that will turn the arduino into a HID device.
Then, the only thing left would be to upload the program with the instructions to be executed on the victim machine.
And... Voila, you have a Rubber-Ducky made with Arduino.
# List
- Arduino x1
- USB cable x1
- DuPont wire x1

# Dfu-Programmer Supported Chips:
### **8051 based controllers**:
at89c51snd1c, at89c51snd2c, at89c5130, at89c5131, at89c5132

### **AVR based controllers**:
at90usb1287, at90usb1286, at90usb1287-4k, at90usb1286-4k, at90usb647, at90usb646, at90usb162, at90usb82, atmega32u6, atmega32u4, atmega32u2, atmega16u4, atmega16u2, atmega8u2

### **AVR32 based controllers**:
at32uc3a0128, at32uc3a1128, at32uc3a0256, at32uc3a1256, at32uc3a0512, at32uc3a1512, at32uc3a0512es, at32uc3a1512es, at32uc3a364, at32uc3a364s, at32uc3a3128, at32uc3a3128s, at32uc3a3256, at32uc3a3256s, at32uc3a4256s, at32uc3b064, at32uc3b164, at32uc3b0128, at32uc3b1128, at32uc3b0256, at32uc3b1256, at32uc3b0256es, at32uc3b1256es, at32uc3b0512, at32uc3b1512, at32uc3c064, at32uc3c0128, at32uc3c0256, at32uc3c0512, at32uc3c164, at32uc3c1128, at32uc3c1256, at32uc3c1512, at32uc3c264, at32uc3c2128, at32uc3c2256, at32uc3c2512

### **XMEGA based controllers**:
atxmega64a1u, atxmega128a1u, atxmega64a3u, atxmega128a3u, atxmega192a3u, atxmega256a3u, atxmega16a4u, atxmega32a4u, atxmega64a4u, atxmega128a4u, atxmega256a3bu, atxmega64b1, atxmega128b1, atxmega64b3, atxmega128b3, atxmega64c3, atxmega128c3, atxmega256c3, atxmega384c3, atxmega16c4, atxmega32c4

# Boot:
## **Arduino-COMBINED-dfu-usbserial-atmega16u2-Uno-Rev3.hex**:
### **DOC**:


- https://arduino.stackexchange.com/questions/1048/whats-the-difference-relationship-between-arduino-and-avr
## **Arduino-keyboard-0.3.hex**:
- https://github.com/coopermaa/USBKeyboard

# Installation:
- First we will have to install the dfu-programmer tool.\
`sudo apt install dfu-programmer`
- Install Arduino IDE.
- Clone the project:\
`git clone https://github.com/TomasTexeira/Rubber-Duino.git`
- Execute permissions:\
`cd Rubber-Duino`\
`chmod +x script.sh`
- Important! run the script with `sudo`\
`sudo ./script.sh`
- Follow the instructions.
![arduino_r3_image](https://user-images.githubusercontent.com/66860132/202038810-77c6b9db-0bdc-41b4-8d67-0ea0bbfb1aa7.png)
