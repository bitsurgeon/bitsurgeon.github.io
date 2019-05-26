### **[Traffic Sign Classifier](https://github.com/bitsurgeon/CarND_TrafficSignClassifier)**  

A [CNN](https://en.wikipedia.org/wiki/Convolutional_neural_network) network based on a modified [LeNet-5](http://yann.lecun.com/exdb/lenet/) has been trained to classify 43 German traffic signs.

<img src="https://raw.githubusercontent.com/bitsurgeon/CarND_TrafficSignClassifier/master/examples/LeNet-5.png" alt="LeNet-5" width="600">

The highlights of the project are listed in below:

* [German Traffic Sign Datasets](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) are used for training and testing
* the classic LeNet-5 has been exploried with [TensorFlow](https://www.tensorflow.org/) on GPUs
* data preprocessing improves training efficiency and reduced model sizes
* data regularization, such as [pooling](http://cs231n.github.io/convolutional-networks/#pool) and [dropout](https://en.wikipedia.org/wiki/Convolutional_neural_network#Dropout), to avoid model from over fitting
* the trained model has been verified against Internet sourced traffic signs
* visualised the hidden layers in the CNN, which reveals how the model learn by itself
* the CNN model was trained on both local PC and [AWS](https://aws.amazon.com/ec2/) G3 and P3 instances
* the AWS deep learning AMI image is build from scratch based on Ubuntu 18.04 LTS

An example of all the 43 different traffic signs used for training is shown in below.

<img src="https://raw.githubusercontent.com/bitsurgeon/CarND_TrafficSignClassifier/master/examples/all_signs.jpg" alt="all_signs" width="600">

Here is one of the traffic signs found from the Internet.

<img src="https://raw.githubusercontent.com/bitsurgeon/CarND_TrafficSignClassifier/master/extra_signs/sign_04.png" alt="70km/h" width="100">

Below are the feature maps extracted by the model at the first layer output of the CNN.

<img src="https://raw.githubusercontent.com/bitsurgeon/CarND_TrafficSignClassifier/master/examples/conv1.png" alt="conv1" width="600">

For details, please follow this [link](https://github.com/bitsurgeon/CarND_TrafficSignClassifier). A copy of the trained model can be found in [here](https://github.com/bitsurgeon/CarND_TrafficSignClassifier/tree/master/model).
