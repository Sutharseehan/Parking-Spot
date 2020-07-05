# Parking Spot Sensor

Developed a system that detects motion using a PIR sensor and outputs the state through an LED

## Description

This system uses an Arduino board to hold the hardware components including, a PIR sensor, a LED, and wires. The components are then programmed to work together using Python as the programming language. The PIR sensor is set to the highest sensitivity, and once any such motion is detected, the LED would turn on and remain on as long as the PIR sensor detects motion. Once motion is no longer detected, the LED light turns off.

## Setup

```python
import RPi.GPIO as GPIO
import time
```
## Application

Although this is a very basic application of hardware components and the python language, it has a rather realistic and useful application. This system could be implemented in an overcrowded parking lot, such as malls, where people often spend the vast majority of their time finding a parking space. With the implementation of this system, people would be able to easily find an open parking spot and park their cars and decrease the amount of time spent in the parking lot, searching for a parking space.


## Roadmap

Plan to use multiple LEDs in the future. The LEDs will be used in a way such that, if motion is detected a green LED light will light up, and if no motion is detected, a red LED will light up.
