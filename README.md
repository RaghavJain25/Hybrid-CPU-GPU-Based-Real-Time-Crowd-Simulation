# Hybrid CPU-GPU Based Real-Time Crowd Simulation

A high-performance real-time crowd simulation system built using a hybrid CPU–GPU architecture to simulate large-scale evacuation and crowd movement scenarios efficiently.

## Overview

This project implements a scalable crowd simulation framework capable of handling thousands of agents in real time using parallel computing principles. The system models realistic crowd behavior using the Boids algorithm and accelerates computationally intensive tasks through GPU parallelization.

The project was developed as part of the Parallel and Distributed Computing (UCS645) course at Thapar Institute of Engineering and Technology.

---

## Features

- Real-time crowd simulation
- Hybrid CPU–GPU execution model
- Boids-based behavioral modeling
- Collision avoidance and path navigation
- Scalable architecture supporting up to 20,000 agents
- GPU accelerated parallel computation
- Crowd density visualization and heatmapping
- Performance benchmarking and FPS analysis

---

## Technologies Used

- C++
- CUDA
- Parallel Computing
- OpenGL / Graphics Rendering
- GPU Programming
- Data Visualization

---

## Core Concepts

The simulation is based on the following Boids behavioral rules:

- Separation – Avoid collisions between agents
- Alignment – Match velocity with nearby agents
- Cohesion – Move toward neighboring group centers

The GPU handles parallel agent interaction calculations while the CPU manages rendering, control flow, and user interaction.

---

## Performance Highlights

- Simulates up to 20,000 agents
- Maintains real-time responsiveness
- Achieves significant speedup compared to CPU-only implementations
- Demonstrates scalable parallel execution

---

## Results

The hybrid CPU–GPU implementation showed:

- Higher FPS stability under dense crowd conditions
- Lower execution time per frame
- Improved computational throughput
- Realistic crowd behaviors such as:
  - Bottleneck formation
  - Lane formation
  - Density-based congestion visualization

---

## Applications

- Evacuation planning
- Smart city simulations
- Pedestrian traffic analysis
- Swarm robotics
- Intelligent transportation systems

---

## Future Improvements

- Multi-GPU support
- AI-driven crowd prediction
- Dynamic obstacle handling
- 3D environment simulation
- Reinforcement learning integration

---

## Authors

- Raghav Jain
- Narhar Singh
- Harkirat Singh

Under the guidance of Dr. Saif Nalband  
Thapar Institute of Engineering and Technology

---

## License

This project is licensed under the MIT License.
