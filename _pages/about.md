---
permalink: /
#title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Welcome
=====
I am a lecturer in Guangdong Ocean University, China. Now I am working as a research associate in Newcastle University, developing the software for underwater buoyancy-driven gliders. 

I mainly work on the underwater VO/SLAM based on the combination of multiple sensors, taking advantages of the conventional acoustic means and cutting-edge computer vision technologies.  I recieved my Ph.D in Marine Technology in Newcastle Univeristy, 2021, working on the underwater autonomous vehicle navigation, researching the multiple sensors fusion method to enhance the accuracy of the conventional fashion of the underwater positioning.  

Project Hightligts
======

Real-Time Underwater Autonomous Buoyancy-driven Glider Simulator
------
We proposed the UGSim, a simulator for buoyancy-driven gliders, with a LQR control strategy, and a recursive guidance
system. Building on the top of the DAVE and the UUVsim, it is designed to address unique challenges that come from the complex
hydrodynamic and hydrostatic impacts on buoyancy-driven gliders, which conventional robotics simulators can’t deal with.
[![Watch the Video](https://img.youtube.com/vi/wowY2xWD2XI/0.jpg)](https://www.youtube.com/watch?v=wowY2xWD2XI)


Modularised ROV Developed Based on ROS
------
In order to collect data and evaluate proposed navigation and localisation algorithms, the multi-function ROV
was developed. It is of open-frame type, and has a modular design, with extra functionality loaded on demand.
[![Watch the video]()]()


Integrated VO for Underwater Vehicles 
------
The proposed algorithms fusing data from a camera, a sonar, and a gyroscope, localise underwater vehicles in
sparse environments, whilst being at low cost. **A video of the comparisons of our proposed methods(IVO-monocular and IVO Stereo), ORB SLAM2, VINS and OKVIS is given below,** 
[![Watch the Video](https://img.youtube.com/vi/C1qkOEcEFiY/0.jpg)](https://www.youtube.com/watch?v=C1qkOEcEFiY)


ArUco Marks Implimented in Underwater Positioning
------
The multiple ArUco markers are set out beforehand. With the knowledge of the computer vision, such markers may
be detected by a camera. Simultaneously, the pose of the camera related to markers is calculated without suffering 
from the accumulative error.
[![Watch the video](https://img.youtube.com/vi/IoqIBqz2smw/0.jpg)](https://www.youtube.com/watch?v=IoqIBqz2smw)


LiDAR Camera Implimented in Underwater Positioning  
------
The LiDAR camera, benefiting from the laser scanning techniques, could generate the associated depth maps.
With the altitudes provided by the IMU, the positions of underwater vehicles can be estimated.
[![Watch the video]()]()


Publication
======
- Xu, Z., Haroutunian, M., Murphy, A.J., Neasham, J. and Norman, R., 2020. An integrated visual odometry system for underwater vehicles. IEEE Journal of Oceanic Engineering, 46(3), pp.848-863.

- Yang, H., Xu, Z. and Jia, B., 2022. An underwater positioning system for uuvs based on lidar camera and inertial measurement unit. Sensors, 22(14), p.5418.

- Xu, Z., Haroutunian, M., Murphy, A.J., Neasham, J. and Norman, R., 2021. An underwater visual navigation method based on multiple ArUco markers. Journal of Marine Science and Engineering, 9(12), p.1432.

- Xu, Z., Haroutunian, M., Murphy, A.J., Neasham, J. and Norman, R., 2022. An integrated visual odometry system with stereo camera for unmanned underwater vehicles. IEEE Access, 10, pp.71329-71343.

- Xu, Z., Haroutunian, M., Murphy, A.J., Neasham, J. and Norman, R., 2020. A comparison of functional control strategies for underwater vehicles: Theories, simulations and experiments. Ocean Engineering, 215, p.107822.




------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).
