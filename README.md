# SELF DRIVING CAR

![N|Solid](https://i.ibb.co/59fN4qm/Webp-net-resizeimage-2.png)

The the goal of behavioral cloning is to collect data while exhibiting good behavior and then train a model to mimic that behavior with the collected data. This project makes use of Udacity's open source car simulator to generate image dataset by behavioral cloning. 
<br>The trained model works very well and manages to:</br>
- Stay on the track and keep driving at optimum speed
- come back to the center of lane(as the model is slightly biased toward center)
- avoid crashing into water, bridge or dividers.

## Tools/Libraries Used:
```
Git
Imgaug
PIL
SciKit-learn
Keras
Tensorflow
Numpy
Ntpath
Pandas
OpenCV
Matplotlib
```

## How to run:
* Download the simulator for your operating system from [here: ](https://github.com/udacity/self-driving-car-sim)
* To run the simulation, open ```Command Prompt``` or ```terminal``` at the ```git-clone``` or downloaded location.
* Input the following commands:
```sh
$ cd Self_Driving_Car
$ python drivercode.py
```
* Now open the simulation, and click on autonomous mode. The socket connection feeds in real time predictions of steering angle, throttle and speed from 3 cameras mounted on windshield of the car.

# Project Breakdown:
<br>The entire project is split-up in nine stages demonstrated below: </br>
![N|Solid](https://i.ibb.co/8mB14v0/Untitled-Diagram.png)
###### POWERED BY:
![N|Solid](https://blog.keras.io/img/keras-tensorflow-logo.jpg)
> Thanks to Udacity for open-sourcing their simulator. This project couldn't be successful without it.


