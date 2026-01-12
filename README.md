# Dual-Arm-Cartesian-Control
This repository contains the initial setup and partial implementation of a dual-arm robotic system in ROS 2 (Jazzy). The work includes dual-arm URDF integration, visualization in RViz, and controller scaffolding for Cartesian control. The task is currently in progress, with focus on system architecture, robot description, controller configuration
Objectives:-
-Set up a dual-arm robotic system in ROS 2
-Configure and visualize the system in RViz
-Design controller architecture for Cartesian motion control
-Prepare groundwork for coordinated dual-arm control
-Current Implementation Status

Completed:-
-Dual-arm URDF/XACRO integration
-Proper mounting and alignment of both arms on a shared base
-TF tree validation using robot_state_publisher
-RViz visualization of the complete dual-arm system
-Controller configuration scaffolding
In Progress:-
-Cartesian control implementation
-Coordinated dual-arm motion planning
-Trajectory execution refinement
-Stability and synchronization improvements
System Requirements:-Operating System
-Ubuntu 24.04
-ROS Version
-ROS 2 Jazzy
Languages & Tools
-Python 3
-C++
-ROS 2 Control
-RViz2
-XACRO / URDF

DEXSENT_TASK2_WS/
├── build/
├── install/
├── log/
└── src/
    ├── dual_arm_controller/
    │   ├── dual_arm_controller/
    │   │   ├── __init__.py
    │   │   └── dual_arm_cartesian_controller.py
    │   ├── resource/
    │   ├── test/
    │   ├── package.xml
    │   ├── setup.py
    │   └── setup.cfg
    │
    └── dual_arm_description/
        ├── config/
        ├── include/
        ├── launch/
        │   └── view_dual_arm.launch.py
        ├── meshes/
        │   └── visual/
        │       ├── base_link.dae
        │       ├── link_1.dae
        │       ├── link_2.dae
        │       ├── link_3.dae
        │       ├── link_4.dae
        │       ├── link_5.dae
        │       ├── link_6.dae
        │       └── link_7.dae
        ├── urdf/
        │   ├── fanuc_single_arm.urdf.xacro
        │   └── fanuc_dual_arm.urdf.xacro
        ├── CMakeLists.txt
        └── package.xml
