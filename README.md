
Robotics & AI Researcher | Control Systems Enthusiast

Department of Mechanical and Civil Engineer, Florida Institute of Technology

Lab: [IPCL](https://sites.google.com/view/fit-ipcl/home)

Email: phat.xuan.truong@gmail.com • [GitHub](https://github.com/phat-truongxuan) • [LinkedIn](https://www.linkedin.com/in/xuan-phat-truong-2545001a0/)

---
# Publications

**Truong, X. P., & Hong, S. H. (2026). Safe Rocket Landing Using Lyapunov-Based Reinforcement Learning. In AIAA SCITECH 2026 Forum (p. 1588).**
[ DOI](https://arc.aiaa.org/doi/abs/10.2514/6.2026-1588)

**Truong, X. P., & Hong, S. H. (2024). Rough Terrain Path Planning for Autonomous Ground Robot. In AIAA SCITECH 2024 Forum (p. 2764).**
[ DOI](https://doi.org/10.2514/6.2024-2764)

**Truong, X. P., Jeon, H., Wang, Y., & Hong, S. H. (2025). Monitoring energy consumption for cyberattack detection in additive manufacturing systems. The International Journal of Advanced Manufacturing Technology, 1-17.**
[ DOI](https://doi.org/10.1007/s00170-025-16551-2)

---
# Research Project

**Stable Reinforcement Learning Control for Satellites with Learned Dynamics. Space Force (Air Force). PI: Seong Hyeon Hong**

---

# Work Experience

**Robotics Software Engineer, Techtile / Goldbell Co., 2022**

**Robotics Software Engineer, NextAMR / FPT Software, 2021 - 2022**
    
**Robotics Software Engineer, Emage Development, 2022 - 2021**

---
# Projects

## Lyapunov control for Reinforcement Learning Policy

**a. Vertical rocket landing**

| Vanilla PPO | Lyapunov PPO |
|:------:|:------:|
| ![](images/landing_PPO.gif) | ![](images/landing_LPO.gif) |

---

**a. Quadrotor path tracking**

| Vanilla PPO | Lyapunov PPO |
|:------:|:------:|
| ![](images/ppo_new.gif) | ![](images/lpo_new.gif) |

---

## Rough Terrain Path Planning for Autonomous Ground Robot

**The system is setup on ROS and ROS2, planner map displayed on RViz, simulation built on Gazebo. The robot uses differential drive (4 wheeled drive) and tracks the planned path using PID controller**

**a. Without terrain planner**


| Planned Path | Path Tracking |
|:------:|:------:|
| ![](images/without_terrainplanner.png) | ![](images/without_terrainplanner.gif) |

**b. With terrain planner**

| Planned Path | Path Tracking |
|:------:|:------:|
| ![](images/with_terrainplanner.png) | ![](images/with_terrainplanner.gif) |

---

## Neural Network tuning using Genetic Algorithm

**This project uses PyGame as an environment. The goal is to tune a Neural Network (NN) weights using Genetic Algorithm (GA) so the car can adapt and cross the finish line. The input of the NN is the LiDAR distance values, and the output is the steering action. A generation is recreated with the best candidates after each episode termination and mutates to search for the best policy.**

![GA Demo](images/ga_race_demo.gif)

---

## Nav2 demo with Gazebo

![Demo](images/nav2_demo.gif)

[Video](https://www.youtube.com/watch?v=vf5PCvhSXe0)

---

## Moveit demo with Gazebo

![Demo](images/moveit_demo.gif)

[Video](https://www.youtube.com/watch?v=X2w5IWsK_So&t=62s)

---

## AStar Path Planning with Multiple Agent (time scheduling) (with Python)

| Plan Path | Execute Path |
|:------:|:------:|
| ![](images/astar_multi_plan.gif) | ![](images/astar_multi_exe.gif) |

[Code](https://github.com/phat-truongxuan/path_algo.git)

## Cubic Spline Interpolation (with C++)

![Demo](images/cubic_spline_result.png)

[Code](https://github.com/phat-truongxuan/path_algo.git)

---

## Delta Robot fully built and controlled

![Demo](images/delta_robot.gif)

[Video](https://www.youtube.com/watch?v=rsFehdk5Mqs)
