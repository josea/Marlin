## To compile in Arduino. 

#### Procedure tested in a Windows 10 Enterprise x64 computer. 

1. Install Arduino 1.6.5rev5
2. Install Teensyduino 1.45 (https://www.pjrc.com/teensy/td_download.html) 
3. Install this (copy files to Arduino folder) https://github.com/scwimbush/Printrboard-HID-Arduino-IDE-Support.
4. Select Teensy 2.0++ in the Arduino IDE as the board. 
5. Verify/Compile. *Might need to modify the preferences.txt file into the Arduino folders to find the avr-g++ compiler.*
6. Use FLIP 3.4.7 to upload the .HEX file.
   1. Printrbot Rev. D motherboard -> jumper in the BOOT pins, power on, reboot and connect. Chip = AT90USB1286.

**After it is up, revert settings to factory default: M502.**