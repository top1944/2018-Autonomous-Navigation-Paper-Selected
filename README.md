# 论文列表
1. Build Your Own Visual-Inertial Drone: A Cost-Effective and Open-Source Autonomous Drone   

Inkyu Sa;   Mina Kamel;   Michael Burri;   Michael Bloesch;   Raghav Khanna;   Marija Popovic;   Juan Nieto;   Roland Siegwart     
IEEE Robotics & Automation Magazine    
Year: 2017, Volume: PP, Issue: 99   
代码：https://github.com/ethz-asl/mav_dji_ros_interface  

 2. NanoMap: Fast, Uncertainty-Aware Proximity Queries with Lazy Search over Local 3D Data
 
 视频：http://news.mit.edu/2018/mit-csail-programming-drones-fly-face-uncertainty-0212  
 代码：https://github.com/peteflorence/nanomap_ros
 
## github上传命令  
 
cd D:\github\2018-Autonomous-Navigation-Paper-Selected  
git init  
git add .  
git commit -m "注释"  
git remote add origin https://github.com/top1944/2018-Autonomous-Navigation-Paper-Selected.git  
git push -u origin master  
git pull --rebase origin master

ssh权限查看
ssh -T git@github.com  

如果没有密钥，则通过密钥生成   
ssh-keygen -t rsa -C "name@163.com"  
用记事本打开id_rsa.pub，得到ssh key公钥  
切换到github，展开个人头像的小三角，点击settings，然后打开SSH keys菜单， 点击Add SSH key新增密钥  

