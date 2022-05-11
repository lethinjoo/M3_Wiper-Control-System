## Requirements

## Introduction

Wiper system is automatically ON during the time of rainfall. The senor is fixed in the vehicle glass. The conductive (Touch) sensor is used in this project. It senses the rainfall and giving control signal to the control unit. The control unit activates the wiper motor automatically.

## Components Used

## Stm32

The STM32 family of 32-bit microcontrollers based on the Arm® Cortex®-M processor is designed to offer new degrees of freedom to MCU users. It offers products combining very high performance, real-time capabilities, digital signal processing, low-power / low-voltage operation, and connectivity, while maintaining full integration and ease of development.

![image](https://user-images.githubusercontent.com/102678112/167770911-b81487e4-ff98-461d-ad48-6cf34fb3f297.png)

## Servo Motor

A servomotor is a rotary actuator or linear actuator that allows for precise control of angular or linear position, velocity and acceleration. It consists of a suitable motor coupled to a sensor for position feedback.


## Resistors

A resistor is a passive two-terminal electrical component that implements electrical resistance as a circuit element. In electronic circuits, resistors are used to reduce current flow.


## Capacitor

A capacitor is a device that stores electrical energy in an electric field. It is a passive electronic component with two terminals. The effect of a capacitor is known as capacitance.

## LED's

A light-emitting diode is a semiconductor light source that emits light when current flows through it. Electrons in the semiconductor recombine with electron holes, releasing energy in the form of photons.


## Cables and Connector

A cable, also known as a cord, plug, or connector transmits power or data between devices or positions, which is covered in plastic by one or more wires.

## Push Button

A push-button or simply button is a simple switch mechanism to control some aspect of a machine or a process. Buttons are typically made out of hard material, usually plastic or metal. 


## High Level Requirements

| ID | Description | Status |
|----|--------------|-------|
| HLR01 | Detecting rainfall and active automobile rain wiper | Implemented |
| HLR02 | It operate manually | Implemented |
| HLR03 | Displaying the information in led | Implemented |

## Low Level Requirements

| ID | Description | Status |
|----|--------------|--------|
| LLR01 | It work functionally according to outside water | Implemented |
| LLR02 | Consume less power | Implemented |

## 4W's and 1H

## What
Wipers system are operated by an electric motor and vechile.

## Why
The main purpose of the wiper system is to clean the windscreen sufficiently to provide suitable visibility at all times.

## When 
American inventor Mary Anderson received credit for the first operational windshield wiper, back in 1903. Anderson's “window cleaning device” used a rubber squeegee blade on an arm, operated via a hand-cranked lever from inside the vehicle.

## Where
Wipers system can be activated by a lever located to the right of the steering wheel. Pulling the lever down should activate the windshield wipers on their lowest setting

## How
When we turn the wiper on, the wiper switch sends the signal to the control module. The control module operates the wiper relay. The relay sends 12-volt power to the wiper motor.
