# ORB_SLAM3-ROS-Interface
Two ROS interfaces Mono_inertial and Stereo_inertial were added to the ORB-SLAM3. Modified the loading vocabulary in a faster binary way.

增加了两个ROS接口，单目IMU和双目IMU，替换了词典为二进制格式，加载速度更快。

Command

Mono_inertial: rosrun ORB_SLAM3 Mono_inertial /YOUR_PATH/ORBvoc.bin /YOUR_PATH/EuRoC.yaml

Stereo_inertial: rosrun ORB_SLAM3 Stereo_inertial /YOUR_PATH/ORBvoc.bin /YOUR_PATH/EuRoC.yaml

![运行效果](https://github.com/xiefei2929/ORB_SLAM3-ROS-Interface/blob/master/ROS-Interface.png)
