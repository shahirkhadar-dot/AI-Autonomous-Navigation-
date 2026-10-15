# AI-Autonomous-Navigation-
# AI-Based Autonomous Navigation System

An industry-oriented virtual simulation demonstrating perception, path planning, and dynamic obstacle avoidance for self-driving vehicles and autonomous mobile robots (AMRs).

![Simulation Preview](simulation_output.png)

## 📌 Overview
Autonomous navigation requires a vehicle to process spatial data, generate optimal trajectories, and dynamically react to unexpected obstacles in real time. This project implements a complete autonomous pipeline utilizing the **A* (A-Star) search heuristic**, simulated occupancy grids, and real-time sensory re-planning.

## 🚀 Key Features
- **Deterministic Path Planning:** Computes mathematically optimal collision-free trajectories across 8-directional motion primitives.
- **Dynamic Obstacle Avoidance:** Simulates on-board proximity detection and triggers sub-second path recalculation.
- **Sensor Telemetry Visualization:** Plots static obstacles, dynamically identified hazards, original plans, and final executed tracks.
- **Lightweight Architecture:** Engineered to execute cleanly on resource-constrained platforms, embedded systems, and mobile environments.

## 🛠️ Tech Stack
- **Language:** Python 3
- **Data Structures & Algorithms:** A* Search Algorithm, Min-Heap Priority Queues
- **Libraries:** NumPy (Grid Matrix Operations), Matplotlib (Telemetry & Trajectory Rendering)

## 📂 System Architecture
1. **Sensory Map (Grid environment):** Discretizes real-world space into traversable vs blocked cells.
2. **Perception Engine:** Detects sudden obstacles and flags unpassable coordinates.
3. **Planner (A star planner):** Uses Euclid mean heuristics ($f = g + h$) to minimize travel distance.
4. **Navigator (Autonomous navigator):** Manages real-time waypoint progression and exception handling.

## ⚙️ Installation & Usage
### 1. Clone the repository
```bash
git clone [https://github.com/shahirkhadar-dot/AI-Autonomous-Navigation-System.git](https://github.com/shahirkhadar-dot/AI-Autonomous-Navigation-System.git)
cd AI-Autonomous-Navigation-System
Screenshot_20261015_185226.jpg
