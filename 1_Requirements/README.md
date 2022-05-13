# Wiper Control System

## Introduction 
The Repositirory gives the tutorial of usig the Qemu Emulator and also STM32 cube IDE.ON and OFF of Ignition by long pressing the blue botton and it is indicated by Red light.
Blue, Green and Orange LEDs to show the rotation of wiper system and speed of Blinking of led is speed of the wiper system, which will be control with Frequency.

## Objective
The goal of this project is to know about the Wiper Control System.There will be one blue colour button on STM32.If we long press it the car will start Ignition and Just by 
Clicking it the Speed can be Change by changing the frequency.

## Requirements
* 4 LEDs
* Switch
* Some Internal Timer

##### LED
* Blue, Green and Orange LEDs
* RED LED for ON and OFF Ignition

## Operation

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














