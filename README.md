<h1>Laterna mini V3</h1>

The Laterna series of boards are mainly intended to be used with [WLED software ](https://github.com/Aircoookie/WLED "WLED's Homepage"), but you can also program the board using your own code or other library via [Arduino](https://www.arduino.cc "Arduino Homepage"), [ESPHome](https://esphome.io "ESPHome Homepage"), [Tasmota](https://tasmota.github.io/docs "Tasmota Homepage") etc.


The controller can be ordered from [Aliexpress](https://www.aliexpress.us/item/3256804573459837.html?spm=a2g0o.store_pc_allProduct.8148356.7.357860603lHAKu&pdp_npi=2%40dis%21USD%21US%20%2416.75%21US%20%2416.75%21%21%21%21%21%402146a03716660030378366121e8ed3%2112000030370281507%21sh&gatewayAdapt=glo2usa&_randl_shipto=US)<br>

<h3>Features</h3>
Chip:   ESP32-Pico-mini
<br>USB Type C connector for flashing and 5V power
<br>CP2102 USB to serial chip for easy flashing (https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers) 
<br>1 channels for adressable LED strip with 3 (e.g. WS281x, SK6812 etc.)
<br>3A resettable Fuse (https://en.wikipedia.org/wiki/Resettable_fuse)
<br>Version with and without integrated digital Microphone available (INMP441)

<h3>Wiring instructions will be updated soon</h3>

<h3>Installation</h3>

All our boards are delivered with a up to date WLED version.You can use the board out of the box.

You can customize the software based on your needs and flash it by **USB** or the **programming connector**.
The board has an integrated CP2102 USB to UART bridge so you can flash it without using **any additional hardware**.

For Flashing a precompiled Firmware we recommend [ESPHome Flasher](https://github.com/esphome/esphome-flasher/releases "ESPHome Flasher Releases")

We also have a ESPHome template available which can be easily flashed via [this website](https://planet-laterna.github.io/Laterna-ESPHome-template)

<h5>Required steps for manual flashing</h5>

* First you need to put the Board in flash mode
* Press and hold the Flash button before connecting the board to USB or programmer connector. Release the flash button after you connect the board.


<h3>Circuit protection</h3>

Our boards include a resetable fuses to limit current on the board.
<br>Powered by USB C port -> 3A

<h3>Tested LED Strips:</h3>
WS281x
<br>SK6812


<h3>Use Cases - Videos</h3> 

[![Laterna Mini Ambilight](http://i3.ytimg.com/vi/7gAAEo-JBUc/hqdefault.jpg)](https://www.youtube.com/watch?v=7gAAEo-JBUc)

Iron Man Suit by Nate from the Internet

[![Iron Man](https://img.youtube.com/vi/u2959fVrq-s/hqdefault.jpg)](https://youtu.be/u2959fVrq-s?si=skSPCmUmJoFIo4mM&t=94)

<h3>License</h3>

Software used in this guide is open source and licensed under the **MIT License**

<h3>FAQ</h3>

* Can I use this board with my own code?
  - yes, you can write your own code and programm this board. Refer to programming steps section

<h3>Acknowledgment</h3>

We would like to thank WLED Developers for their great job, our platform relies strongly on their work

[![Alt text](https://github.com/Aircoookie/WLED/blob/main/images/wled_logo_akemi.png?raw=true)](https://github.com/Aircoookie/WLED)
