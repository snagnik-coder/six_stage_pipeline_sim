# IITB-RISC-22 Pipelined Processor Project

This project involves the design and implementation of a 6-stage pipelined processor based on the IITB-RISC-22 architecture. The processor is optimized for performance and includes hazard mitigation techniques such as forwarding and branch prediction. This `Readme.md` file provides an overview of the project and instructions for setting up and running the simulation.

## Table of Contents

- [Introduction](#introduction)
- [Architecture Overview](#architecture-overview)
- [Pipeline Stages and Hazard Mitigation](#pipeline-stages-and-hazard-mitigation)
- [Branch Prediction Technique](#branch-prediction-technique)
- [Performance Evaluation](#performance-evaluation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Introduction

This project aims to create a 6-stage pipelined processor, IITB-RISC-22, based on the IITB-RISC-22 architecture. The processor incorporates hazard mitigation techniques including forwarding and branch prediction to enhance performance.

## Architecture Overview

The IITB-RISC-22 architecture is a 16-bit computer system with 8 registers. It includes general-purpose registers (R0 to R7) and a condition code register with Carry and Zero flags. The architecture allows predicated instruction execution, multiple load and store execution, and offers three machine-code instruction formats (R, I, and J type).

## Pipeline Stages and Hazard Mitigation

The pipelined processor follows a standard 6-stage pipeline:
1. Instruction Fetch
2. Instruction Decode
3. Register Read
4. Execute
5. Memory Access
6. Write Back

Hazard mitigation techniques, such as forwarding, are employed to handle data hazards and ensure smooth pipeline execution.

## Branch Prediction Technique

The processor incorporates a branch prediction technique to minimize the impact of branch instructions on pipeline performance.

## Performance Evaluation

The project includes a performance evaluation section that benchmarks the pipelined processor's performance using various test cases. Hazard scenarios are analyzed to assess the effectiveness of the hazard mitigation techniques.
