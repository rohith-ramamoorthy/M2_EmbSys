# AUTOMATIC PLANT IRRIGATION SYSTEM

## INTRODUCTION

Water shortage is one of the major problems in the world. Many different methods are incorporated for conservation of water. We need water in each and every field & is needed for every human being, animals, plants, etc. Agriculture is one such field where water is required in high quantity. Wastage of water is a major problem in agriculture. Every time excess of water is given to the fields. A number of techniques are available to save or to control wastage of water from agriculture.

## BLOCK DIAGRAM
![block diagram](https://user-images.githubusercontent.com/98830460/155117259-a0befc4c-c33d-4011-ad01-4ded7db31f37.png)

## SWOR ANALYSIS

## HIGH LEVEL REQUIREMENT
## LOW LEVEL REQUIREMENT


## COMPONENTS REQUIRED
# Humidity/Soil Moisture Sensor:
The humidity/soil moisture sensor just senses the humidity or the moisture of the soil. The change in humidity is proportional to the amount of current flowing through the soil.
# Diode (In4007):
 It allows unidirectional flow of current/power supply to the system.
# Potentiometer: 
It is used to control the contrast of the LCD display.

# Voltage Regulator Ic7805: 
Voltage regulator IC converts fluctuating ac voltage in to constant dc voltage.
# Temperature Sensor:
 LM35 sensor is used to record the atmospheric temperature which is then displayed on LCD.
# Microcontroller Atmega 328: 
It is a single chip microcontroller. This 8 bit microcontroller has 32kB flash memory with read-write features. It has 32 general purpose working registers, and 3 flexible timer counters. It also has internal-external interrupts and serial programmable USART. It has 28 pins out of which maximum 18 pins are used.
# Oscillator: 
A 16MHz oscillator is used to provide constant non-fluctuating frequency to the microcontroller.
# Motor: 
Motor is used to indicate the on/off state of pump when soil is wet/dry. It is controlled by microcontroller as programmed.


# LCD (16x2):
 This is the first interfacing example for the Parallel Port. It is used to display the current statistic on the screen.
# Power Supply:
 Power supply of 12V is used for running this hardware system.
# Reference Voltage: 
It is the ideal defined voltage.
# GSM Module: 
This system is connected to a communication device called “GSM Module”. It can be connected to different devices such as modems, cellular phones or satellite terminal to activate the remote collection of recorded data or alarming of certain parameters. The connections between the two mobiles are done using GSM. When the soil moisture sensor senses the low moisture content of the soil, it gives a signal to the microcontroller. The microcontroller then gives a signal to the GSM Module which further sends a message to the mobile.

