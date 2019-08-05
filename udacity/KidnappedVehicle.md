### **[Kidnapped Vehicle](https://github.com/bitsurgeon/CarND_KidnappedVehicle)**

An end-to-end localizer using 2D Monte Carlo Localization for sparse feature map according to LIDAR measurements.

Some of the highlights of the projects:

* Implemented [Particle Filter](https://en.wikipedia.org/wiki/Monte_Carlo_localization) in C++
* Estimate position of a moving car based on LIDAR measurements

Here is a video demonstration.

[![Watch the video](https://img.youtube.com/vi/0gnI4elrmuk/mqdefault.jpg)](https://youtu.be/0gnI4elrmuk)

- blue car - ground truth data
- blue circle, with arrow point to the heading of the car - estimated location
- green line - laser range reading from the car
- blue line - laser range reading from the particle

As shown in the demo, the green laser sensors from the car nearly overlap the blue laser sensors from the particle, this means that the particle transition calculations were done correctly.

For details, please follow this [link](https://github.com/bitsurgeon/CarND_KidnappedVehicle).
