**Disclaimer:**  
This is code for a personal project and will **not** be **maintained**. I'm just making the source available as-is in case it is helpful for your project.
If you would like to build upon it, feel free to create a fork!

## Arduino code for drawing BMP images from LittleFS to Waveshare 7.3 inch 7 color epaper (F) display using an ESP32

It is highly recommended to use 4-bit BMP as these already have a large file size (190 kB for 800x480).  
Lower size images are supported, make sure height and width are both an even pixel count.

Set pins in `epdif.h`. Use another program, e.g. [WLED](https://github.com/Aircoookie/WLED), to upload BMP images to LittleFS filesystem.  
Early demo stage, I am not fully satisfied with the performance of this display as of now as there is a loss of contrast and striping when drawing dithered photos.

Code is based on the [official demo by Waveshare](https://www.waveshare.com/wiki/7.3inch_e-Paper_HAT_(F)_Manual#Run_The_Demo)

If this code is useful to you, you may consider to [![](https://img.shields.io/badge/send%20me%20a%20small%20gift-paypal-blue.svg?style=flat-square)](https://paypal.me/aircoookie)