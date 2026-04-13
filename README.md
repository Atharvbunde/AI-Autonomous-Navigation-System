# 🚀 AI-Based Autonomous Navigation System

## 📌 Overview

This project simulates an **AI-based autonomous navigation system** where a virtual robot navigates from a start point to a goal while intelligently avoiding obstacles using the **A* (A-Star) path planning algorithm**.

It demonstrates the core concepts used in **self-driving cars, warehouse robots, and delivery systems**.

---

## 🎯 Problem Statement

Autonomous systems must navigate safely in complex environments without human intervention.  
This project showcases how AI can:

* Plan optimal paths  
* Avoid obstacles  
* Simulate intelligent navigation  

---

## 🧠 Key Features

* 🎮 Interactive 2D simulation using Pygame  
* 🧠 A* path planning algorithm  
* 🚧 Obstacle avoidance system  
* 🔄 Dynamic path recalculation  
* 🤖 Real-time robot movement  
* 🧱 Maze-based environment  

---

## 🛠 Tech Stack

* Python  
* Pygame  
* NumPy  
* OpenCV *(for future upgrades)*  

---

## 🏗 System Architecture
Input → Grid Environment → A* Algorithm → Path Planning → Robot Movement → Visualization
---

## 📁 Folder Structure
AIAI-Autonomous-Navigation-System/
│
├── data/                      # Dataset or map data (if used)
├── docs/                      # Documentation (reports, diagrams)
├── images/                    # Screenshots for README
│   ├── FinalOutput1.png
│   ├── FinalOutput2.png
│   └── terminal.png
│
├── outputs/                   # Generated results
│   ├── images/
│   └── videos/
│       └── maze_run.mp4
│
├── simulation/                # Main simulation code
│   └── grid_world.py
│
├── src/                       # Core algorithms
│   └── a_star.py
│
├── .gitignore
├── README.md
├── requirements.txt
└── main.py
---

## ⚙️ Installation
'''bash
# Create virtual environment
python -m venv venv

# Activate (Windows)
venv\Scripts\activate

# Install dependencies
pip install pygame numpy

# Save dependencies
pip freeze > requirements.txt

'''bash
python simulation/grid_world.py



## 🎮 Controls *(if implemented)*

| Action              | Control      |
| ------------------- | ------------ |
| Set Start           | Left Click   |
| Set Goal            | Right Click  |
| Add/Remove Obstacle | Middle Click |

---

## 📸 Results

* ✅ Intelligent path planning
* ✅ Maze navigation
* ✅ Real-time simulation

---

## 📸 Screenshots

### 🧠 Simulation Output

![Simulation](images/FinalOutput1.png)
![Simulation](images/FinalOutput2.png)

### 💻 Terminal Output

![Terminal](images/terminal.png)

---

📌 Add video here:
videos/maze_run.mp4

---

## 🚀 Future Improvements

* 🔍 Real-time object detection (YOLO)
* 🤖 ROS integration
* 🚗 CARLA simulator
* 🧠 Reinforcement learning navigation
* 👥 Multi-agent system
* 📡 IoT-based real robot implementation

---

## 📚 Learning Outcomes

* Path planning algorithms (A*)
* Simulation design using Pygame
* AI-based decision making
* Real-world robotics concepts

---

## 👨‍💻 Author

**Atharv Bunde**
🎓 Diploma in Mechatronics Engineering (DBATU)

🔗 LinkedIn:
[https://www.linkedin.com/in/atharv-bunde-602361400/](https://www.linkedin.com/in/atharv-bunde-602361400/)

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it!

````

