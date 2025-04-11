# nRF52840
Supermini Pro Micro nRF52840 Arduino Board Variant and information for compiler
Tested and functioning only with digital pins, not with analogue yet. 

Boards.txt - Remember to change supermini_nrf52840.build.usb_product="USBandBTNAME" to suit your designed name for bluetooth and USB connectivity
Variants files - You will want to confirm pins. 


1. First install BSP for adafruit equivalent boards using the following instructions:
https://learn.adafruit.com/introducing-the-adafruit-nrf52840-feather/arduino-bsp-setup

2. Add board folder to:
(MacOS)
~/Users/<username>/Library/Arduino15/packages/adafruit/hardware/nrf52/1.6.1/variants

3. Update your /Users/<username>/Library/Arduino15/packages/adafruit/hardware/nrf52/1.6.1/boards.txt
to include the boards.txt content from this repo, postpending it to the end of the file.

