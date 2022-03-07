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
# SWOT Analysis 

# Strengths
* Easy to use application
* removes the necessity of having a physical key to open the door
* safer then having a typical lock key mechanism for the door
* users do not need to worry about carrying or losing the keys to their doors

# Weaknesses
* problem if the password is forgotten
* can cause inconveince  to the user if the door does not close/open in proper time
* the door may not close or open if there is a issue in the system
* the user must remember the password or store it elsewhere

# Oppurtunities
* we can replace the traditional lock and key mechanism in doors with this system if the system is made cheap and affordable
* is very sclable and has a large market for such a product

# Threats
* can lead to theaft/robbery if the password is leaked 
* the system might fail in case of loss of power supply 

# 5W 1H
# Who
* can used by people around the world 

# What
* it is a password based door lock security system

# When
* can be used when it is necessary to lock the door and key is not available 

# Where
*  can be used in homes,banks,restuarants,malls etc

# Why
* can be used for enchancing the security of door lock system and to replace the lock and key mechanism

# How
* to design this system the programme is written in c and the microcontroller used controls the processes like taking the password from the keypaad module comparing passwords driving buzzers and driving the servo motor and sending the status to the LCD display.

# Test Cases
* when power is supplied to check whether the system is working or not(Y/N)
* when power is suppplied to check whether the LCD is turning on or not(Y/N)
* to check whether the microcontroller is receving the signal or not(Y/N).
* to check whether the servo motor is rotating 180 degree to open the door(Y/N)
* to check whether the buzzer is working or not(Y/N)
* to check whether the keypad module is taking the password or not(Y/N)
* to check whether the LCD is displaying the status of the system and displaying the messages or not(Y/N)
