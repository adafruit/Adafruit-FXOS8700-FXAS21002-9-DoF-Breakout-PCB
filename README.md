## Adafruit FXOS8700 FXAS21002 9-DoF Breakout PCB

<a href="http://www.adafruit.com/products/3463"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit FXOS8700 + FXAS21002 9 DoF Breakout. Format is EagleCAD schematic and board layout

For more details, check out the product page at
* https://www.adafruit.com/products/3463

### Description

The NXP Precision 9DoF breakout combines two of the best motion sensors we've tested here at Adafruit: The FXOS8700 3-Axis accelerometer and magnetometer, and the FXAS21002 3-axis gyroscope.

These two sensors combine to make a nice 9-DoF kit, that can be used for motion and orientation sensing. In particular, we think this sensor set is ideal for AHRS-based orientation calculations: the gyro stability performance is superior to the LSM9DS0, LSM9DS1, L3GD20H + LSM303, MPU-9250, and even the BNO-055 (see our Gyro comparison tutorial for more details).

Compared to the BNO055, this sensor will get you similar orientation performance but at a lower price because the calculations are done on your microcontroller, not in the sensor itself. The trade off is you will sacrifice about 15KB of Flash space, and computing cycles, to do the math 'in house.'

To make it fast and easy for you to get started, we have a version of AHRS that we've adapted to work over USB or Bluetooth LE. Load the code onto your Arduino-compatible board and you will get orientation data in the form of Euler angles or quaternions! It will work on a ATmega328 (the fusion code is 15KB of flash) but faster/larger chips such as M0 or ESP8266 will give you more breathing room.

Each board comes with the two chips soldered onto a breakout with 4 mounting holes. While the chips support SPI, they don't tri-state the MISO pin, so we decided to go with plain I2C which works well and is supported by every modern microcontroller and computer chip set.  There's a 3.3V regulator and level shifting on the I2C and Reset lines, so you can use the breakout safely with 3.3V or 5V power/logic. Each order comes with a fully assembled and tested breakout and a small strip of header. Some light soldering is required to attach the header if you want to use in a breadboard.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
