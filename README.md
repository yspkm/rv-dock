# lichee-rv-dock
Stuff to utilize Lichee RV 7001, the RISC-V-based Linux computer recently announced by Sipeed. 

Project 0: PWM Servo Control: Through the pwm0-7 generators of Allwinner D1 RISC-V CPU, I'd like to glance at the possibility of direct control of the servo motors with the RISC-V Linux kernel.


![lichee-rv-dock-gpio](https://user-images.githubusercontent.com/71680670/169593529-47a8b321-f7a3-4be1-bac0-23b9885f95bb.png)


The figure above is the GPIOs of a lichee-RV dock. Because the USB-C and USB-A ports do not automatically convert to USB protocol, We must connect them via debugger or ttl2usb converter.


| Debugger | Lichee RV Dock |
|---|---|
| TX | RX |
| RX | TX |
