---
layout: page
title: My Work
---

Hi! Sorry I haven't updated this; here's my [CV](/assets/CV.pdf) instead

### Past Projects

## Cache Security From Side Channel Attacks
Studied the vulnerabilities of shared cache and attacks like Flush+Reload, and Prime+Probe. Replicated the work of PASS-P, an algorithm that mitigates the threat of such hardware attacks. Implemented a modified PASS-P algorithm by introducing a more effective and dynamic insertion policy -DAAIP. The detailed report can be found [here](/assets/Rishabh_200260041_RnD_report.pdf).

## 2D mapping system for Corrosion Monitoring Product
The problem asks us to devise a mechanism to map the path/terrain droid tracks remotely. This is similar to the SLAM problem of localizing and mapping the surrounding as an autonomous vehicle moves. The droid being moved manually removes the problem of an autonomous drive. We only need to 'sense' our surroundings and transmit the readings to a base station. Alternatively, we could track the droid's movement, keeping track of its 'pose' and 'movement'. This will help us mathematically model the droid's motion in a 2D plane using Newtons's equations. Once we have an estimate of the path the droid traces, the mapping will involve plotting this on a graph.

<p align="center">
<img src="/assets/img/EDL.jpg" alt="EDL" width="300"/>               
</p>

Received recognition for outstanding performance and achieving top rankings among a competitive field of projects. This project was ranked among the top 3 projects out of 60+ projects.
The complete report can be found [here](/assets/EDL_DESIGN.pdf).

## Superscalar Out of Order Processor


## RISC Pipelined Processor
Building on the Multistage processor, I built a 6 stage pipelined processor in VHDL. To tackle the pipelining hazards I developed a branch predictor, data forwarding unit and a hazard unit to detect data dependancies. I evaluated the design once again by running RTL simulation and Gatelevel simulations. This processor achieved a peak performance of 1.94 cycle/instruction. The repository containing the code can be found [here](https://github.com/borlaugg/RISC-processor-with-pipelining.git). Having developed a pipelined processor, we expanded it to a 2-way fetch superscalar processor handling out-of-order execution. The repository can be found [here](https://github.com/borlaugg/OoO.git)

## RISC Multistage Processor
I developed a Multistage Reduced Instruction Set Computer, enitrely in VHDL. We evaluated the design by running RTL simulation and Gatelevel simulations. The design can be found [here](https://github.com/borlaugg/Multistage-Processor/blob/4c2cf56df1689e0abbcdafab8be9c9def99544c4/Project1-RISC-Processor-Design.pdf)
