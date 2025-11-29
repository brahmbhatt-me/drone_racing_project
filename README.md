# 🚁 Autonomous Drone Racing: 3D Path Planning & Trajectory Optimization

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/brahmbhatt-me/drone_racing_project/blob/main/Drone_Project.ipynb)
[![View Notebook](https://img.shields.io/badge/View%20Notebook-NBViewer-orange.svg)](https://nbviewer.org/github/brahmbhatt-me/drone_racing_project/blob/main/Drone_Project.ipynb?flush_cache=true)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![GTSAM](https://img.shields.io/badge/GTSAM-4.2-green.svg)](https://gtsam.org)

> 🎮 **Click NBViewer badge to see interactive 3D visualizations without running code**

An autonomous drone racing system using **RRT/RRT*** for path planning and **nonlinear trajectory optimization** to navigate through hoops while avoiding obstacles.

---

## 🎯 What It Does

| Input | Output |
|-------|--------|
| Start position, hoop locations, obstacles | Smooth, collision-free racing trajectory |

**Pipeline:** `RRT Path Planning` → `Collision Checking` → `Physics-Based Dynamics` → `Trajectory Optimization`

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

## 🛠️ Tech Stack

`Python` `GTSAM` `SciPy` `Plotly` `NumPy`

---

## 🚀 Quick Start

**Option 1:** Click **NBViewer** badge — view all visualizations instantly

**Option 2:** Click **Colab** badge → Runtime → Run all — full interactive experience

---

## 👤 Author

**Meet Brahmbhatt** — MS Robotics, Northeastern University
```
