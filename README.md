# Autonomous-unmanned-Ground-Vehicle-
Final Year Project (FYP) / Thesis
Project was to enable a UGV to move through designated GPS waypoints autonomously while identifying and avoiding any obstacles in its route.
The project was considered the best in the department of Electrical Engineering for the year 2022 and Recieved Rector's Gold Medal
It involved
1) real-time detection through stereo vision cameras
2) calibration of stereo vision cameras that involved performing 
intrinsic calibration to cater for lens distortions and extrinsic calibration to establish the spatial 
relationship between the left and right cameras, enabling the transformation of pixel disparities into real world distances.
3) It involved using transfer learning to train SSD MobileNetV2 for real-time detection of any obstacle in the path. 
4) Deployment of SSD MobileNetV2 on Nvidia Jetson Nano using Linux.
5) SSD MobileNetV2 Tensor Rt optimized to increase FPS from 5 to 20.
6) ROS 1 melodic for modular design for the integration and communication with different
software and hardware nodes.
7) integration of ARDUPILOT map with GUI designed in PyQT5 for waypoint selection and navigation demonstration.
8) Sensor caliberation and sensor fusion for accurate localization.
