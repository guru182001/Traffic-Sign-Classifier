# Traffic Sign Classification

### Overview
In this project, I used deep neural networks and three classic convolutional neural network architectures(LeNet, AlexNet and GoogLeNet) to classify traffic signs. I will train and validate a model so it can classify traffic sign images using the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset). After the model is trained, I will then try out my model on images of German traffic signs that I find on the web.

### The goals / steps of this project are the following:
* Load and explore the data set.
* Realize LeNet architecture and use `ReLu`, `mini-batch gradient descent` and `dropout`. 
* Realize AlexNet and make some modifications, use `learning rate decay`, `Adam optimization` and `L2 regulization`. 
* Use GoogLeNet to classify traffic signs and make some modifications, use `inception` and `overlapping pooling` and `average pooling`. 
* Analyze the softmax probabilities of the new images
* Summarize the results

### Dependencies
python3.5  
matplotlib (2.1.1)  
opencv-python (3.3.1.11)  
numpy (1.13.3)  
tensorflow-gpu (1.4.1)  
sklearn (0.19.1)  

### Dataset
Download the [data set](https://d17h27t6h515a5.cloudfront.net/topher/2017/February/5898cd6f_traffic-signs-data/traffic-signs-data.zip). This is a pickled dataset in which the images are already resized to 32x32. It contains a training, validation and test set.


[//]: # (Image References)
[exploratory]: ./result_images/exploratory.jpg "exploratory"
[distribution]: ./result_images/distribution.jpg "distribution"
[lenet]: ./result_images/lenet.png "lenet"
[alexnet]: ./result_images/alexnet.png "alexnet"
[inception]: ./result_images/inception.jpg "inception"
[googlenet]: ./result_images/GoogLeNet.png "googlenet"
[image2]: ./test_images/1.jpg "Traffic Sign 1"
[image3]: ./test_images/2.jpg "Traffic Sign 2"
[image4]: ./test_images/3.jpg "Traffic Sign 3"
[image5]: ./test_images/4.jpg "Traffic Sign 4"
[image6]: ./test_images/5.jpg "Traffic Sign 5"
[image7]: ./test_images/6.jpg "Traffic Sign 6"
[image8]: ./test_images/7.jpg "Traffic Sign 7"
[image9]: ./test_images/8.jpg "Traffic Sign 8"
[image10]: ./test_images/9.jpg "Traffic Sign 9"
[image11]: ./test_images/10.jpg "Traffic Sign 10"
