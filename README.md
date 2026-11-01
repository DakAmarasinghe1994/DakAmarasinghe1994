# Dakshitha (Dak) Amarasinghe
### Robotics, Mechatronics & Automation Engineer

I develop integrated robotic systems that connect sensing, intelligent perception, motion planning, and physical robot control.

My experience spans AI-enabled robotic workcells, autonomous mobile robots, collaborative manipulators, industrial automation, and marine robotics. I combine software development with hands-on hardware integration, system testing, and troubleshooting.

With an **MS in Robotics and Automation from Santa Clara University** and a **BS in Mechanical Engineering, majoring in Robotics and Mechatronics, from Virginia Tech**, I bring a multidisciplinary perspective to robotics development—connecting mechanical systems, electronics, embedded controllers, and intelligent software.

My technical work includes **Python, C/C++, Linux, and ROS 2**, with applications in **YOLOv8 object detection, stereo-camera perception, object tracking, robotic manipulation, inverse kinematics, sensor fusion, localization, SLAM, and motion planning**. I develop interfaces that connect sensors and control hardware with modular robotics software, supporting both physical robot operation and virtual-model visualization.

I approach engineering challenges through technical analysis, system modelling, systematic testing, and root cause investigation. My focus is on improving robot behavior, reliability, and operational efficiency through careful integration, validation, and iterative refinement.

## Education

- MS in Robotics and Automation — Santa Clara University, USA
- BS in Mechanical Engineering, major in Robotics and Mechatronics —
  Virginia Tech, USA

## Engineering Experience

### Robotics Research and Development Visiting Scholar — Santa Clara University, Robotic Systems Lab

Developed mobile-robot localization and mapping software, ROS 2 robot-control interfaces, and embedded communication systems. Also contributed to AGV troubleshooting, marine robotic system integration, and ROV operation training.

- **Encoderless localization and SLAM:** Developed a Raspberry Pi 5-based ROS 2 Jazzy stack integrating YDLIDAR TG30, RF2O laser odometry, BNO055 IMU measurements, robot_localization/EKF, and SLAM Toolbox. Built an Arduino-to-ROS 2 serial interface, configured sensor fusion and covariance settings, and integrated master launch, RViz, and SSH-based operation. The implementation supports occupancy-grid mapping without wheel encoders and provides a foundation for future wheel-encoder fusion and Nav2 navigation.

- **Collaborative robot control:** Developed modular ROS 2 subsystems for independently controlling a myCobot 280 Pi and its virtual model through joint-space and Cartesian commands. Integrated a pre-existing GUI using dedicated interfaces and launch configurations, developed script-based command publishers, and implemented a MoveIt 2 inverse-kinematics client for virtual-model control and RViz visualization.

- **Hardware-platform migration and communication:** Upgraded the myCobot’s onboard computer from Raspberry Pi 4B to Raspberry Pi 5, then established external PC control through CH340 USB-to-TTL communication. Subsequently migrated control to an NVIDIA Jetson Orin Nano and implemented an Arduino Uno UART bridge to resolve converter compatibility issues.

- **Manipulator motion sequencing:** Developed a ROS 2 publisher-subscriber package for a Rotrics DexArm, coordinating Cartesian motion and pneumatic-gripper commands through serial/G-code communication. Implemented reversible pick-and-place sequences with command-completion acknowledgments to serialize robot movements and pneumatic actions.

- **Stereo perception and planning research:** Integrated a ZED 2i camera with a Jetson Orin Nano for 3D point-cloud generation and visual-inertial SLAM support. Evaluated baseline A* and RRT planning and explored heuristic costs and bidirectional tree growth as potential improvements for future integration.

- **Mobile and marine robotics:** Diagnosed Pioneer AGV motor-controller PWM and RC-channel issues using RoboteQ, Pixhawk 6C, Roborun+, and QGroundControl. Updated marine vertical-profiler wiring documentation, checked power distribution and embedded-software I/O assignments, supported mechanical assembly and leak testing, and assisted students with ROV inspection, deployment, underwater operation, and recovery.

### Mechatronics Implementation Engineer — Pepper Equipment Corporation

