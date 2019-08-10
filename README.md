# chinese-1.8-128x160-RGB-TFT-ST7735S-on-D1-R32 
chinese 1.8" 128x160 RGB TFT ST7735S example on D1 R32  
Since I was not able to find a decent pinout for the fake wemos D1 R32  
I had problems configuring the GPIO pin numbers to get the undocumented 
chinese TFT diplay working.
  
The example code is based on: The adafruit ST7735 library 

The examples suplied within the library only worked with branded hardware, 

All I did was figure out the GPIO commands and connect everything to my defined pin numbers.
In the code you will find this below. Adjust for your brand and type of board and GPIO numbers.

#define TFT_DC 18

#define TFT_CS 19

#define TFT_RST 13

#define TFT_SCLK 22 //SCL

#define TFT_MOSI 21 //SDA


/**************************************************************************

  This is a library for several Adafruit displays based on ST77* drivers. 
  
  Written by Limor Fried/Ladyada for Adafruit Industries.
  
  MIT license, all text above must be included in any redistribution
  
 **************************************************************************/
 
 
 Below is the only pinout refference I could find for the fake WEMOS D1 R32 
 
 SCL is GPIO 22 & SDA is GPIO 21
 
 ![D1 R32 pinout](https://raw.githubusercontent.com/JanBosNL/chinese-1.8-128x160-RGB-TFT-ST7735S-on-D1-R32/master/8.png)
 
