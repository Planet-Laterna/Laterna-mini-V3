<h1>Laterna mini V3</h1>

The Laterna series of boards are mainly intended to be used with [WLED software ](https://github.com/Aircoookie/WLED "WLED's Homepage"), but you can also program the board using your own code or other library via [Arduino](https://www.arduino.cc "Arduino Homepage"), [ESPHome](https://esphome.io "ESPHome Homepage"), [Tasmota](https://tasmota.github.io/docs "Tasmota Homepage") etc.


The controller can be ordered from [Aliexpress](https://www.aliexpress.us/item/3256804573459837.html?spm=5261.ProductManageOnline.0.0.6b454edf0eqcsJ&gatewayAdapt=glo2usa4itemAdapt&_randl_shipto=US)<br>

<h3>Features</h3>
Chip:   ESP32-Pico-mini
<br>USB Type C connector for flashing and 5V power
<br>CP2102 USB to serial chip for easy flashing (https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers) 
<br>1 channels for adressable LED strip with 3 (e.g. WS281x, SK6812 etc.)
<br>3A resettable Fuse (https://en.wikipedia.org/wiki/Resettable_fuse)
<br>Version with and without integrated digital Microphone available (INMP441)

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

<h3>License</h3>

Software used in this guide is open source and licensed under the **MIT License**

<h3>FAQ</h3>

* Can I use this board with my own code?
  - yes, you can write your own code and programm this board. Refer to programming steps section

<h3>Acknowledgment</h3>

We would like to thank WLED Developers for their great job, our platform relies strongly on their work
[![Alt text](https://github.com/Aircoookie/WLED/blob/master/images/wled_logo_akemi.png)](https://github.com/Aircoookie/WLED)
