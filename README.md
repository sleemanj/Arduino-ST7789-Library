Arduino-ST7789-Library
======================

Extention of the Adafruit_GFX Library to interface with ST7789 IPS SPI 240x240 pixel displays.

Download, Install and Example
-----------------------------

You must install the Adafruit_GFX library first, in the Arduino IDE go to Sketch > Include Library > Manage Libraries and search for Adafruit GFX, install it.

Then 

* Download: http://sparks.gogo.co.nz/Arduino-ST7789-Library.zip
* Open the Arduino IDE
* Select the menu item Sketch > Import Library > Add Library
* Choose to install the Arduino-ST7789-Library.zip file you downloaded
* Now you can choose File > Examples > Arduino-ST7789-Library > helloworld

Connecting To Your Arduino
--------------------------

The ST7789 is a 3.3 Volt Module, both power and signalling is 3.3v, so you can not connect it directly to a 5v Arduino, you will need to level-shift.

:warning: **Remember do not connect to 5v Arduino directly, you must level shift or use a 3.3v Arduino**

### Uno/Nano Connections

| Display          |    Arduino | 
-------------------| ------------- |
| VCC              |    3.3v |
| GND              |    Gnd| 
| SCL              |    Pin 13 (SCK)| 
| SDA              |    Pin 11 (MOSI) | 
| RES              |    Pin 9 | 
| DC               |    Pin 8 | 
| BLK              |    Leave disconnected | 

### Mega Connections

| Display          |    Arduino | 
-------------------| -------------| 
| VCC              |    3.3v | 
| GND              |    Gnd| 
| SCL              |    Pin 52 (SCK)| 
| SDA              |    Pin 51 (MOSI) | 
| RES              |    Pin 9 | 
| DC               |    Pin 8 | 
| BLK              |    Leave disconnected | 


Usage
--------------------------

Open the HelloWorld example.  as this library uses the Adafruit_GFX library as it's foundation you should google for more information about using the Adafruit_GFX library.

Patches Welcome
--------------------------

By all means!


