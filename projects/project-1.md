---
layout: project
type: project
image: images/hudphoto3.jpg
title: Motorcycle Heads-Up Display (HUD)
permalink: projects/motorcycleHUD
# All dates must be YYYY-MM-DD format!
date: 2018-07-01
labels:
  - Robotics
  - Arduino
  - C++
  - Optics
summary: Prototype HUD that can be inserted into any helmet to display rear blindspots.
---

<h1>Motorcycle Heads Up Display</h1> 
Our Motorcycle HUD project is designed to provide a universal drop-in HUD to increase a motorcyclist's field of view. The wind drag caused by turning the helmet into a less aerodynamic position at higher speeds can cause the rider's bodyweight to shift, which in turn causes the rider to quickly drift into another lane position. At higher speeds, the drag force exerted on riders' helmets can be strong enough as to torque the neck enough to cause muscle strains. The goal of this project is to minimize the amount of time riders must spend turning their head when traveling at speed. 

<h2>Components</h2>
The HUD system is composed of three subsystems. The first part is a wirelessly controlled servo-mounted camera that is to be placed on the back of the motorcycle. The servo will automatically pivot in the direction of the intended lane change when the rider turns on either turn signal. A sample circuit setup is shown in Figure 1 below.

<img class="ui image" src="../images/cameraCircuit.png">
<h3>Figure 1. Wirelessly controlled servo circuit</h3> 

The second part of the system is the camera-display system. Our original prototype used long wires to connect the camera to a micro LCD display. However, the next version will have a wireless connection between the camera circuit and LCD display. A sample circuit for the camera-display feed  is shown in Figure 2 below.

<img class="ui image" src="../images/arduinoCircuit.png">
<h3>Figure 2. Arduino used as video processor</h3> 

The third subsystem is the optics component. This consists of two lenses and a glass pane positioned in such a way as to project a virtual image of the display without obstructing the rider's field of view. The magnification power of the lenses were chosen so that the virtual image is large enough and far enough as to be seen without the rider having to refocus their eyes. Doing so reduces the strain on the rider's eyes and minimizes the reaction time when changing focal points. The display pane was inserted in the helmet as shown in Figure 3 below.

<img class="ui image" src="../images/arduinoCircuit.png">
<h3>Figure 3. Transparent Heads Up Display in helmet</h3> 

For this project, I was the lead programmer who was responsible for programming the Arduino controllers. I started by programming the basics, such as wireless communication between devices and mapping the controls to the servo. The code used to supply camera feed to the LCD screen was sourced from open projects on GitHub. My partner, Keenan Lee, and I both contributed to the wiring and soldering of the electrical components. 

  
  

