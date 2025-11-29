# 🚁 Autonomous Drone Racing: 3D Path Planning & Trajectory Optimization

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brahmbhatt-me/drone_racing_project/blob/main/drone_racing_trajectory_optimization.ipynb)
[![NBViewer](https://img.shields.io/badge/View%20with%20Plots-NBViewer-orange.svg)](https://nbviewer.org/github/brahmbhatt-me/drone_racing_project/blob/main/Drone_Project.ipynb)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)

An autonomous drone racing system using **RRT/RRT*** for path planning and **nonlinear trajectory optimization** to navigate through hoops while avoiding obstacles.

---

## 🎯 What It Does

| Input | Output |
|-------|--------|
| Start position, hoop locations, obstacles | Smooth, collision-free racing trajectory |

**Pipeline:** RRT Path Planning → Collision Checking → Physics-Based Dynamics → Trajectory Optimization

---

## 🔧 Key Implementations

- **RRT & RRT*** — 3D path planning with goal bias and rewiring
- **6-DOF Drone Dynamics** — Terminal velocity model with gravity and drag
- **Direct Transcription** — Trajectory optimization via SLSQP
- **Collision Avoidance** — Sphere and box obstacle handling

---

## 📊 Results

| Metric | RRT | Optimized |
|--------|-----|-----------|
| Path Length | ~45m | ~32m |
| Smoothness | Jerky | Smooth |
| Physics | Ignored | Enforced |

---
---

## 🎬 Visualizations

### RRT Tree Exploration
![RRT Tree](assets/rrt_tree.png)

### Racing Through Hoops
![Racing Path](assets/racing_path.png)

### RRT vs Optimized Trajectory
![Comparison](assets/comparison.png)

### Obstacle Avoidance
![Obstacles](assets/obstacle_course.png)

> 🎮 **For interactive 3D plots, [open in Colab](https://colab.research.google.com/github/brahmbhatt-me/drone_racing_project/blob/main/Drone_Project.ipynb)**

---
## 🛠️ Tech Stack

`Python` `GTSAM` `SciPy` `Plotly` `NumPy`

---

## 🚀 Quick Start

Click **Open in Colab** badge above — runs in browser, no setup needed.

---

## 📁 Structure
```
├── drone_racing_trajectory_optimization.ipynb  # Main notebook
├── helpers_obstacles.py                         # Utility functions
└── README.md
```

---

## 👤 Author

**Meet Brahmbhatt** — MS Robotics, Northeastern University
