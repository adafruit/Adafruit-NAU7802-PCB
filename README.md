## Adafruit NAU7802 24-Bit ADC - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/4538"><img src="assets/4538.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit NAU7802 24-Bit ADC - STEMMA QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4538

### Description

If you are feeling the stress and strain of modern life a Wheatstone bridge and you want to quantify it, this handy breakout will do the job, no sweat! The Adafruit NAU7802 contains a super-high-resolution 24-Bit differential ADC with extra gain and calibration circuitry that makes it perfect for measuring strain gauges / load cells or other sensors that have four wires that are connected in a Wheatstone bridge arrangement.

Each breakout comes with a NAU7802 ADC chip, plus some support circuitry, and 4 terminal blocks that can be used to connect a 4-wire sensor.

The E- pad connects to ground (often a black wire), the E+ pad connects to a generated voltage from the NAU7802 that can be configured from 2.4V to 4.0V for a solid positive reference (often a red wire).

Then A- and A+ pads connect to the differential outputs from the bridge. For example, connecting to a strain gauge these tend to be the white and green wires.

As the sensor is twisted and bent, the slight changes in resistance are converted to minuscule voltage changes that can be read by the NAU ADC for converting into force or mass measurements. You can use our Arduino library or CedarGrove's CircuitPython/Python library to configure and read the ADC for fast interfacing. Note that this sensor has a fixed I2C address, if multiple sensors are desired on one I2C bus, a multiplexer can be used.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
