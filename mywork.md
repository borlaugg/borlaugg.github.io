---
layout: post
title: My Work
---

Hi! Sorry I haven't updated this; here's my [CV](/assets/CV.pdf) instead

## 2D mapping system for Corrosion Monitoring Product
The problem at hand asks us to devise a mechanism that will remotely map the path/terrain a droid tracks. This is similar to the SLAM problem of localizing and mapping the surrounding as an autonomous vehicle moves. The droid being moved manually removes the problem of an autonomous drive. We only need to 'sense' our surroundings and transmit the readings to a base station. Alternatively, we could track the droid's movement, keeping track of its 'pose' and 'movement'. This will help us mathematically model the droid's motion in a 2D plane using Newtons's equations. Once we have an estimate of the path the droid traces, the mapping will involve plotting this on a graph.
<p align="center">
<img src="https://github.com/borlaugg/borlaugg.github.io/blob/6522fcae367577e63c755e57f779b0213fd8b34a/assets/img/Probe.jpeg" alt="Probe" width="350"/>               
</p>

 We have used two different sensors for this project, an Inertial Measurement Unit(IMU), which includes a 6-axis gyroscope and accelerometer, and a Rotary Encoder. The purpose of IMU is to give us the orientation of the bot in order to track rotation. The optical encoder was used to obtain the speed of the bot, which was required to obtain X-Y coordinates. Additionally, we have used a photoresistor to plot the variance of ambient light as the droid traverses. This way, we could plot a heat map of the ambient light intensity for different locations. A Bluetooth module will be used to transmit data to a computer for further computation. Python is used for mapping. As per instructions, Raspberry Pi Pico MCU was used to interface the sensors and Bluetooth module. The Bluetooth module and Raspberry Pi Pico MCU were interfaced on the PCB along with the sensors, while the power was supplied externally. All this was packaged inside a four-wheeled box.
The complete report can be found [here](/assets/EDL_DESIGN.pdf).
