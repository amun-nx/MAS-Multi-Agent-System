# 🔧 IN424 - Autonomous exploration using MASMATLAB-Projects

MAS (Multi-Agent System) project consisting of exploring an unknown space using 3 robots with LiDAR sensors using strategies and algorithms in ROS2. 
This project is a school given by our teachers in order to better understand MAS. The project was greatly setup by them, the main changes that we did was on the in424_nav file. We coded there the MAS logic but also the displacement of the robots, the path planning (A star) and other things. 
All of these information are reported in the pdf report in the file.

## 📚 Table of Contents

- [Built with](#-built-with)
- [Getting Started](#-getting-started)
- [Requirements](#requirements)
- [Contributors](#contributors)
- [License](#license)
- [Acknowledgments](#acknowledgments)


## 🧠 Built with 

- Language: Python 

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/amun-nx/MAS-Multi-Agent-System.git
```

### 2. Install the Dependencies 
```bash
cd ~/ros2_ws/src/IN424 && ./install_galactic.sh
cd ~/ros2_ws/src/IN424 && ./install_dependencies.sh && source ~/.bashrc
```
### 3. Run the project 
In one tab, run 
```bash
ros2 launch in424_simu start_world_launch.py
```
In another one run
```bash
ros2 launch in424_nav agents_launch.py
```

## 🛠Requirements
- ROS2

## 🤝Contributors
- Teachers :
  - Johvany Gustave
  - Jonatan Alvarez
- Classmates :
  - Quentin Constant
  - Raoul Johannes
  - Peyrard Lejeune Luc

## 📜License 
Distributed under the Apache License. See LICENSE.txt for more information.

## ✨Acknowledgments 
- School project 





