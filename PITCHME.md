
## Feedback ROSCON FR 2019

---

### Main Subjects

@snap[text-09 text-black text-left]
@ul[](false)
- ROS1 and ROS2
- ROS in the industry
- Simulators
- Features / Packages added by the community
- Projects presentations
@ulend
@snapend

---

### ROS1 and ROS2

@snap[text-05 text-black text-left span-100]
@ul[](false)
- Next ROS1 LTS in 2020 (support until 2025)
- Next LTS might support python 3
- Creation of a package indexation website
- New ROS2 distro avaiable since May (Dashing Diademata)
- ROS2 has been dev. to be safe and reliable @fa[arrow-right] industrial applications
@ulend
@snapend

---

### ROS2 main features

@snap[text-05 text-black text-left]
@ul[](false)
- No more rosmaster and param server
    + standalone nodes with broadcasting systems
    + ROS2 is a distributed system
- Deterministic execution
    + Control and monitoring of node status (configuration/active/inactive)
    + Realtime applications
- Quality of Service improvements
    + Topic Deadline (Data must arrive before it's too late)
    + Topic LifeSpan (Data obsolescence principle)
    + Node Liveliness
- No more nodelets (ROS2 nodes ~ nodelets)
- System security (hacking-proof)
    + concept of private nodes or group of nodes
    + crypted communications
    + ROS2 threat model and security testing tool (from Amazon)
- Support for small embedded systems (microROS)
- Code quality improvements
    + Validation/Verification/Certification tools (for industrial critical apps)
    + Sanitizer tool (from Amazon)
- Python support and CLI/GUI tools such as ROS1 (eg. rqt, rviz, ...)
- Actions nativly integrated with CLI tools (just like Services / Topics)
- Rosbag format different from ROS1 (but you can still read ROS1 rosbag with ROS2)
@ulend
@snapend

---

### ROS and the industry

@snap[text-05 text-black text-left]
**Why ?**

@ul[](false)
- In the past years many acquisitions of companies with ROS based product (eg. Erle, Here Maps, ...)
- Big tech companies are changing their point of view on Open Source
- ROS inherent to robotic development
@ulend
@snapend

@snap[text-05 text-black text-left]
**How ?**

@ul[](false)
- ROS Industrial (Fraunhofer Institut) : Push forward ROS for industries
- ROS for railways (SNCF) : Community for ROS applications in railways sector
- AWS Robomaker (Amazon) : Cloud extension for ROS Dev. / Simulation / Deployment
- ROS 2 Technical Steering Commitee include Amazon, Intel, Microsoft, Bosch, and many other big companies...
    + Help in the Dev. effort
    + Help to Establish Roadmap
    + Help to Establish Dev. Policies
    + All decisions on consensus (if not they vote)
@ulend
@snapend

---

### Simulators

@snap[text-05 text-black text-left]
**Gazebo improvements with ROS 2**

@ul[](false)
- No more killing/relaunch bug !
- New graphicals engines
    + 4 avaiables
    + Chosen at runtime
    + Common API for all engines
    + Allow to choose an only kinematic engine
- Gazebo-Ignition avaiable with ROS2
- Gazebo now decomposed in Ignition libs @fa[arrow-right] no need of Gazebo to use simulation tools
- New GUI tools / API / CLI
@ulend
@snapend

---

### Simulators

@snap[text-05 text-black text-left]
**Webots R2019a (Cyberbotics)**

@ul[](false)
- Private tool now open (since December 2018)
- Multi-plateform (Linux, Mac, Windows)
- Big library of free-to-use simulated robots / sensors / actuators / parts
- GUI editor for robot creation
- C, C++, Python, ROS, Java and Matlab API for component creation and interaction
- ROS compatible (ROS2 incoming)
- Simulation of urban environnment
- Powerfull graphical engine - really interesting for image processing in simulation
    + Optical distorsion / blur / reflect implemented
    + Optimized
@ulend
@snapend

@snap[south-east span-30]
![](https://upload.wikimedia.org/wikipedia/commons/8/82/Wbinterface.png)
@snapend

---

### Simulators

@snap[text-05 text-black text-left]
**QiBullet**
@snapend

@snap[text-05 text-black text-left]
@ul[](false)
- Intern tool of Softbank now released for the community
- Pepper / NAO simulator
- Python API with a ROS wrapper (close from Naoqi API)
- Does not use Naoqi OS to pilot the Pepper (Shame !)
- Not all the embedded sensors are simulated (Shame again !)
@ulend
@snapend

@snap[south-east span-35]
![](https://raw.githubusercontent.com/ProtolabSBRE/qibullet/master/ressources/short_top_cam.gif)
@snapend

---

### Features added by the community

@snap[text-05 text-black text-left]
@ul[](false)
- **ROS2RUST** Power of RUST language as an alternative to the C++ / Python for ROS nodes
- **PyROS** Get ROS inside python (ROS as a python lib). Can create ROS node without ros workspace / packages. Powerful for UI / Web applications.
- **rosmon** Node launcher with node monitoring and performance diagnostic
- **plotjuggler** Show topic data in real time. Allow online data processing (eg. derivation, filtering, ...).
- **librosqt** Allow to merge the ROS loop with the QT loop for GUI applications
- **libros2qt** Same as before but for ROS2
- **ROS tracing** ROS diagnostic tool that helps to understand the messages flow (eg. path of a message through nodes) and the nodes executions.
@ulend
@snapend

---

### Packages added by the community

@snap[text-05 text-black text-left]
@ul[](false)
- **dynamixel_control** Allow any-level of control on any type of Dynamixel actuator
- **ros_vector** Allow to control the Anki's Vector robot with ROS
@ulend
@snapend

---

### Projects presentations

@snap[text-05 text-black text-left]
@ul[](false)
- **AGIMUS framework**  ROS achitecture for futomatic motion planning for humanoid robots
- **Autoware.Auto** OpenSource ROS Stack for autonomous driving (will replace **Autoware.AI**)
- **R2P2** Railway maintenance robot developped by Generation Robots for SNCF
- **Konexinc** Creation of a ROS based robot to pilot / monitor a house
- **ROS_2_GUIX** GUIX for ros applications  (Gnu package manager eqv. virtual env) 
- **BOARR** Quadrotor collision avoidance algorithms benchmark based on Gazebo+ROS
- **Gaby + ROSIhmWeb** ROS Tool to remotly pilot and monitor a fleet of robots
- **UTBM robocar dataset** New long-term dataset purely based on ROS.
- **Pulsar** Prototype of an ultra large structure assembly robot simulated under Gazebo.  
@ulend
@snapend
