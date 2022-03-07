#  Abstract
* as thefts are increasing day by day and security is becoming a major concern nowadays we are designing a password based security system which uses a digital code which opens the door only when the right password is entered making the user's place more secure.

# Requirements
* central system: a microcontroller
* sub system : Keypad module

# Low Level Requirements
* LLR 1.1 switch to turn on/off the door lock security system.
* LLR 1.2 power supply needed for the operation of device i.e. for microcontroller, keypad module,LCD,Actuator,etc

# High Level Requirements
* HLR 1.1  write a program to store the correct password in arduino
* HLR 1.2 when wthe user enters the password to check whether it matches with the password stored in arduino. if it is correct then show "Access Granted Welcome" and then rotate the servo motor to 180 degree to open the door and then give 10 seconds for the user to enter and after 10 second lock the door automatically
* HLR 1.3 if the password entered by the user is incorrect then show "password incorrect go away" and buzzer beeps once any key is pressed

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

# Circuit diagram of password based security system based on arduino
![circiuit diagram](https://user-images.githubusercontent.com/97897323/157044663-f767709c-6039-458a-bd3f-3f3148592185.jpg)
# schematic diagram of password based security system based on arduino
![schematic diagram](https://user-images.githubusercontent.com/97897323/157044955-8bdf6daf-9584-4695-bdae-82dd30d92995.png)

# components Used
* Arduino UNO R3 Developement Board -1
* 4X3 keypad -1
* JHD 162A 16X2 LCD display -1
* Potentiometer 10K -1
* SG90 Servo motor -1
* 5V Active Buzzer -1
* Jumper Wires -20
* Breadboard - 1

# Test plan and output
* Hardware implementation

# Result Explanation
* 
