# Robotics-term2-P1-Robot-inference
### Abstract
Object detection is a priority task that helps manipulator and ground vehicle to complete their missions. Object detection
should provide object position and object class for implementing specify operation. Especially, when a robot want to do a operation with
a tool, robot needs to know what the kind of the tool is. So an automated tool recognition solution is needed. In this paper, a method
based on convolutional neural network is presented. Using supervised learning on the NVIDIA deep learning platform which name is
DIGITS. The hardware to gathering the data is a depth camera d435 from INTEL. The common deep learning layer structure used in
this paper is ’GoogLeNet’ and ’Alexnet’. With the GPU acceleration parallel computing service which is provided from Udacity reduces
a lot of time. With this method, algorithm can gives a reliable recognition result with only RGB input. The result is only verified in single picture level.

![Classification result](https://github.com/Fred159/Robotics-term2-P1-Robot-inference/blob/master/Project%20figures/alexnet_scissors.jpg)
