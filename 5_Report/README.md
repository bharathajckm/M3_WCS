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

## Operation
ON and OFF of Ignition by long pressing the blue botton and it is indicated by Red light.Blue, Green and Orange LEDs to show the rotation of wiper system 
and speed of Blinking of led is speed of the wiper system, which will be control with Frequency.

#### There will be 5 tasks.
* First task is to start the car: Assume Red LED indicates the Ignition Start or Stop, if Red LED On the Ignition will Start and Red LED Off the Ignition will Start.
                                  In First task Red LED will On and the Ignition will Start
* 2nd task is to Start the Wiper System: Assume Blue, Green and Orange LEDs blink will indicates the Rotation of Wiper. 
                          It will rotate from Blue, Green and Orange LEDs and while wiper come back indicates from Orange, Green and Blue LEDs.
                          It will rotate in a slow mode.
* 3rd and 4th task is related to Speed of  Blinking of LED it Indicates the speed of wipper system which will control with frequency.
* 5th task is to Off the Red LED Indicates the ignition is Stop it means the car is off.

LED for presentation of Wiper System,Speed of Blinking of LED is the speed of wiper and which is controlled with frequency.There are Blue colour bottom on STM32, 
if we long press the blue botton ( it may be 2sec) the Red LED will Glow it indicates the start of ignition.Then single press Blue botton then Blue, Green and 
Orange LEDs Blink in a sequence this will indicates the wiper rotation.Once single press on Blue botton the speed of the  rotation of wiper increases by 
controlling the Frequency at 4Hz.Once again press the blue botton the speed of the  rotation of wiper increases by controlling the Frequency at 8Hz.
Then again long press on the blue botton ( it may be 2sec) the Red LED will Off it indicates the stop of ignition ( car is off).

 
## TestCases
In this Assume Red LED indicates the Ignition Start or Stop.
Assume Blue, Green and Orange LEDs indicates the Rotation of Wiper. 


| TestCase         |                  Description                                                   |     Result                                    |
| -----------------|:------------------------------------------------------------------------------:|----------------------------------------------:|
|   First task     | Red LED will On and the Ignition will Start ( car is on)                       | Red LED will on (Ignition will Start)         |
|   2nd task       | Blue, Green and Orange LEDs blink will indicates the Rotation of Wiper         | Blue, Green and Orange LEDs will blink        |
| 3rd and 4th task | Blue, Green and Orange LEDs blinks Fast controlled by Frequency of 4Hz and 8Hz | Blue, Green and Orange LEDs will blink fast   |
|     5th task     | Red LED will Off by long press and the Ignition will Start ( car is off)       | Red LED will off (Ignition will Stop)         |


## Output

Red LED will ON by long press of Blue botton in STM32, will indicate the Ignition Starts (Car is Started).
Next Single press Blue botton the Blue, Green and Orange LEDs Blink in a sequence this will indicates the wiper rotation.
Again Single press Blue botton the speed of the Blink will increase by Increasing the Frequency at 4Hz.
Once Again Single press Blue botton the speed of the Blink will increase by Increasing the Frequency at 8Hz.
Long press of Blue Botton(may be 2sec) the Red LED will OFF, will indicate the Ignition Stops (Car is Stops).



