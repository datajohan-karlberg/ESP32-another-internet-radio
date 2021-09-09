# ESP32 another internet radio
 A simple internetradio with stream buffer.

# esp32
I use ADAFRUIT Music Maker as soundcard. It have the VS1053 chip.
The special with this code is it use a ringbuffer for the stream.
#include <RingBuf.h>
and that make the stream more stable.
To change channel, push the Flash button on the ESP32. That button is IO-0 on this ESP32 board.  

 
![GitHub Logo](/Drawing.png)



![GitHub Logo](/Picture1.jpg)
