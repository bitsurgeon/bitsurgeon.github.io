### **[Behavioral Cloning](https://github.com/bitsurgeon/CarND_BehavioralCloning)**  

Train a deep neural network to drive like you!

A 9 layers neural network was trained to keep the car driving in the center of the lane line. The model get trained by observing how you drive in the Udacity car [simulator](https://github.com/udacity/self-driving-car-sim).

The driving data is captured by 3 cameras. Here are the examples of the captured images:

<img src="https://raw.githubusercontent.com/bitsurgeon/CarND_BehavioralCloning/master/examples/left1.jpg" alt="left" width="140">
<img src="https://raw.githubusercontent.com/bitsurgeon/CarND_BehavioralCloning/master/examples/center1.jpg" alt="center" width="140">
<img src="https://raw.githubusercontent.com/bitsurgeon/CarND_BehavioralCloning/master/examples/right1.jpg" alt="right" width="140">

Some of the highlights of the project are:

* the network consistes a mix of convolutional layers and fully connected layers
* different kernel sizes and strides are used
* dropout layer to prevent model overfitting
* ReLu activation to introduce non-linearity
* Python generator to work with limited GPU memory
* explored YUV color space
* achieved low Mean Square Error (MSE) loss

Here is a video demostration of the network.

[![Watch the video](https://img.youtube.com/vi/jrNxl5diAsM/mqdefault.jpg)](https://youtu.be/jrNxl5diAsM)

As shown in above video:

- The the car, when pulled to the side of the road in both straight lane and curves, can always recovery itself back onto the middle of the lane.
- It can navigate through the curves smoothly and keeps itself in the center of the lane all the time.

For details, please follow this [link](https://github.com/bitsurgeon/CarND_BehavioralCloning).
