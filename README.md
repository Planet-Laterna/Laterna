<h1>Laterna </h1>

The Laterna series of boards are mainly intended to be used with [WLED software ](https://github.com/Aircoookie/WLED "WLED's Homepage"), but you can also program the board using your own code or other library via Arduino, ESPHome, Tasmota etc.
<br>The board comes with or without soldered screw terminal and extra pins.

<h3>Features</h3>
Chip:   ESP32 WROOM 32E Wifi and Bluetooth
<br>USB Type C connector for flashing and 5V power
<br>2 channels for adressable LED strip with 3 or 4 pins (e.g. WS281x, WS2801, SK6812 etc.)
<br>1 channel for RGB/RGBW 5050 LED  Strips
<br>Works with 5V, 12V and 24V (Input = Output Voltage)
<br>Several GPIOs and 3V outputs for adding additional sensors, buttons, microphone etc.

![Laterna](https://github.com/monoapp3/Laterna/blob/main/Photos/Laterna.png?raw=true)
![Laterna](https://github.com/monoapp3/Laterna/blob/main/Photos/Laterna_blue_terminals_case.png?raw=true)

<h3>Installation</h3>

All our boards are delivered with a default WLED version **link to board version and software flashed**.You can use the board out of the box after you solder required connectors.

You can customize the software based on your needs and flash it by **USB** or the **programming connector**.
The board has an integrated CP2102 USB to UART bridge so you can flash it without using **any additional hardware**.

For Flashing a precompiled Firmware we recommend [ESPHome Flasher](https://github.com/esphome/esphome-flasher/releases "ESPHome Flasher Releases")

<h5>Required steps for manual flashing</h5>

* First you need to put the Board in flash mode
* Option 1: Press and hold the Flash button before connecting the board to USB or programmer connector. Release the flash button after you connect the board.
* Option 2: Press the Reset and Flash button while the board is connected. Then release the Reset button first and then the Flash button.


<h3>PINOUT Description</h3>

**to be updated**

<h3>Circuit protection</h3>

Our boards include 2 resetable fuses to limit current on the board.
<br>If powered by USB C port -> 3A
<br>If powered by external power supply -> 12A

<h3>Tested LED Strips:</h3>
WS281x
<br>WS2801
<br>SK6812
<br>RGB and RBGW 5050 Strips

<h3>Tested Sensors:</h3>
Analoge Microphone: MAXX4466      (Tested with WLED Sound Reactive https://github.com/atuline/WLED/wiki) 
<br>Digital Microphone: INMP441   (Tested with WLED Sound Reactive https://github.com/atuline/WLED/wiki)
<br>Wemos Button Shield

<br>Please take note that this Laterna Version can support 5V, 12V and 24V LED strip and Power Supplies => Input Voltage = Output Voltage</br>

<h3>Use Cases - Videos</h3> 

[![Alt text](https://img.youtube.com/vi/g_3g_RMFQ8w/0.jpg)](https://www.youtube.com/watch?v=g_3g_RMFQ8w)


* plug and play example - USB power
* plug and play example - External power supply
* Adding a button
* Adding a sound sensor
* Adding a distance sensor
* etc
(**Work in Progress**)

<h3>License</h3>

Software used in this guide is open source and licensed under the **MIT License**

<h3>FAQ</h3>

* Can I use this board with my own code?
  - yes, you can write your own code and programm this board. Refer to programming steps section
* How many LEDs can I control with this board?
  - we recomend to use xx LEDs if board powered by USB and yy LEDs if powered with external power supply (**Work in Progress**)

<h3>Acknowledgment</h3>

We would like to thank WLED Developers for their great job, our platform relies strongly on their work
[![Alt text](https://github.com/Aircoookie/WLED/blob/master/images/wled_logo_akemi.png)](https://github.com/Aircoookie/WLED)
