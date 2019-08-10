# chinese-1.8-128x160-RGB-TFT-ST7735S-on-D1-R32 
chinese 1.8" 128x160 RGB TFT ST7735S example on D1 R32  
Since I was not able to find a decent pinout for the fake wemos D1 R32  
I had problems configuring the GPIO pin numbers to get the undocumented 
chinese TFT diplay working. 
  
The example code is based on: The adafruit ST7735 library 

/**************************************************************************

  This is a library for several Adafruit displays based on ST77* drivers. 
  

  Works with the Adafruit 1.8" TFT Breakout w/SD card 
    ----> http://www.adafruit.com/products/358
    
  The 1.8" TFT shield 
    ----> https://www.adafruit.com/product/802
    
  The 1.44" TFT breakout  
    ----> https://www.adafruit.com/product/2088
    
  The 1.3" TFT breakout 
  ----> https://www.adafruit.com/product/4313
  
  The 1.54" TFT breakout  
    ----> https://www.adafruit.com/product/3787
    
  The 2.0" TFT breakout 
    ----> https://www.adafruit.com/product/4311
    
  as well as Adafruit raw 1.8" TFT display  
    ----> http://www.adafruit.com/products/618
    

  Check out the links above for our tutorials and wiring diagrams.
  
  These displays use SPI to communicate, 4 or 5 pins are required to
  
  interface (RST is optional).
  

  Adafruit invests time and resources providing this open source code,
  
  please support Adafruit and open-source hardware by purchasing
  
  products from Adafruit!
  

  Written by Limor Fried/Ladyada for Adafruit Industries.
  
  MIT license, all text above must be included in any redistribution
  
 **************************************************************************/
 
 
 Below is the only pinout refference I could find for the fake WEMOS D1 R32 
 
 SCL is GPIO 22 & SDA is GPIO 21
 ![D1 R32 pinout](https://raw.githubusercontent.com/JanBosNL/chinese-1.8-128x160-RGB-TFT-ST7735S-on-D1-R32/master/8.png)
 
