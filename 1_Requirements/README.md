# Wiper Control System

## Introduction 
The Repositirory gives the tutorial of usig the Qemu Emulator and also STM32 cube IDE.ON and OFF of Ignition by long pressing the blue botton 
and it is indicated by Red light.Blue, Green and Orange LEDs to show the rotation of wiper system and speed of Blinking of led is speed of 
the wiper system, which will be control with Frequency.

## Objective
The goal of this project is to know about the Wiper Control System.There will be one blue colour button on STM32.If we long press it the car 
will start Ignition and Just by Clicking it the Speed can be Change by changing the frequency.

## Requirements
* 4 LEDs
* Switch
* Some Internal Timer

##### LED
* Blue, Green and Orange LEDs
* RED LED for ON and OFF Ignition

## Operation
ON and OFF of Ignition by long pressing the blue botton and it is indicated by Red light.Blue, Green and Orange LEDs to show the rotation of wiper system 
and speed of Blinking of led is speed of the wiper system, which will be control with Frequency.

#### There will be 5 tasks.
* First task is to start the car: Assume Red LED indicates the Ignition Start or Stop, if Red LED On the Ignition will Start and if Red LED Off the Ignition will Stop.
* Start the Wiper System: Assume Blue, Green and Orange LEDs indicates the Rotation of Wiper. 
                          It will rotate from Blue, Green and Orange LEDs and while wiper come back indicates from Orange, Green and Blue LEDs.
                          It will rotate in a slow mode.
* 3rd and 4th task is related to Speed of  Blinking of LED it Indicates the speed of wipper system which will control with frequency.
* 5th task is to Off the Red LED Indicates the ignition is Stop it means the car is off.

LED for presentation of Wiper System,Speed of Blinking of LED is the speed of wiper and which is controlled with frequency.There are Blue colour bottom on STM32, 
if we long press the blue botton ( it may be 2sec) the Red LED will Glow it indicates the start of ignition.Then single press  Blue botton then Blue, Green and 
Orange LEDs Blink in a sequence this will indicates the wiper rotation.Once single press on Blue botton the speed of the  rotation of wiper increases by 
controlling the Frequency at 4Hz.Once again press the blue botton the speed of the  rotation of wiper increases by controlling the Frequency at 8Hz.
Then again long press on the blue botton ( it may be 2sec) the Red LED will Off it indicates the stop of ignition ( car is off).


## Scenario of Wiper Control System
#### 1.Ignition Key Position at ACC: 
The Red LED is ON, if the user button is pressed for long (it may be 2sec)
#### 2.Wiper ON: 
Wiper is OFF: On press of the user input, Blue, Green and Orange LEDs come ON one at a time with the set frequency, 
The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz
#### 3.Wiper OFF: 
Wiper is ON: The LED glow pattern stops on the 4th press; the wiper action starts next press onwards as mentioned in step 2
#### 4.Ignition Key Position at Lock: 
The Red LED is OFF, if the user button is pressed and held for 2 secs














