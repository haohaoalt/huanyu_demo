<!--
 * @Author: zhanghao
 * @Date: 2022-09-02 16:03:41
 * @LastEditTime: 2022-09-02 16:07:57
 * @FilePath: /huanyu_demo/README.md
 * @Description
-->
# huanyu_demo
这是一个简易的SLAM实验平台

## 01 ps2 control
```
cd ~/huanyu_demo
catkin_make
source devel/setup.bash
roslaunch huanyu_joy huanyu_ps2_control.launch
```
change the topic `cmd_vel` to `turtle1/cmd_vel`
```
rosrun turtlesim turtlesim_node
```
operate the ps2 and control the turtle1 moving. 