Programmed and tested AI-to-KUKA robot interfaces, coordinated robot and conveyor operation, and installed and tested pneumatic and mechanical systems for an agricultural robotics R&D workcell.

- Developed and tested **KUKA Robot Language (KRL)** interface code and robot motion sequences supporting potato grading and handling.
- Wired, configured, and programmed **automatic external operation using four switches**, with emergency-stop and operator-safety switch interfaces.
- Installed and tested electro-pneumatic controls and associated mechanical systems, troubleshooting interactions between robot motion, gripping equipment, and conveyor operation.
- Completed **Robot Programming 1 and Robot Programming 2 training at KUKA College, Michigan, USA**.
- Performed additional company fabrication assignments using MIG welding, grinding, drilling, and shop equipment; these assignments were separate from the robot-workcell project.

### Intern Engineer — Virginia Tech

Developed wireless EV-charging specifications and LTspice simulations to investigate power transfer and efficiency.

- Contributed remotely to specifications involving **inductive coupling, wireless power transmission, and signal-processing considerations**.
- Created **LTspice simulations of tuned transmitter and receiver coils** to analyze power-transfer and efficiency behavior at the required frequencies.

## Featured Projects

### [AI-Enabled Multi-Task Robot Work-Cell](https://github.com/DakAmarasinghe1994/ai-enabled-multi-task-robot-workcell)
Integrated YOLOv8 object detection, ZED stereo vision, and DexArm control
for conveyor-based tool picking. Developed perception and handling workflows
including object characterization, coordinate transformations, grasp
verification, and retry logic.

### [Encoderless AGV Localization and SLAM](https://github.com/DakAmarasinghe1994/encoderless-agv-localization-slam)
Developed a Raspberry Pi 5-based ROS 2 stack combining RF2O LiDAR odometry,
BNO055 IMU data, EKF sensor fusion, and SLAM Toolbox for occupancy-grid
mapping without wheel encoders. Provides a foundation for future
wheel-encoder fusion and autonomous navigation using Nav2.

### [KUKA Industrial Automation](https://github.com/DakAmarasinghe1994/kuka-industrial-automation)
Programmed and tested AI-to-robot interface code for a KUKA Delta robot
R&D workcell, including robot/conveyor coordination, automatic external
operation, and electro-pneumatic integration.

### [MyCobot280Pi Control System](https://github.com/DakAmarasinghe1994/mycobot280pi-control-system)
Developed modular ROS 2 interfaces for physical and virtual robot control
in joint and Cartesian space. Integrated an existing controller GUI,
implemented MoveIt 2 inverse-kinematics requests for virtual-model control,
and adapted UART communication across PC and Jetson platforms.

### [Path Planning Algorithms for an Autonomous Vehicle](https://github.com/DakAmarasinghe1994/autonomous-vehicle-path-planning)
Developed MATLAB simulations using RRT and A* to investigate planning
around static and dynamic obstacles, including probabilistic
route-confidence updates and route visualization.

## Technical Skills

- **Programming:** Python, C/C++, MATLAB
- **Robotics:** ROS 2, MoveIt 2, TF2, URDF/Xacro, RViz
- **Perception:** YOLOv8, OpenCV, stereo vision, point clouds
- **Localization and Mapping:** RF2O, EKF, robot_localization, SLAM Toolbox
- **Hardware:** Raspberry Pi, NVIDIA Jetson, Arduino, UART, sensor integration
- **Engineering Tools:** Linux, Simulink, LTspice, SOLIDWORKS

## Training and Certifications

- Robot Programming 1 — KUKA College, Michigan, USA
- Robot Programming 2 — KUKA College, Michigan, USA
- Computer Programming — NIBM, Sri Lanka

## Career Interests

Robotics Engineering • Robotics Software • Robotics Systems Integration • Robotics Applications • AI-Enabled Robotics • Mechatronics • Automation

## Contact

- **Location:** Gampaha, Western Province, Sri Lanka
- **Email:** [dakshithaama1994@gmail.com](mailto:dakshithaama1994@gmail.com)
- **LinkedIn:** [Dak Amarasinghe](https://www.linkedin.com/in/dak-amarasinghe-946aa71b1/)
