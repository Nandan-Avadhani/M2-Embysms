# Password based door lock security system
# Power Supply
* External source of power supply that powers all buttons and microcontroller

# Buttons
* keypad module to take the password from the user
* button to turn on/off the arduino uno


# Buzzer
* the buzzer is used for indications to the user regarding the system.


# LCD
* to display  the status of the system and to display the necessary messages

# servo motor
* to open the gate while rotating

# Microcontroller [Arduino Uno]
* performs the operations needed by the system
* Arduino controls the complete processes like taking the password from the keypad module,comparing passwords,driving buzzers,rotating servo motor,and sending status to the LCD display.

# Actuator
* servo motor for opening the gate while rotating 

# V-Model
# concept of operation
* Password based door lock security system.

# Requirements
* central system: a microcontroller
* sub system : Keypad module

# Low Level Requirements
* switch to turn on/off the door lock security system.
* power supply needed for the operation of device i.e. for microcontroller, keypad module,LCD,Actuator,etc

# High Level Requirements
* write a program to store the correct password in arduino
* when wthe user enters the password to check whether it matches with the password stored in arduino. if it is correct then show "Access Granted Welcome" and then rotate the servo motor to 180 degree to open the door and then give 10 seconds for the user to enter and after 10 second lock the door automatically
* if the password entered by the user is incorrect then show "password incorrect go away" and buzzer beeps once any key is pressed

# Test Cases
* when power is supplied to check whether the system is working or not(Y/N)
* when power is suppplied to check whether the LCD is turning on or not(Y/N)
* to check whether the microcontroller is receving the signal or not(Y/N).
* to check whether the servo motor is rotating 180 degree to open the door(Y/N)
* to check whether the buzzer is working or not(Y/N)
* to check whether the keypad module is taking the password or not(Y/N)
* to check whether the LCD is displaying the status of the system and displaying the messages or not(Y/N)
