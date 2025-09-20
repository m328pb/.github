# ATmeag328p/pb projects
This is a collection of libraries and programs for ATmega328p. The main motivation is simplicity and memory efficency (also to learn and better understand but who cares). Arduino or Sparkfun libraries are enourmous in size which make them practically useless for any serious project on ATmega328, which is quite suprising...but it is what it is.

- each repo in this organization is written to be maximum lightweight (memory footprint is always reported in README.md)
- there is always simplicity in mind creating the lib, don't expect whitles and bells, just minimum set of fucntion needed for purpose.
- software is created with help of *platformio* so should be reasonably easy to use; libraries (or other code potentially reusable) has also `library.json` file which make it easy to include in other project by adding lib_deps to `platformio.ini`

# IC protocols

- ICinterface; common interface for protocols
- [I2C](https://github.com/m328pb/i2c);
- [SPI](https://github.com/m328pb/spi);
- [UART](https://github.com/m328pb/uart);

# DISPLAY

- ssd1306; interface to OLEDs on ssd1306
- HD44780; interface to LCD on HD44780

# OTHER
- [strings](https://github.com/m328pb/strings); collection of usefull string manipulation functions
