# SYSU-Campus-GVI-Dataset

### A campus scene GNSS-visual-inertial dataset collected at Sun Yat-sen University Shenzhen Campus.
![map_sysu](https://github.com/SYSU-CPNTLab/SYSU-Campus-GVI-Dataset/assets/74598384/c039b9a8-81d1-4094-aa11-6ca49ab2f9ef)

![scence](https://github.com/SYSU-CPNTLab/SYSU-Campus-GVI-Dataset/assets/74598384/1b91d1fe-3e0b-41de-a885-8e2d4bd440b5)

### The data items within the rosbag are listed below:
| topic | type | frequency | description |
| :---: | :--: | :-------: | :---------: |
| /camera/imu | sensor_msgs/Imu | 200Hz | IMU measurments from D455|
| /camera/infra1/image_rect_raw | sensor_msgs/Image | 30Hz | left camera |
| /camera/infra2/image_rect_raw | sensor_msgs/Image | 30Hz | right camera |
| /fixposition/corrimu | sensor_msgs/Imu | 200Hz | IMU measurments from VRTK2| 
| /fixposition/gnss1 | sensor_msgs/NavSatFix | 5Hz | GNSS1 RTK position from VRTK2| 
| /fixposition/gnss2| sensor_msgs/NavSatFix | 5Hz | GNSS2 RTK position from VRTK2| 

### Data set download：
LINK: https://pan.baidu.com/s/1SiHDs3xduDLrfQUzlAEYEQ 

PASSWORD: CPNT 
