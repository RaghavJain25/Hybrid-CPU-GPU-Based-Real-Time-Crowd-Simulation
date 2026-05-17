# Hybrid CPU-GPU Based Real-Time Crowd Simulation

## 🚀 Project Overview

Hybrid CPU-GPU Based Real-Time Crowd Simulation is a high-performance parallel computing project designed to simulate realistic crowd movement and evacuation behavior in real time.

The project leverages the computational power of GPUs to efficiently process large-scale agent interactions while maintaining smooth simulation performance. Traditional CPU-based crowd simulations struggle to handle dense environments due to quadratic computational complexity. This project overcomes that limitation using a hybrid CPU–GPU architecture.

The system is capable of simulating up to 20,000+ agents while preserving realistic crowd dynamics such as congestion, collision avoidance, bottleneck formation, and lane development.

---

# 📌 Key Features

- Real-time crowd simulation
- Hybrid CPU-GPU architecture
- Massive parallel processing using CUDA
- Boids-based behavioral modeling
- Dynamic collision avoidance
- Multi-agent path navigation
- Crowd density heatmap visualization
- Performance benchmarking
- Scalable simulation framework
- Realistic evacuation behavior
- Interactive simulation environment

---

# 🧠 Problem Statement

Traditional crowd simulation systems become computationally expensive as the number of agents increases. Since every agent continuously interacts with neighboring agents, the complexity grows rapidly.

This project addresses the challenge of:

- Maintaining real-time responsiveness
- Efficiently handling thousands of agents
- Preserving behavioral realism
- Reducing CPU bottlenecks
- Optimizing computational throughput

The solution uses GPU parallelization to accelerate interaction calculations and maintain stable frame rates under dense crowd conditions.

---

# ⚙️ System Architecture

## CPU Responsibilities
- Rendering and visualization
- User interaction
- Simulation control flow
- Data initialization
- GUI handling

## GPU Responsibilities
- Parallel agent interaction calculations
- Velocity updates
- Position updates
- Collision handling
- Boids rule computation

---

# 🧩 Core Behavioral Rules

The simulation is based on the famous **Boids Model** introduced by Craig Reynolds.

Each agent follows three core behaviors:

## 1. Separation
Agents avoid collisions with nearby agents.

## 2. Alignment
Agents align their movement direction with neighboring agents.

## 3. Cohesion
Agents move toward the average position of nearby agents.

These simple rules collectively produce realistic emergent crowd behavior.

---

# 📊 Mathematical Model

Velocity update equation:

vᵢ(t + 1) = vᵢ(t) + wₛSᵢ + wₐAᵢ + w𝒸Cᵢ

Where:
- Sᵢ = Separation vector
- Aᵢ = Alignment vector
- Cᵢ = Cohesion vector

The computational complexity of traditional implementations is:

O(N²)

GPU parallelization significantly reduces execution overhead by processing agent interactions simultaneously.

---

# 🔥 Technologies Used

| Technology | Purpose |
|------------|----------|
| C++ | Core Simulation Logic |
| CUDA | GPU Parallel Computing |
| OpenGL | Graphics Rendering |
| Parallel Computing | Agent Computation |
| Data Visualization | Performance Analysis |
| GPU Programming | Optimization |

---

# 📈 Performance Results

## Simulation Capacity
- Supports 100 – 20,000 agents

## Performance Improvements
- 20x–40x higher throughput compared to CPU-only implementation
- Stable FPS during dense crowd simulations
- Significant reduction in execution time per frame

## Realistic Crowd Behaviors
- Bottleneck formation
- Lane formation
- Congestion patterns
- Density heatmapping

---

# 📉 Benchmark Analysis

The hybrid architecture demonstrates:

✅ Lower execution time  
✅ Better scalability  
✅ Higher FPS stability  
✅ Improved computational throughput  
✅ Real-time responsiveness  

Compared to traditional CPU-only implementations, the GPU-accelerated system maintains efficient processing even under extreme crowd density.

---

# 🖥️ Simulation Workflow

1. Initialize agents randomly
2. Assign exit targets
3. Compute neighboring agents
4. Apply Boids behavioral rules
5. Update velocities and positions
6. Render updated simulation
7. Repeat in real time
   
---

# 🎯 Applications

This project can be applied in:

- Smart city planning
- Emergency evacuation systems
- Crowd management
- Swarm robotics
- Pedestrian traffic analysis
- Intelligent transportation systems
- Disaster response simulations

---

# 🔮 Future Enhancements

- Multi-GPU acceleration
- AI-driven crowd prediction
- Reinforcement learning integration
- 3D simulation environments
- Dynamic obstacle avoidance
- Real-world map integration
- Cloud-based simulation scaling

---

# 🏆 Learning Outcomes

Through this project, we explored:

- GPU programming concepts
- CUDA parallel execution
- Hybrid CPU-GPU workload distribution
- Real-time simulation systems
- Performance optimization
- Scalable software architecture

---
