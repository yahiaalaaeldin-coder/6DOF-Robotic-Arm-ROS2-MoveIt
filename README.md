# 6-DOF Robotic Arm | ROS 2, RViz2 & MoveIt 2

### Mechanical Design & Robotics Simulation Project

A six-degree-of-freedom (6-DOF) robotic arm modeled in SolidWorks and integrated into ROS 2 for robot visualization, kinematic analysis, and motion-planning development.

The project combines mechanical CAD, robot description using URDF, ROS 2 integration, RViz2 visualization, and MoveIt 2 motion planning.

**Project Status:** Simulation and motion-planning development
**Hardware:** Not yet implemented

---

## 📌 Project Overview

The objective of this project is to develop a 6-DOF robotic arm model and integrate it into a ROS 2 simulation environment.

The robotic arm is designed in SolidWorks, converted into a URDF robot description, and visualized in RViz2. MoveIt 2 is used to configure the robot's planning environment and explore inverse kinematics and motion planning.

The project provides practical experience in robotic system modeling, kinematic configuration, and ROS 2-based simulation.

---

## 🎯 Project Objectives

* Develop a 6-DOF robotic arm mechanical model using SolidWorks.
* Convert the CAD model into a ROS-compatible URDF description.
* Integrate the robot into ROS 2 Jazzy.
* Visualize the robot model and joint configurations in RViz2.
* Configure MoveIt 2 for motion planning and inverse kinematics.

---

## ⚙️ System Architecture

The project workflow consists of the following stages:

1. **Mechanical Design:** Create the robotic arm assembly in SolidWorks.
2. **Robot Description:** Define links, joints, and kinematic relationships using URDF.
3. **ROS 2 Integration:** Load the robot description into the ROS 2 environment.
4. **Visualization:** Display the robotic arm in RViz2.
5. **Motion Planning:** Configure MoveIt 2 for inverse kinematics and trajectory planning.

---

## 🔩 Mechanical Design — SolidWorks

The robotic arm was modeled as a six-degree-of-freedom articulated manipulator.

### Design Features

* 6 rotational degrees of freedom
* Multi-link robotic structure
* CAD-based mechanical assembly
* Joint-based articulated motion
* Mechanical model prepared for ROS 2 integration

The SolidWorks model serves as the foundation for the robot's URDF description and simulation environment.

**CAD Software:** SolidWorks

*SolidWorks assembly screenshots and renders will be added to the project gallery.*

---

## 🤖 Robot Description — URDF

The robot's mechanical structure is represented in URDF (Unified Robot Description Format) for integration with ROS 2.

### Implementation

* Defined robot links and joints.
* Configured the robot's kinematic structure.
* Generated the robot description from the SolidWorks model.
* Integrated the URDF into the ROS 2 description package.
* Prepared the robot model for visualization and motion planning.

**Technologies:** `URDF` `ROS 2` `SolidWorks`

---

## 🖥️ ROS 2 & RViz2 Integration

The robotic arm was integrated into a ROS 2 Jazzy environment and visualized using RViz2.

### Features

* Robot model visualization
* Joint configuration display
* Robot description integration
* Simulation environment setup
* Visualization of the articulated 6-DOF structure

**Software:** `ROS 2 Jazzy` `RViz2` `Ubuntu 24.04`

---

## 🧭 MoveIt 2 — Motion Planning

MoveIt 2 was introduced to configure the robotic arm for kinematic analysis and motion planning.

### Implemented Work

* MoveIt configuration package setup
* Robot planning group configuration
* Forward kinematics workflow
* Inverse kinematics configuration
* Motion-planning environment setup
* Planning and execution workflow testing

The project explores how MoveIt 2 can generate robot motion plans based on target configurations.

**Current Development:** Motion-planning and controller integration are being refined.

---

## 💻 Software & Tools

| Category                | Tools        |
| ----------------------- | ------------ |
| Mechanical CAD          | SolidWorks   |
| Robot Description       | URDF, Xacro  |
| Robotics Middleware     | ROS 2 Jazzy  |
| Visualization           | RViz2        |
| Motion Planning         | MoveIt 2     |
| Operating System        | Ubuntu 24.04 |
| Development Environment | VirtualBox   |

---

## 📊 Project Development Status

| Project Phase                          | Status              |
| -------------------------------------- | ------------------- |
| SolidWorks Mechanical Model            | Completed           |
| URDF Robot Description                 | Completed           |
| ROS 2 Integration                      | Completed           |
| RViz2 Visualization                    | Completed           |
| MoveIt 2 Configuration                 | Implemented         |
| Inverse Kinematics                     | In Progress         |
| Motion Planning & Execution Refinement | In Progress         |
| Physical Hardware Implementation       | Not Yet Implemented |

---

## 🖼️ Project Gallery

Screenshots and visual documentation will be added as the repository is developed.

| SolidWorks CAD Model | RViz2 Visualization    |
| -------------------- | ---------------------- |
| *Add CAD screenshot* | *Add RViz2 screenshot* |

| MoveIt 2 Planning Environment |
| ----------------------------- |
| *Add MoveIt 2 screenshot*     |

**Project Demonstration:** *Add video link here*

---

## 📁 Repository Structure

```text
6DOF-Robotic-Arm-ROS2-MoveIt/
│
├── README.md
│
├── Images/
│   ├── SolidWorks/
│   ├── RViz2/
│   └── MoveIt/
│
├── robotic_arm_description/
│   ├── urdf/
│   ├── meshes/
│   └── launch/
│
├── robotic_arm_moveit_config/
│   ├── config/
│   └── launch/
│
└── Documentation/
```

*The repository structure will be updated to match the actual uploaded project files.*

---

## 🧠 Engineering Skills Demonstrated

* Mechanical CAD modeling
* Robotic system design
* URDF robot description
* ROS 2 integration
* Robot visualization
* Forward and inverse kinematics
* Motion-planning configuration
* Simulation and debugging
* Mechanical and software system integration

---

## 🎓 Project Information

**Project:** 6-DOF Robotic Arm — ROS 2 & MoveIt 2
**Discipline:** Mechatronics Engineering
**Project Type:** Robotics Design & Simulation
**ROS 2 Distribution:** Jazzy
**Collaboration:** Developed collaboratively

---

*This project is a simulation-based robotics development project. Physical robot fabrication and hardware-level validation have not yet been completed.*
