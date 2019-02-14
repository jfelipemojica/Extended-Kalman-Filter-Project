# Extended Kalman Filter Project

We implemented the extended Kalman filter in C++. The data provided are simulated lidar and radar measurements detecting a bicycle that travels around your vehicle. You will use a Kalman filter, lidar measurements and radar measurements to track the bicycle's position and velocity.

We used the workspace provided by Udacity and the simulator to execute the project and know the output of this.

[//]: # (Image References)

[image1]: ./output_images/simulator_output.jpg

![alt text][image1]

Lidar measurements are red circles, radar measurements are blue circles with an arrow pointing in the direction of the observed angle, and estimation markers are green triangles. The image below shows what the simulator looks like when a c++ script is using its Kalman filter to track the object. The simulator provides the script the measured data (either lidar or radar), and the script feeds back the measured estimation marker, and RMSE values from its Kalman filter.
