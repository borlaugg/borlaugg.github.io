---
layout: page
title: My Work
---

Hi! Sorry I haven't updated this; here's my [CV](/assets/CV.pdf) instead

# Ongoing Projects

## HW/SW Codesign for Accelerating CFD Applications

# Past Projects

## Accelerating Ray Tracing
Parallelized a RayTracing algorithm using OpenMP and CUDA, achieving a speedup of 7x. Additionally, performed a comparative study on OpenMP and CUDA and quantized their overheads.

The complete report can be found [here](/assets/RAY-tracing.pdf).

## SCAM: Secure Shared Cache Partitioning Scheme

## Subsampling of Correlated Graph Signals [arXiv](https://arxiv.org/abs/2409.04107)
Devised an algorithm to approximate correlated graph signals into a lower-dimensional space using low-rank approximations that allowed for spatial signal subsampling and reconstruction. Proved that the reconstruction error for deleting two or more nodes was dependent on the nature of the graph and had perfect reconstruction for the deletion of just one node. 

## A Review of Commercial Accelerator Architectures

## tinyVTA: FPGA-based Accelerator for Neural Networks
Implemented an accelerator for floating point operations such as block matrix-multiply-accumulate and activation function of DNN inference to an FPGA. Also verified the correctness by testing against the MNIST dataset using a large, fully connected model on the Xilinx ZCU104 FPGA and observing consistent results across all 128 test examples
The complete report can be found [here](/assets/tinyVTA.pdf).

## Reproducing the results of R3DLA on GEM5

## 2D mapping system for Corrosion Monitoring Product
The problem asks us to devise a mechanism to map the path/terrain droid tracks remotely. This is similar to the SLAM problem of localizing and mapping the surrounding as an autonomous vehicle moves. The droid being moved manually removes the problem of an autonomous drive. We only need to 'sense' our surroundings and transmit the readings to a base station. Alternatively, we could track the droid's movement, keeping track of its 'pose' and 'movement'. This will help us mathematically model the droid's motion in a 2D plane using Newtons's equations. Once we have an estimate of the path the droid traces, the mapping will involve plotting this on a graph.

<p align="center">
<img src="/assets/img/EDL.jpg" alt="EDL" width="300"/>               
</p>

Received recognition for outstanding performance and achieving top rankings among a competitive field of projects. This project was ranked among the top 3 projects out of 60+ projects.
The complete report can be found [here](/assets/EDL_DESIGN.pdf).

## Model based Embedded System Design
<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/cV9TXogiC-Q?si=dx-bAtAr1WJF_JSZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>
We developed an embedded system using model-based design for autonomous valet-parking. It also included an algorithm for line following, track color inversion, and parking-space identification


## RISC Pipelined Processor
Building on the Multistage processor, I built a 6 stage pipelined processor in VHDL. To tackle the pipelining hazards I developed a branch predictor, data forwarding unit and a hazard unit to detect data dependancies. I evaluated the design once again by running RTL simulation and Gatelevel simulations. This processor achieved a peak performance of 1.94 cycle/instruction. The repository containing the code can be found [here](https://github.com/borlaugg/RISC-processor-with-pipelining.git). Having developed a pipelined processor, we expanded it to a 2-way fetch superscalar processor handling out-of-order execution. The repository can be found [here](https://github.com/borlaugg/OoO.git)

## RISC Multistage Processor
I developed a Multistage Reduced Instruction Set Computer, enitrely in VHDL. We evaluated the design by running RTL simulation and Gatelevel simulations. The design can be found [here](https://github.com/borlaugg/Multistage-Processor/blob/4c2cf56df1689e0abbcdafab8be9c9def99544c4/Project1-RISC-Processor-Design.pdf)
