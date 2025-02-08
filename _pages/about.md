---
permalink: /
title: "Welcome"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a lecturer in Guangdong Ocean University, China. Now I am working as a research associate in Newcastle University, developing the software for underwater buoyancy-driven gliders. 

I mainly work on the underwater VO/SLAM based on the combination of multiple sensors, taking advantages of the conventional acoustic means and cutting-edge computer vision technologies.  I recieved my Ph.D in Marine Technology in Newcastle Univeristy, 2021, working on the underwater autonomous vehicle navigation, researching the multiple sensors fusion method to enhance the accuracy of the conventional fashion of the underwater positioning.  

Project Hightligts
======

Real-Time Underwater Autonomous Buoyancy-driven Glider Simulator
------
We proposed the UGSim, a simulator for buoyancy-driven gliders, with a LQR control strategy, and a recursive guidance
system. Building on the top of the DAVE and the UUVsim, it is designed to address unique challenges that come from the complex
hydrodynamic and hydrostatic impacts on buoyancy-driven gliders, which conventional robotics simulators can’t deal with. **\[Click below link to see the video\],\[[Click to PDF](https://xuzhizun.github.io/files/2501.17851v1.pdf)\]**.

[![Watch the Video](https://img.youtube.com/vi/0ZNpnGoFGWM/0.jpg)](https://www.youtube.com/watch?v=0ZNpnGoFGWM)


Modularised ROV Developed Based on ROS
------
In order to collect data and evaluate proposed navigation and localisation algorithms, the multi-function ROV
was developed. It is of open-frame type, and has a modular design, with extra functionality loaded on demand. **\[Click below link to see the video\],\[[Click to PDF](https://xuzhizun.github.io/files/modularisedRov.pdf)\]**.

[![Watch the video](https://img.youtube.com/vi/XEVUgK7OR00/0.jpg)](https://www.youtube.com/watch?v=XEVUgK7OR00)


Integrated VO for Underwater Vehicles 
------
The proposed algorithms fusing data from a camera, a sonar, and a gyroscope, localise underwater vehicles in
sparse environments, whilst being at low cost. Our proposed methods(IVO-monocular and IVO Stereo) outperform the ORB-SLAM2, VINS and OKVIS in underwater sparse environments. 
**\[Click below link to see the comparison video\],\[[Click to PDF](https://xuzhizun.github.io/files/paper1.pdf)\]**.

[![Watch the Video](https://img.youtube.com/vi/C1qkOEcEFiY/0.jpg)](https://www.youtube.com/watch?v=C1qkOEcEFiY)


ArUco Marks Implimented in Underwater Positioning
------
The multiple ArUco markers are set out beforehand. With the knowledge of the computer vision, such markers may
be detected by a camera. Simultaneously, the pose of the camera related to markers is calculated without suffering 
from the accumulative error. **\[Click below link to see the video\],\[[Click to PDF](https://xuzhizun.github.io/files/paper4.pdf)\]**.

[![Watch the video](https://img.youtube.com/vi/IoqIBqz2smw/0.jpg)](https://www.youtube.com/watch?v=IoqIBqz2smw)


LiDAR Camera Implimented in Underwater Positioning  
------
The LiDAR camera, benefiting from the laser scanning techniques, could generate the associated depth maps.
With the altitudes provided by the IMU, the positions of underwater vehicles can be estimated. **\[Click below link to see the video\],\[[Click to PDF](https://xuzhizun.github.io/files/paper3.pdf)\]**.

[![Watch the video](https://img.youtube.com/vi/paiOY9JxJyI/0.jpg)](https://www.youtube.com/watch?v=paiOY9JxJyI)


Publication
======
- Xu, Z., Haroutunian, M., Murphy, A.J., Neasham, J. and Norman, R., 2021. An integrated visual odometry system for underwater vehicles. IEEE Journal of Oceanic Engineering, 46(3), pp.848-863.

- Xu, Z., Haroutunian, M., Murphy, A.J., Neasham, J. and Norman, R., 2022. An integrated visual odometry system with stereo camera for unmanned underwater vehicles. IEEE Access, 10, pp.71329-71343.

- Xu, Z., Haroutunian, M., Murphy, A.J., Neasham, J. and Norman, R., 2020. A comparison of functional control strategies for underwater vehicles: Theories, simulations and experiments. Ocean Engineering, 215, p.107822.

- Xu, Z., Haroutunian, M., Murphy, A.J., Neasham, J. and Norman, R., 2021, October. A low-cost visual inertial odometry system for underwater vehicles. In 2021 4th International Conference on Mechatronics, Robotics and Automation (ICMRA) (pp. 139-143). IEEE.

- Xu, Z., Haroutunian, M., Murphy, A.J., Neasham, J. and Norman, R., 2021. An underwater visual navigation method based on multiple ArUco markers. Journal of Marine Science and Engineering, 9(12), p.1432.
  
- Xu, Z., Song, Y., Zhu, J. and Shi, W., 2025. UGSim: Autonomous Buoyancy-Driven Underwater Glider Simulator with LQR Control Strategy and Recursive Guidance System. arXiv preprint arXiv:2501.17851.
 
- Merveille, F.F.R., Jia, B., Xu, Z. and Fred, B., 2024. Advancements in Sensor Fusion for Underwater SLAM: A Review on Enhanced Navigation and Environmental Perception. Sensors (Basel, Switzerland), 24(23), p.7490.

- Merveille, F.F.R., Jia, B., Xu, Z. and Fred, B., 2024. Enhancing Underwater SLAM Navigation and Perception: A Comprehensive Review of Deep Learning Integration. Sensors (Basel, Switzerland), 24(21), p.7034.
  
- Yang, H., Xu, Z. and Jia, B., 2022. An underwater positioning system for uuvs based on lidar camera and inertial measurement unit. Sensors, 22(14), p.5418.

