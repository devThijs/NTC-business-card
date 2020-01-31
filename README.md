# NTC-business-card
NTC ntag business card circuit board for flexing purposes


Design files for an NTC ntag circuit board business card. 
The antenna coil is a winding pcb trace. It uses a NT3H2111 ic from NXP. An ATTINY416 is used as MCU.
The NT3H2111 IC features I2C capability and an energy harvesting capability. This allow for interesting possibilities. Such as simply lighting a LED, or on the fly reprogramming of the NFC chip's data by an external processor. This is all powered by wireless energy harvesting.
This design is an experiment to see how well this actually works. Theoretically, there should be enough power to do all kinds of (ultra low power) things.

User input is handled using capacitive touch sensing in the ATTINY416. Specifically, using the 'QtouchADC' peripheral. 