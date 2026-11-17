# Hi, I'm Dr. Abdul Manan Khan 👋

**Lecturer (Assistant Professor) in Electronics and Robotics, University of West London** · formerly **Research Associate in Trustworthy AI for Autonomous Systems, [Imperial College London](https://www.imperial.ac.uk/design-engineering/)** · Senior Research Associate, **Bristol Robotics Laboratory**

I build robots and drones that are safe, explainable and work in the real world, combining control engineering with reinforcement learning.

🌐 **Website:** [abdul-mannan-khan.github.io/abdul-mannan-khan](https://abdul-mannan-khan.github.io/abdul-mannan-khan/) &nbsp;·&nbsp;
🎓 [Google Scholar](https://scholar.google.com/citations?user=akoaYEEAAAAJ&hl=en) &nbsp;·&nbsp;
💼 [LinkedIn](https://www.linkedin.com/in/abdul-manan-khan-711893a1/) &nbsp;·&nbsp;
🎬 [YouTube](https://www.youtube.com/@DreamRobotics/videos)

## Research

- **Trustworthy & explainable AI:** safe and explainable reinforcement learning, causal learning, XAI-guided optimisation for 6G drone networks
- **Drones & multi-robot systems:** flight control, RL-tuned model predictive control, sensor fusion, sim-to-real transfer with PX4 and ROS 2
- **Soft & rehabilitation robotics:** shape memory alloy actuators, dexterous robotic hands, exoskeletons, adaptive neural-network control

58 publications · 39 journal articles · 780+ citations · h-index 16 · IEEE Senior Member · Fellow of the Higher Education Academy

## Featured: warehouse robot simulation in NVIDIA Isaac Sim

[![Warehouse picking shift replayed in NVIDIA Isaac Sim](https://github.com/abdul-mannan-khan/warehouse-sim-rl/raw/main/media/demo_isaac.gif)](https://github.com/abdul-mannan-khan/warehouse-sim-rl/blob/main/media/demo_isaac.mp4)

A simulated warehouse shift with no people in it: mobile robots that pick parcels off the shelves with their own two UR5e arms, and UR5e arms at the packing tables, dispatched by a learned policy (masked PPO) and replayed in NVIDIA Isaac Sim. The discrete-event model is built in SimPy and calibrated with Optuna. **[Watch the full 60-second video](https://github.com/abdul-mannan-khan/warehouse-sim-rl/blob/main/media/demo_isaac.mp4)** · [Code: warehouse-sim-rl](https://github.com/abdul-mannan-khan/warehouse-sim-rl)

## Featured: farm digital twin in NVIDIA Isaac Sim

[![Farm digital twin with a weeding rover, a survey drone and a scouting robot in NVIDIA Isaac Sim](https://github.com/abdul-mannan-khan/farm-digital-twin/raw/main/media/farm_twin.gif)](https://github.com/abdul-mannan-khan/farm-digital-twin/blob/main/media/farm_twin.mp4)

A farm field built from scratch in NVIDIA Isaac Sim: about 30,000 procedurally modelled lettuce and maize plants on shaped soil under a real farm HDRI sky. A UR5e on a Clearpath Ridgeback pulls weeds into its bin, a Holybro X500 drone flies a survey and streams synthetic training data (RGB, depth, semantic segmentation, weed boxes), and a Clearpath Jackal scouts the maize. Runs in a Docker container (`docker run --gpus all farm-twin render`). **[Watch the full 60-second video](https://github.com/abdul-mannan-khan/farm-digital-twin/blob/main/media/farm_twin.mp4)** · [Code and Docker setup: farm-digital-twin](https://github.com/abdul-mannan-khan/farm-digital-twin)

## Selected repositories

| Repository | What it is |
|---|---|
| [farm-digital-twin](https://github.com/abdul-mannan-khan/farm-digital-twin) | Farm digital twin in NVIDIA Isaac Sim: procedural crops, UR5e weeding rover, X500 survey drone with synthetic data, Docker container |
| [warehouse-sim-rl](https://github.com/abdul-mannan-khan/warehouse-sim-rl) | Warehouse picking simulator: SimPy discrete-event model, Gymnasium environment, PPO dispatch policy, Optuna calibration and an NVIDIA Isaac Sim replay |
| [rl-tuned-mpc-drones](https://github.com/abdul-mannan-khan/rl-tuned-mpc-drones) | Reinforcement-learning-enhanced model predictive control for multi-drone systems |
| [wind-aware-delivery](https://github.com/abdul-mannan-khan/wind-aware-delivery) | Wind-aware route, altitude and speed planning for quadrotor parcel delivery in cities, with PX4 hardware-in-the-loop |
| [quadrotor-wind-corridors](https://github.com/abdul-mannan-khan/quadrotor-wind-corridors) | Quadrotor package delivery through urban wind corridors: 6-DOF simulator and wind-aware planner |
| [control-for-robots](https://github.com/abdul-mannan-khan/control-for-robots) | M.Sc.-level course on advanced control for robots: MPC, adaptive, robust, backstepping and sliding mode control |
| [TC70045E-robotics-sim](https://github.com/abdul-mannan-khan/TC70045E-robotics-sim) | 12-week ROS 2 robotics simulation course: Gazebo, RViz, CARLA, AirSim and PX4 in containers |

## Project videos

| | |
|---|---|
| [Safe reinforcement learning control for a drone in human presence](https://www.youtube.com/watch?v=jM0R4A10_9k) | [Soft robotic hand with shape memory alloy actuators](https://www.youtube.com/watch?v=n3poAvv3e0M) |
| [Crazyflie motion planning and control](https://www.youtube.com/shorts/pxFtXxIMWUI) | [UR5 industrial robot with ROS](https://www.youtube.com/watch?v=hx4_EYdZYxo) |
| [Drone flying in a scaled urban environment](https://www.youtube.com/shorts/4ffRYZYpAkc) | [ROS delivery robot with depth camera and lidar](https://www.youtube.com/watch?v=82VEt2ZYzfA) |

More on the [Videos page](https://abdul-mannan-khan.github.io/abdul-mannan-khan/#videos) of my website.

## Tools

Python · PyTorch · MATLAB/Simulink · C/C++ · ROS/ROS 2 · PX4 · Gazebo · AirSim · NVIDIA Jetson · Docker

---

*This repository also hosts my personal website ([index.html](index.html)), published with GitHub Pages.*
