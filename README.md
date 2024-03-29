# sensor_fusion_cg

* [ethzasl_sensor_fusion](http://wiki.ros.org/ethzasl_sensor_fusion): Time delay compensated single and multi sensor fusion framework based on an EKF
* [ethzasl_sensor_fusion Tutorials](http://wiki.ros.org/ethzasl_sensor_fusion/Tutorials)
* [robot_localization wiki](http://docs.ros.org/melodic/api/robot_localization/html/)
* [Sensor Fusion and Tracking Toolbox (mathworks)](https://www.mathworks.com/products/sensor-fusion-and-tracking.html)

-----

[TOC]

# Code

## Install & Build

* install dependencies
  ```sh
  wstool init src/ src/dependencies.rosinstall
  ```

* build
  ```sh
  catkin build
  ```

# Docs

## Methods Overview

<div align=center>
  <img src="./images/sensor_fusion_methods.jpg">
</div>

## Kalman Filter

* [Sensor Fusion and Object Tracking using an Extended Kalman Filter Algorithm — Part 1](https://medium.com/@mithi/object-tracking-and-fusing-sensor-measurements-using-the-extended-kalman-filter-algorithm-part-1-f2158ef1e4f0)

* [Sensor Fusion and Object Tracking using an Extended Kalman Filter Algorithm — Part 2
](https://medium.com/@mithi/sensor-fusion-and-object-tracking-using-an-extended-kalman-filter-algorithm-part-2-cd20801fbeff)

* [WTF is Sensor Fusion? The good old Kalman filter](https://towardsdatascience.com/wtf-is-sensor-fusion-part-2-the-good-old-kalman-filter-3642f321440)
* [Sensor Fusion (towardsautonomy)](http://www.towardsautonomy.com/sensor_fusion)
* [IMU-sensor-fusion-with-linear-Kalman-filter (mathworks)](https://www.mathworks.com/matlabcentral/fileexchange/70093-imu-sensor-fusion-with-linear-kalman-filter)
