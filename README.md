# nrf24l01

Export of code.google.com/p/nrf24l01, see http://nrqm.ca/nRF24L01.

# Original README:

This driver provides an API for controlling the nRF24L01 radio from Nordic Semiconductor, with 
code running on the AT90USB1287. It should be more or less compatible with other AVR boards 
(and almost compatible with non-AVR boards) with a few changes to macro names and maybe the 
SPI driver.

See this for more information:

http://nrqm.ca/nRF24L01

This project includes a branch (/branches/arduino) for the driver to be built against the Arduino 
core library. It uses Arduino I/O and interrupt code instead of the raw AVR code but is otherwise
the same as the trunk. It includes an SPI driver for Arduino.

# License 

[New BSD License](http://opensource.org/licenses/BSD-3-Clause)

