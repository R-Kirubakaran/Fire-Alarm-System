# Fire-Alarm-System
## Flame Sensor Arduino Project

### Abstract

A Flame Sensor is employed to detect fire or bright light using an Infrared Radiation Sensitive Sensor. This project details the implementation with a 60-degree detection angle and a 100cm range. The Flame Sensor, featuring VCC, GND, and DO pins, is connected to Arduino UNO. A Buzzer circuit, including a 1KΩ Resistor, NPN Transistor (2N2222 or BC548), 5V Buzzer, and PN Junction Diode, alerts to fire detection. Arduino code activates the Buzzer upon detecting a flame, changing the output from LOW to HIGH.

### Connections

- VCC: +5V
- GND: GND
- DO: Digital I/O Pin 11
- ## Introduction

- Fire alarm systems are integral to a building's life safety systems, playing a crucial role in saving lives and minimizing property damage.
- These systems not only enhance safety but also regulate other building systems, leading to substantial cost savings for property owners.
- This overview explores the components of various fire alarm systems and their impact on safety and functionality.

### Problem Statement

Safety is paramount in designing residential and commercial buildings to prevent loss of life and property damage. Existing fire alarm systems in the market are often too complex in design, requiring regular maintenance for optimal operation. However, this complexity can lead to increased maintenance costs.

### Objectives

The flame sensor module, equipped with a photodiode for light detection and an op-amp for sensitivity control, aims to simplify fire detection. Upon detecting a fire, it provides a HIGH signal. Arduino interprets this signal, triggering alerts through a buzzer and LED.
## project 
![Fire Alarm System][Fire Alarm System/Fire alarm project Diagram.jpg]
