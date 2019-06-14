
@snap[west span-100]

# Feedback ROSCON FR 2019

@snapend

---

### Main Subjects

@ul[](false)
- ROS1 and ROS2
- ROS in the industry
- Simulators
- Features / Packages added by the community
- Projects presentations
@ulend

---

### ROS1 and ROS2

@ul[](false)
- Next ROS1 LTS in 2020 (support until 2025)
- Creation of a package indexation website
- New ROS2 distro avaiable since May (Dashing Diademata)
- ROS2 has been dev. to be safe and reliable @fa[arrow-right] industrial applications
@ulend

---

### ROS2 main features

@snap[text-05 text-black]
@ul[](false)
- No more rosmaster (standalone node with broadcasting system)
- Deterministic execution (control on configuration/active/inactive status)
- No more nodelets (ROS2 nodes ~ nodelets)
- Realtime control
- System security (eg. private nodes, crypted communications, ...)
- Support for small embedded systems (microROS)
- Validation/Verification/Certification tools (for industrial critical apps)
- Python support and same CLI/GUI tools as ROS1 (eg. rqt, rviz, ...)
- Rosbag format different (but you can still read ROS1 rosbag with ROS2)
@ulend
@snapend

---

### ROS and the industry

@snap[text-05 text-black]
**Why ?**

@ul[](false)
- In the past years many acquisitions of companies with ROS based product (eg. Erle, Here Maps, ...)
- Big tech companies are changing their point of view on Open Source
- ROS inherent to robotic development
@ulend
@snapend

@snap[text-05 text-black]
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

@snap[text-05 text-black]
**Gazebo improvments**

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

@css[text-11 text-black](text-11)

@css[text-10 text-black](text-10)

@css[text-09 text-black](text-9)

@css[text-08 text-black](text-8)

@css[text-07 text-black](text-7)

@css[text-06 text-black](text-6)

@css[text-05 text-black](text-5)


---?color=linear-gradient(180deg, white 75%, black 25%)
@title[Customize Slide Layout]

@snap[west span-50]
## Customize the Layout
@snapend

@snap[east span-50]
![](assets/img/presentation.png)
@snapend

@snap[south span-100 text-white]
Snap Layouts let you create custom slide designs directly within your markdown.
@snapend

---?color=linear-gradient(90deg, #E27924 65%, white 35%)
@title[Add A Little Imagination]

@snap[north-west h4-white]
#### And start presenting...
@snapend

@snap[west span-55]
@ul[spaced text-white]
- You will be amazed
- What you can achieve
- *With a little imagination...*
- And **GitPitch Markdown**
@ulend
@snapend

@snap[east span-45]
@img[shadow](assets/img/conference.png)
@snapend

---?image=assets/img/presenter.jpg

@snap[north span-100 h2-white]
## Now It's Your Turn
@snapend

@snap[south span-100 text-06]
[Click here to jump straight into the interactive feature guides in the GitPitch Docs @fa[external-link]](https://gitpitch.com/docs/getting-started/tutorial/)
@snapend
