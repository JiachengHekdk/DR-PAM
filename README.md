<h1 align="center">
  <span style="font-size: 40px;">PriDRAM</span> <!-- 将字体大小从30px调整到40px -->
  <br> <!-- 在描述文字之前的换行保持不变 -->
  Priority-Based Deadlock Recovery for Distributed Swarm Obstacle Avoidance in Cluttered Environments
</h1>


An introduction video can be seen on  [Bilibili](https://www.bilibili.com/video/BV19DYAe3EVi/?spm_id_from=333.999.list.card_archive.click&vd_source=2421d86d062a73ffa2c05fb6487e7fcf)


## Quick Start

### Installation

```
Installation
This work is implemented in C++17 and tested on ROS Melodic and Noetic.

Install ROS

Install eigen_quad_prog and run sudo ln -s /usr/include/eigen3/Eigen /usr/include/Eigen.
```

### Preparation

(1) Clone and build the package

```
cd catkin_ws/src
https://github.com/JiachengHekdk/PriDRAM.git
cd .. 
catkin_make  
source devel/setup.bash  
```

(2) Change the parameters of config_5deadlock.yaml according to your settings and run the demo:

```yaml
rosrun dr_pam run_dr_pam
```
(3) Then you will get a .txt file in data profile and can use the animate_trajectory.py to run visualization in matlab.
### Contact
Currently, this is only the initial version. We will continuously improve the code quality and readability, as well as fix some bugs. Please stay tuned for our follow-up work.

Jiacheng he (22232021@zju.edu.cn)
