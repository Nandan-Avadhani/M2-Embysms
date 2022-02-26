# central Heating system 
# Block Diagram
![Block-Diagram-of-Temperature-Control-System-for-Smart-Home](https://user-images.githubusercontent.com/97897323/154857581-4f7dae04-08aa-4b82-8b6f-124f2c4bf05e.png)
# Power Supply
* External source of power supply that powers all buttons and microcontroller

# Buttons
* Thermostat controls to adjust the temperature to a comfortable level 
* button to turn on/off the device

# LED'S
* used to communicate with the user to indicate whether the device is turned on/off
* to indicate that the alarm is turned on

# Alarm
* to alert the user that the temperature has crossed the threshold limit

# Microcontroller
* performs the operations needed by the system
* the microcontroller helps in converting the chemical energy into thermal energy and convert that energy to heat and then deliver it to numerous spaces in the building 

# Temperature sensors 
* to determine the temperature inside the building and display it to the end user

# Clock
* needed for smooth performance of the microcontroller

# Actuators
* if the temperature of the room increases beyond a certain threshold limit in terms of temperature then the device performs according to the decision taken by the microcontroller in this case to turn off the heating system

# V-Model
# concept of operation
* cental heating system

# Requirements
* central system: a microcontroller
* sub system : Temperature sensor LED'S

# Low Level Requirements
* switch to turn on/off the heating system
* power supply needed for the operation of device i.e. for microcontroller, sensor,LED,Actuator,etc

# High Level Requirements
* to convert the chemical energy to thermal energy and transfer that energy into heat,which then is delivered to the spaces inside the building
* to increase the temperature of the room
* to make decision whether to turn off the heater if the temperature of the room passes the threshold

# Test Case
* when power is supplied to check whether the system is working or not(Y/N)
* when power is suppplied to check whether the led is turning on or not(Y/N)
* to check whether the microcontroller is receving the signal or not(Y/N).
* to check whether the temperature sensor is working or not(Y/N)