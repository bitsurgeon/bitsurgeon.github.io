### **[Extended Kalman Filter](https://github.com/bitsurgeon/CarND_ExtendedKalmanFilter)**  

A sensor fusion pipeline for moving object tracking with combined measurements from LIDAR and RADAR.

Some of the highlights of the projects:

* Implemented [Extended Kalman Filter](https://en.wikipedia.org/wiki/Extended_Kalman_filter) in C++
* Estimate object's position and velocity with RADAR and LIDAR measurements
* Use popular linear algebra library [Eigen](http://eigen.tuxfamily.org/index.php)

Here is a video demonstration.

[![Watch the video](https://img.youtube.com/vi/MtKtwCzxLpE/mqdefault.jpg)](https://youtu.be/MtKtwCzxLpE)

- LIDAR measurements are red circles
- RADAR measurements are blue circles with an arrow pointing in the direction of the observed angle
- estimation markers are green triangles
- ground truth positions are marked with the object

As shown in the demo, neither the LIDAR nor the RADAR measurements is good enough for the object tracking by itself. The EKF is making use of the noisy sensor data from both LIDAR and RADAR to provide a posterior of the location of the target. And what's important is that this esitmate is well aligned with the true location of the object.

For details, please follow this [link](https://github.com/bitsurgeon/CarND_ExtendedKalmanFilter).
