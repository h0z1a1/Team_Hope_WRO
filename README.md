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




## Mechanical Desigen

At the forefront of our self-driving car project, we embarked on the mechanical design phase with a clear vision in mind: to create a robust and efficient vehicle that would excel in autonomous navigation. This phase marked a crucial step in translating our conceptual ideas into a tangible, functional reality.

As we delved into the mechanical design process, we were presented with a critical decision: to either procure a pre-built car or embark on the ambitious task of designing and manufacturing our own vehicle. After careful consideration and evaluation of the project's scope and requirements, we opted to take on the challenge of designing and printing our own car.

![WhatsApp Image 2023-06-21 at 1 03 45 PM](https://github.com/h0z1a1/Team_Hope_WRO/assets/137758764/045fa6f5-a6ef-46c7-9409-29dc318c0823)


![WhatsApp Image 2023-06-21 at 1 03 59 PM](https://github.com/h0z1a1/Team_Hope_WRO/assets/137758764/bd36fbb6-7573-40d0-9f19-0deb82af83c4)

After completing the initial prototype and installing the necessary components in the car, we encountered numerous challenges across different areas, such as sourcing suitable sensors, dealing with power supply issues, and overall inefficiency. As a result, we made the strategic decision to transition to an open-source design utilizing aluminum extrusion.
This move offers several advantages, most notably access to a vibrant and supportive community of 
developers.

https://github.com/h0z1a1/Team_Hope_WRO/blob/813c5d2b3da322c21aa2c08c1a3def9fc738b66c/v-photos/Down.jpeg


## Decision-Making
Our self-driving robot utilizes cutting-edge technology, incorporating the Rev Control Hub and distance sensors for enhanced autonomous navigation. The Rev Control Hub serves as the central brain, facilitating seamless communication between the various components. Additionally, we have integrated distance sensors both in the front and on the right and left sides of the robot, further augmenting its perception capabilities.

Key components of our self-driving robot include:

Rev Control Hub: The heart of our system, the Rev Control Hub, acts as the central control unit that synchronizes all operations. It effectively manages data flow, actuator control, and sensor readings, ensuring smooth coordination among the various subsystems.

High-Resolution USB Camera: Our robot is equipped with a high-resolution USB camera that captures visual data from its surroundings. The camera's feed is directed to the Rev Control Hub for processing and analysis.

Raspberry Pi: Integrated with the Rev Control Hub, the Raspberry Pi plays a critical role in our robot's autonomy. It utilizes advanced computer vision algorithms to perform real-time object detection and lane tracking based on the visual data received from the camera.

Arduino Uno: The Arduino Uno complements the Rev Control Hub by controlling actuators and collecting sensory information. It acts as an essential interface to various components, enhancing the robot's capabilities to interact with its environment effectively.

Distance Sensors: We have strategically placed distance sensors on the front, right, and left sides of the robot. These sensors provide valuable information about obstacles and distances to surrounding objects. The data collected from these sensors is transmitted to the Rev Control Hub for decision-making and navigation.

Our synchronized system enables the robot to perceive its environment accurately, make informed decisions based on real-time data, and navigate autonomously. By leveraging the advanced components of the Rev Control Hub and the precision of distance sensors, our self-driving robot achieves remarkable reliability and efficiency in various scenarios.

The codebase is organized into three major parts, each corresponding to a specific aspect of the robot's functionality: sensor integration and data processing, decision-making algorithms, and actuator control. The seamless collaboration between these components empowers our robot to navigate complex environments and accomplish its autonomous objectives effectively. Through our work, we aim to contribute to the advancement of self-driving technology and inspire further innovation in the robotics community.



