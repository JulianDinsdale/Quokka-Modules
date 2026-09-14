
BUZZER Module
=============
QK-02-021
               
.. image:: /BUZZER_images/image_001.png
   :width: 300px
   :align: center


Description     
                                                       
The Buzzer module emits an audible sound typically in the range of 100 to 600Hz when a signal (Logic High) is applied to the module.  It is typically used as an audio signalling device for alarms or audio indications.
The Buzzer has a 3 pin Quokka interface which allows simple plug and play connections to the Kookaberry.
The Buzzer module may be turned on and off by the Kookaberry with a logic High or Low output signal - alternatively pulse width modulation (PWM) may be used to allow simple volume control of the module

Specification

	Operating Temperature 	-10 to 50 deg C
Interface	Quokka 3 Pin JST PH 
Pin 1= Signal, Pin2= VCC, Pin 3 = GND
	Voltage				3.3 volts max 
	Size				20 x 35 mm

Pinout
	
Connector - JST PH 3 Pin

               Pin 1 – Signal        On = Hi=3.3 volts (max) 
   Off = Low = 0 volts
	Pin 2 – VCC            3.3 volts (max) 
	Pin 3 - GND            0 volts

Application

The Buzzer make an audible sound and as such can be used in a variety of applications.  It could for example be used as an intruder alert or an indication that a process has finished.  It is simple to use with a HI signal turning it ON and a LOW signal turning it OFF.  The use of the Buzzer with pulse width modulation (PWM) allows the sound level to be varied.


The Buzzer can be connected directly to connectors P1, P2, P4 or P5 on the Kookaberry with a 3 pin to 3 pin JST PH cable (QK-03-022).  These connectors on the Kookaberry are 3 pin JST PH connectors that conform to the Quokka interface

Sample Code   

KookaBlocs

The following code / script demonstrates turning on and off the Buzzer.  Press Button A on the Kookaberry to turn the Buzzer ON and Press button B to turn it off.

                  


KookaCode
                





Block Schematic


  
