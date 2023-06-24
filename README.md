#two_wheel_differential_mobile_robot

一、启动gmapping建图（激光雷达）

1.启动GAZEBO

```
roslaunch mbot_gazebo mbot_laser_nav_gazebo.launch
```

2.启动RVIZ

```
roslaunch mbot_navigation gmapping_demo.launch
```

3.启动键盘控制节点

```
roslaunch mbot_teleop mbot_teleop.launch
```

4.运行地图保存服务



二、启动自主导航功能

1.

```
roslaunch mbot_gazebo mbot_laser_nav_gazebo.launch
```

2.

```
roslaunch mbot_navigation nav_cloister_demo.launch
```

