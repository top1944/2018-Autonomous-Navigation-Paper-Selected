Top Liu收集阅读的自动驾驶/自主导航文献，持续更新中...

# 学习步骤：  
（如果你的英文基础比较差，推荐以下两本中文书，并停止阅读本博客，因为本专题主要都是英文文献）  

## 中文书籍推荐  

1.《无人驾驶》 非常棒的入门读物！   
如果有人想要找一本关于无人驾驶汽车的书——智能的、广泛运用的、非教科书的、适合大众读者的——利普森教授的书将是很好的选择。

 ![Image text](https://images-cn.ssl-images-amazon.com/images/I/61%2BgFcYFiRL._SX357_BO1,204,203,200_.jpg)
 https://www.amazon.cn/dp/B0719JZ6L1/ref=sr_1_1?ie=UTF8&qid=1529376406&sr=8-1&keywords=%E6%97%A0%E4%BA%BA%E9%A9%BE%E9%A9%B6
 
2.《第一本无人驾驶技术书》 基本知识系统而全面

作者刘少山是PerceptIn联合创始人，加州大学欧文分校计算机博士。

![Image text](https://images-cn.ssl-images-amazon.com/images/I/51EqlykIG6L._SX377_BO1,204,203,200_.jpg)

 https://www.amazon.cn/dp/B07233NSW7/ref=sr_1_2?ie=UTF8&qid=1529376406&sr=8-2&keywords=%E6%97%A0%E4%BA%BA%E9%A9%BE%E9%A9%B6
 
 
## 机器人学预备知识
 
如果你对机器人一无所知，推荐ETH以下入门课程  
首先推荐：Autonomous Mobile Robots  
网页中的其他几门课有能力也鼓励学习     
http://www.asl.ethz.ch/education/lectures.html  


Programming for Robotics - ROS  
http://www.rsl.ethz.ch/education-students/lectures/ros.html

中文版及相关习题解答，参考瑞雷老师博客  
https://blog.csdn.net/zhangrelay/article/details/79463689


## 入门无人驾驶汽车  
1.经典必读  
首先是无人驾驶汽车之父Sebastian Thrun的两篇经典论文，体验一下真车的感受。 
其他的再继续补充。

2.综述  
如果你是研究人员或学校里的研究生，那首先阅读综述，了解当前最新研究动态是必须的。

3-自主平台系统与架构  
一些经典的平台设计，可作为参考。
  


———————————————————————————————————

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
git commit -m "20180619结构调整"  
git remote add origin https://github.com/top1944/2018-Autonomous-Navigation-Paper-Selected.git  
git push -u origin master 


git init 
git add -A
git commit -m "20180619结构调整"  
git remote add origin https://github.com/top1944/2018-Autonomous-Navigation-Paper-Selected.git 
git push --force origin  master

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

