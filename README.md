<h1>Laterna mini v1 </h1>

The Laterna series of boards are mainly intended to be used with [WLED software ](https://github.com/Aircoookie/WLED "WLED's Homepage"), but you can also program the board using your own code or other library via [Arduino](https://www.arduino.cc "Arduino Homepage"), [ESPHome](https://esphome.io "ESPHome Homepage"), [Tasmota](https://tasmota.github.io/docs "Tasmota Homepage") etc.


The controller can be ordered from [Aliexpress](https://www.aliexpress.com/item/1005003856791476.html?spm=5261.ProductManageOnline.0.0.69f24edfKVGmPr)<br>

<h3>Features</h3>
Chip:   ESP-01F 
<br>USB Type C connector for flashing and 5V power
<br>CP2102 USB to serial chip for easy flashing (https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers) 
<br>1 channels for adressable LED strip with 3 or 4 pins (e.g. WS281x, WS2801, SK6812 etc.)
<br>3A resettable Fuse (https://en.wikipedia.org/wiki/Resettable_fuse)

<img src="/Photos/mini-Front.png" width="50%"><img src="/Photos/mini_Back.png" width="50%">

<h3>Installation</h3>

All our boards are delivered with a up to date WLED version.You can use the board out of the box.

You can customize the software based on your needs and flash it by **USB** or the **programming connector**.
The board has an integrated CP2102 USB to UART bridge so you can flash it without using **any additional hardware**.

For Flashing a precompiled Firmware we recommend [ESPHome Flasher](https://github.com/esphome/esphome-flasher/releases "ESPHome Flasher Releases")

We also have a ESPHome template available which can be easily flashed via [this website](https://planet-laterna.github.io/Laterna-ESPHome-template)

<h5>Required steps for manual flashing</h5>

* First you need to put the Board in flash mode
* Press and hold the Flash button before connecting the board to USB or programmer connector. Release the flash button after you connect the board.


<h3>PINOUT Description</h3>

<img src="/Photos/Laterna_Pinout.png" width="50%">

<h3>Circuit protection</h3>

Our boards include a resetable fuses to limit current on the board.
<br>Powered by USB C port -> 3A

The wiring instructions you can find [here](https://github.com/Planet-Laterna/Laterna-mini/tree/main/Wiring)
<br>Depending on the number of LEDs you want to use you can power the LEDs directly via the controller, otherwidse you can connect the LEDs power input directly to the power supply.
<br>1. Power via USB C
<br><img src="/Wiring/Wiring_Laterna_Mini_Power_over_USB.jpg" width="50%">
<br>2. Power via external PSU 
<br><img src="/Wiring/Wiring_Laterna_Mini_Power_LED_with_PSU.jpg" width="50%">


<h3>Tested LED Strips:</h3>
WS281x
<br>WS2801
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
