# AUTOMATIC PLANT IRRIGATION SYSTEM

# INTRODUCTION

Water shortage is one of the major problems in the world. Many different methods are incorporated for conservation of water. We need water in each and every field & is needed for every human being, animals, plants, etc. Agriculture is one such field where water is required in high quantity. Wastage of water is a major problem in agriculture. Every time excess of water is given to the fields. A number of techniques are available to save or to control wastage of water from agriculture.
#  DESIGN
## BLOCK DIAGRAM
![block diagram](https://user-images.githubusercontent.com/98830460/155117259-a0befc4c-c33d-4011-ad01-4ded7db31f37.png)
# SWOT ANALYSIS
![SWOT](https://user-images.githubusercontent.com/98830460/155152539-35c819b7-9459-40f9-896d-0516e82bc71c.png)


# 4W'S and 1 H
 ## WHO
 The automatic plant irrigation system can be used by farmer's, who need the self irrigate the crop's. 
 ## WHAT
 It automaticly give the water to the plants by senseing the water content in the field.  
 ## WHEN
 It is active all the time and notifies in case of needed in irrigation.
 ## WHERE
 It can be used in the large field, small field, garden etc
 ## HOW
It requires a PC or laptop along with embedded device and sensors to complete.

# COMPONENTS REQUIRED
## Humidity/Soil Moisture Sensor:
The humidity/soil moisture sensor just senses the humidity or the moisture of the soil. The change in humidity is proportional to the amount of current flowing through the soil.
## Diode (In4007):
 It allows unidirectional flow of current/power supply to the system.
## Potentiometer: 
It is used to control the contrast of the LCD display.

## Voltage Regulator Ic7805: 
Voltage regulator IC converts fluctuating ac voltage in to constant dc voltage.
## Temperature Sensor:
 LM35 sensor is used to record the atmospheric temperature which is then displayed on LCD.
## Microcontroller Atmega 328: 
It is a single chip microcontroller. This 8 bit microcontroller has 32kB flash memory with read-write features. It has 32 general purpose working registers, and 3 flexible timer counters. It also has internal-external interrupts and serial programmable USART. It has 28 pins out of which maximum 18 pins are used.
## Oscillator: 
A 16MHz oscillator is used to provide constant non-fluctuating frequency to the microcontroller.
#3 Motor: 
Motor is used to indicate the on/off state of pump when soil is wet/dry. It is controlled by microcontroller as programmed.


## LCD (16x2):
 This is the first interfacing example for the Parallel Port. It is used to display the current statistic on the screen.
## Power Supply:
 Power supply of 12V is used for running this hardware system.
## Reference Voltage: 
It is the ideal defined voltage.
## GSM Module: 
This system is connected to a communication device called “GSM Module”. It can be connected to different devices such as modems, cellular phones or satellite terminal to activate the remote collection of recorded data or alarming of certain parameters. The connections between the two mobiles are done using GSM. When the soil moisture sensor senses the low moisture content of the soil, it gives a signal to the microcontroller. The microcontroller then gives a signal to the GSM Module which further sends a message to the mobile.

# PROPOSED WORK
The project is designed to function as an automatic irrigation system which turns the pump/motor ON/OFF depending upon the humidity content of the soil. The project uses ATMEGA 328 microcontroller which is programmed to receive the input signal of varying moisture condition of the soil through the sensing arrangement. This is achieved by using an op-amp as comparator which acts as interface between the sensing arrangement and the microcontroller. An LCD display is also interfaced to the microcontroller to display status of the soil and water pump. The sensing arrangement is made by using two stiff metallic rods inserted into the field at a distance.

#  ADVANTAGES
 • Saves water
 • Improves growth 
• Discourages weeds 
• Saves time 
• Helps control fungal diseases 
• Adaptable 
• Eliminates the manual operation of opening or closing valves 
• Adaption of the advanced irrigation systems and the new technologies, especially the new irrigation systems that are complex and difficult to operate manually. 
• The system will be operated in night also which results in minimization of the water loss due to evaporation. 
• Irrigation process starts and stops exactly when required, thus optimizing energy requirements

# CONCLUSION
The purpose of designing of Automatic Plant Irrigation System is successfully achieved and fulfills the desired objectives. The hardware and software used performed their function properly to produce desired result which is the required for the farmers in the irrigation field. Interfacing of run time switches with microcontroller makes it flexible in respect of time settings for running a water pipe line. Using this system, farmers will get the protection while doing the irrigation work in extremely odd weather conditions, hard work of repeated assembly and will get rid of poisonous reptiles. The system, which is designed, will help the farmers to do the irrigation process in night also. The system designed do not requires the physical presence of the farmers during irrigation in the fields. The system is automatically monitored and controls the pump on and off.

