
## Required libraries

Unzip or git clone the libraries into ‘~/Arduino/libraries/’ directory and restart Arduino IDE

- XPT2046: https://github.com/spapadim/XPT2046
- UTFT-ESP8266: https://github.com/gnulabis/UTFT-ESP8266


Modify: XPT2046.cpp
```
 void XPT2046::begin(uint16_t width, uint16_t height) {  
    ... 
    //SPI.begin(); //comment out 
    ... 
 }  
 ```

See the connection between ESP8266 board and 2.8 inch 240x320 Touch TFT LCD pins
and more at www.usemodj.com 
[Display 2.8 inch Touch LCD with WeMos D1 mini board](http://usemodj.com/2016/03/21/esp8266-display-2-8-inch-touch-lcd-with-wemos-d1-mini-board/)


