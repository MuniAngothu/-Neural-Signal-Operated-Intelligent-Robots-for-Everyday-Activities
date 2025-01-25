# NOIR: Neural Signal Operated Intelligent Robots for Everyday Activities

This repository contains the source code, datasets, and documentation for the project **NOIR**. The system utilizes **Electroencephalography (EEG)** signals for real-time brain-robot interaction. It aims to improve accessibility, independence, and rehabilitation for individuals by decoding neural signals into actionable robotic commands.

## Table of Contents

- [Introduction](#introduction)
- [Motivation](#motivation)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Scope](#future-scope)


---

## Introduction

NOIR integrates **Artificial Intelligence (AI)** and **Machine Learning (ML)** with EEG signal decoding to:
- Detect abnormal brain activities.
- Decode neural commands for robotic control.
- Enhance human-robot interaction and assistive robotics.

### Objectives
1. Develop a versatile Brain-Robot Interface (BRI) system.
2. Implement EEG-based signal decoding pipelines.
3. Train ML models for accurate EEG classification.
4. Enable real-time robotic control.
5. Validate the system’s effectiveness using simulated and real-world EEG data.

---

## Motivation

This project is driven by the goal to:
- Enhance emotional well-being and mental health monitoring.
- Empower individuals with disabilities and senior citizens.
- Advance neurorehabilitation and assistive technologies.

---

## Features

- **EEG Signal Processing**: Noise reduction, artifact removal, and bandpass filtering.
- **Deep Learning Models**: Neural Networks and RNN-GRU for EEG classification.
- **Real-Time Control**: Simulated robotic actions based on EEG classifications.
- **Applications**: Cognitive rehabilitation, motor skill training, and assistive robotics.

---

## System Architecture

![System Architecture](path/to/system_architecture_diagram.png)

1. **Data Acquisition**: Simulated and real EEG signals.
2. **Preprocessing**: Filtering and feature extraction.
3. **Classification**: Using Neural Networks (Simple NN, RNN, GRU).
4. **Robotic Control**: Adaptive responses based on classifications.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MuniAngothu/NOIR.git
   cd NOIR
