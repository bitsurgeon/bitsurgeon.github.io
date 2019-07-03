### **[Behavioral Cloning](https://github.com/bitsurgeon/CarND_BehavioralCloning)**  

Train a deep neural network to drive like you!

A 9 layers neural network was trained to keep the car driving in the center of the lane line. The model get trained by observing how you drive in the Udacity car simulator.

The driving data is captured by 3 cameras. Here are the examples of the captured images:

<img src="https://raw.githubusercontent.com/bitsurgeon/CarND_BehavioralCloning/master/examples/left1.jpg" alt="left" width="140">
<img src="https://raw.githubusercontent.com/bitsurgeon/CarND_BehavioralCloning/master/examples/center1.jpg" alt="center" width="140">
<img src="https://raw.githubusercontent.com/bitsurgeon/CarND_BehavioralCloning/master/examples/right1.jpg" alt="right" width="140">

Some of the highlights of the project are:

* a mix of convolutional layers and fully connected layers
* different kernel sizes and strides are used
* dropout layer to prevent model overfitting
* ReLu activation to introduce non-linearity
* Keras with TensorFlow backend
* Python generator to work with limited GPU memory
* explored YUV color space
* achieved low Mean Square Error (MSE) loss

Here is a video demostration on how the car drive by the nerual network.

[![Watch the video](https://img.youtube.com/vi/A9180bNoAQI/mqdefault.jpg)](https://youtu.be/A9180bNoAQI)

What if the car is driving towards the side of the road? Look at the following video demo to see how the car recovery itself to back on to the middle of the lane.

[![Watch the video](https://img.youtube.com/vi/lEpytd-Qf5A/mqdefault.jpg)](https://youtu.be/lEpytd-Qf5A)

As shown in the above videos:

- The the car, when pulled to the side of the road in both straight lane and curves, can always recovery itself back onto the middle of the lane.
- It can navigate through the curves smoothly and keeps itself in the center of the lane all the time.

A dashcam view can also be checked in below:

[![Watch the video](https://img.youtube.com/vi/YpapT2HVvuo/mqdefault.jpg)](https://youtu.be/YpapT2HVvuo)

For details, please follow this [link](https://github.com/bitsurgeon/CarND_BehavioralCloning).
