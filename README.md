# 正在阅读论文列表
-----------------------
## SLAM综述
1. SLAM: Towards the Robust-Perception Age  
数据集：  
https://slam-future.github.io/  
https://github.com/SLAM-future  

----------------------
## SLAM-Event-based Vision

1.ppt-Tutorial on Event-based Vision for High-Speed Robotics

2.The Event-Camera Dataset and Simulator_ Event-based Data for Pose Estimation, Visual Odometry, and SLAM

仿真环境/数据集与ROSbag数据包

http://rpg.ifi.uzh.ch/davis_data.html  
http://rpg.ifi.uzh.ch/research_dvs.html
 
ROS DVS driver + intrinsic and extrinsic stereo calibration open source:  
https://github.com/uzh-rpg/rpg_dvs_ros

DVS software for Windows and Linux (lot of utilities for LED, line, blob tracking, and even
processing)  
http://sourceforge.net/p/jaer/wiki/jAER%20Installation/  
http://sourceforge.net/p/jaer/wiki/jAER%20USB%20Driver%20Install/  

  
3.Ultimate SLAM? Combining Events, Images, and IMU for Robust Visual SLAM in HDR and High Speed Scenarios.pdf

https://spectrum.ieee.org/automaton/robotics/drones/drone-with-event-camera-takes-first-autonomous-flight  

---------------------------------------------------------------
## VI 
1.Build Your Own Visual-Inertial Drone: A Cost-Effective and Open-Source Autonomous Drone   

	Inkyu Sa;   Mina Kamel;   Michael Burri;   Michael Bloesch;   Raghav Khanna;   Marija Popovic;   Juan Nieto;   Roland Siegwart     
	IEEE Robotics & Automation Magazine    
	Year: 2017, Volume: PP, Issue: 99   
	代码：https://github.com/ethz-asl/mav_dji_ros_interface  

2.NanoMap: Fast, Uncertainty-Aware Proximity Queries with Lazy Search over Local 3D Data
 
	视频：http://news.mit.edu/2018/mit-csail-programming-drones-fly-face-uncertainty-0212  
	代码：https://github.com/peteflorence/nanomap_ros
 
	龟速SLAM已经over了，未来主要就是解决高速SLAM的问题了。高速/鲁棒SLAM并进一步与控制结合，对于对于无人车，无人机等高动态vehicle都是非常重要的。

	Currently, the average robot-vision algorithms have latencies of 50-200 ms.  
	This puts a hard bound on the agility of the platform. [Censi & Scaramuzza, ICRA’14]  
	To go faster, we need faster sensors!

 ![Image text](pic/camera_parameter.png)

 -------------------------------------
## other/
1.Towards a science of integrated AI and Robotics

Rajan K, Saffiotti A. Towards a science of integrated AI and Robotics[J]. Artificial Intelligence, 2017.

60年前，AI与Robotics分道扬镳，但为了共同的理想，一个沿着top-down另一个沿着bottom-up的路径发展，均取得巨大成就。今天，新一代的机器人需要更高的智能，AI也需要更有挑战性的应用场景，二者将重新合流，融为一体。
 
 
 
 ![Image text](pic/paper.jpg)
 
 
----------------------------------------------------- 
 ## github上传命令  
 
cd D:\github\2018-Autonomous-Navigation-Paper-Selected  
git init  
git add .  
git commit -m "注释"  
git remote add origin https://github.com/top1944/2018-Autonomous-Navigation-Paper-Selected.git  
git push -u origin master  

## githu删除命令  
cd D:\github\2018-Autonomous-Navigation-Paper-Selected  
git pull origin master 将远程仓库里面的项目拉下来  
ls  查看有哪些文件夹   
git rm -r --cached target  删除target文件夹  
git commit -m '注释'  提交,添加操作说明    
git push -u origin master 将本次更改更新到github项目上去  

## ssh权限查看
ssh -T git@github.com  

如果没有密钥，则通过密钥生成   
ssh-keygen -t rsa -C "name@163.com"  
用记事本打开id_rsa.pub，得到ssh key公钥  
切换到github，展开个人头像的小三角，点击settings，然后打开SSH keys菜单， 点击Add SSH key新增密钥  

