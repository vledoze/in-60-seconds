
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

@snap[text-05 text-black text-left]
@ul[](false)
- Next ROS1 LTS in 2020 (support until 2025)
- Creation of a package indexation website
- New ROS2 distro avaiable since May (Dashing Diademata)
- ROS2 has been dev. to be safe and reliable @fa[arrow-right] industrial applications
@ulend
@snapend

---

### ROS2 main features

@snap[text-05 text-black text-left]
@ul[](false)
- No more rosmaster (standalone node with broadcasting system : ROS2 is a distributed system)
- Deterministic execution (control on configuration/active/inactive status)
- No more nodelets (ROS2 nodes ~ nodelets)
- Realtime control
- System security (eg. private nodes, crypted communications, ...)
- Support for small embedded systems (microROS)
- Validation/Verification/Certification tools (for industrial critical apps)
- Python support and same CLI/GUI tools as ROS1 (eg. rqt, rviz, ...)
- Rosbag format different (but you can still read ROS1 rosbag with ROS2)
- Actions nativly integrated with CLI tools (just like Services / Topics)
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
- AWS Robomaker (Amazon) : Cloud extension for ROS Dev. / Simulation / Deploiement
- ROS 2 Technical Steering Commitee with Amazon, Intel, Microsoft, Bosch, and many other big companies... : Dev. effort / Roadmap / Dev. Policies
@ulend
@snapend

---

### Simulators

@snap[text-05 text-black text-left]
**Gazebo improvments with ROS 2**

@ul[](false)
- No more killing/relaunch bug !
- New graphicals engines
    + 4 avaiables
    + Chosen at runtime
    + Common API for all engines
    + Allow to choose an only kinematic engine
- Gazebo-Ignition avaiable with ROS2
- Gazebo now decomposed in Ignition libs : no need of Gazebo to use simulation tools
- New GUI tools / API / CLI
@ulend
@snapend

---

### Simulators

@snap[text-05 text-black text-left]
**Webots R2019a (Cyberbotics)**

@ul[](false)
- Private tool now open
- Multiplateform (Linux, Mac, Windows)
- Big library of free to use simulated robots / sensors / actuators / parts
- API for component creation
- Simulation of urban environnment
- Powerfull graphical engine - really interesting for image processing in simulation
- ROS compatible
@ulend
@snapend

---

### Simulators

@snap[text-05 text-black text-left]
**QiBullet**

@ul[](false)
- Intern tool of Softbank now released for the community
- Pepper / NAO simulator
- Python API with a ROS wrapper (close from Naoqi API)
- Does not use Naoqi OS to pilot the Pepper (Shame !)
- Not all the embedded sensors are simulated (Shame again !)
@ulend
@snapend

---

### Features added by the community

- **ROS2RUST** Power of RUST language as an alternative to the C++ / Python.
- **PyROS** Get ROS inside python (ROS as a python lib). Can create ROS node without ros workspace / packages. Powerful for UI / Web applications.
- **rosmon** Node launcher with node monitoring and performance diagnostic
- **plotjuggler** Show topic data in real time. Allow the calculus capacity directly from data (eg. derivation, filtering, ...).
- **librosqt** Allow to merge the ROS loop with the QT loop for GUI applications
- **libros2qt** Same as before but for ROS2
- **ROS tracing** ROS diagnostic tool that helps to understand the messages flow (eg. path of a message through nodes) and the nodes executions.

---

### Packages added by the community

- **dynamixel_control** Allow any-level of control on any type of Dynamixel actuator
- **ros_vector** Allow to control the Anki's Vector robot with ROS

---

### Projects presentations

- **AGIMUS framework**  ROS achitecture for futomatic motion planning for humanoid robots
- **Autoware.Auto** OpenSource ROS Stack for autonomous driving (will replace **Autoware.AI**)
- **R2P2** Railway maintenance robot developped by Generation Robots for SNCF
- **Konexinc** Creation of a ROS based robot to pilot / monitor a house
- **ROS_2_GUIX** GUIX (Gnu package manager eqv. virtual env) for ros applications  
- **BOARR** Quadrotor collision avoidance algorithms benchmark based on Gazebo+ROS
- **Gaby + ROSIhmWeb** ROS Tool to remotly pilot and monitor a fleet of robots
- **UTBM robocar dataset** New long-term dataset purely based on ROS.
- **Pulsar** Prototype of an ultra large structure assembly robot simulated under Gazebo.  

---

# Titre1
## Titre2
### Titre3
#### Titre4
##### Titre5
###### Titre6

---

@css[text-25 text-black](text-25)

@css[text-20 text-black](text-20)

@css[text-17 text-black](text-17)

@css[text-15 text-black](text-15)

@css[text-12 text-black](text-12)

@css[text-10 text-black](text-10)

@css[text-07 text-black](text-7)

@css[text-05 text-black](text-5)
