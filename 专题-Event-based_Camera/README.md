龟速SLAM已经over了，未来主要就是解决高速SLAM的问题了。高速/鲁棒SLAM并进一步与控制结合，对于对于无人车，无人机等高动态vehicle都是非常重要的。

Currently, the average robot-vision algorithms have latencies of 50-200 ms.  
This puts a hard bound on the agility of the platform. [Censi & Scaramuzza, ICRA’14]  
To go faster, we need faster sensors!

 ![Image text](camera_parameter.png)

# 正在阅读论文列表

0.ppt-Tutorial on Event-based Vision for High-Speed Robotics

1.The Event-Camera Dataset and Simulator_ Event-based Data for Pose Estimation, Visual Odometry, and SLAM

仿真环境/数据集与ROSbag数据包

http://rpg.ifi.uzh.ch/davis_data.html  
http://rpg.ifi.uzh.ch/research_dvs.html
 
ROS DVS driver + intrinsic and extrinsic stereo calibration open source:  
https://github.com/uzh-rpg/rpg_dvs_ros

DVS software for Windows and Linux (lot of utilities for LED, line, blob tracking, and even
processing)  
http://sourceforge.net/p/jaer/wiki/jAER%20Installation/  
http://sourceforge.net/p/jaer/wiki/jAER%20USB%20Driver%20Install/  

  
2. Ultimate SLAM? Combining Events, Images, and IMU for Robust Visual SLAM in HDR and High Speed Scenarios.pdf

https://spectrum.ieee.org/automaton/robotics/drones/drone-with-event-camera-takes-first-autonomous-flight
 
 ![Image text](paper.jpg)
 
 
 
 