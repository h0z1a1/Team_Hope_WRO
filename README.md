Engineering Documentation | Team_Hope
====

This repository contains engineering materials of Robogee, a self-driven vehicle model from Team Team_Hope, participating in the WRO Future Engineers competition in the season of 2023.


## Team Members
In participating in the WRO Fuutre-Engineers 2023 our team conssits of:

* `Mohammad Marrwa`(The Team's Coach)-Email:mhd.marwa@multiaidprograms.org
* `Ahmad Shurbaji`- Email: Ahmad.Shurbaji0@gmail.com 
* `Mohammad Al-Sabag`- Email: eldeenseraj64@gmail.com 
* `Haitham Jammour`-Email: Haithamjaamour@gmail.com





## Repository Overview

* `v-photos` contains photos of the robot from all directions.
* `src` contains the code of control software for all components of Robogee.
* `other` is for other essential photos and files.

## Introduction

At the onset of our preparations for the competition, we embarked on extensive research to explore various options related to the design, programming, and algorithms for our self-driving car. After thorough investigation and analysis, we formulated a comprehensive plan to guide our development process. 


## Program arrangement and Algorithm Planning

Our self-driving robot integrates a high-resolution USB camera, Raspberry Pi, and Arduino Uno to achieve autonomous navigation. The USB camera captures visual data, while the Raspberry Pi processes it using computer vision algorithms for object detection and lane tracking. The Arduino Uno controls actuators and collects sensory information. This synchronized system enables our robot to perceive its environment, make informed decisions, and navigate autonomously. By leveraging these advanced components. The code is then divided into three major parts.



### Part 1 - Detecting run direction:
The first part determines the direction of the robot run. The robot moves slowly through the first straightforward section to ensure it can safely detect the direction of the run with its sonar sensors. Once it detects a large distance (>90cm) from one of the sensors, it marks the direction as “L” - clockwise, or “R” - anti-clockwise accordingly.



### Part 2 - Completing the run 






## Mechanical Desigen

At the forefront of our self-driving car project, we embarked on the mechanical design phase with a clear vision in mind: to create a robust and efficient vehicle that would excel in autonomous navigation. This phase marked a crucial step in translating our conceptual ideas into a tangible, functional reality.

As we delved into the mechanical design process, we were presented with a critical decision: to either procure a pre-built car or embark on the ambitious task of designing and manufacturing our own vehicle. After careful consideration and evaluation of the project's scope and requirements, we opted to take on the challenge of designing and printing our own car.

![WhatsApp Image 2023-06-21 at 1 03 45 PM](https://github.com/h0z1a1/Team_Hope_WRO/assets/137758764/045fa6f5-a6ef-46c7-9409-29dc318c0823)


![WhatsApp Image 2023-06-21 at 1 03 59 PM](https://github.com/h0z1a1/Team_Hope_WRO/assets/137758764/bd36fbb6-7573-40d0-9f19-0deb82af83c4)

After completing the initial prototype and installing the necessary components in the car, we encountered numerous challenges across different areas, such as sourcing suitable sensors, dealing with power supply issues, and overall inefficiency. As a result, we made the strategic decision to transition to an open-source design utilizing aluminum extrusion.
This move offers several advantages, most notably access to a vibrant and supportive community of developers.

## Parts List:


* Raspberry Pi 3

* Arduino Uno

* MPU6050

* 2x Adafruit HC-SR04 Ultrasonic Sensors

* 12V DC Motor

*  REV Smart Robot Servo

* 3x 3.7V lithium battery

* DC to DC converter


