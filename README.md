
# OBJECT Detection Using YOLO
The main contribution in this project is to use the state of the art YOLO Neural network architecture to train the model on custom datasets collected for persons and objects in undreground mines.


# Training the model and creating the new dataset and testing the model
The following document talks in detail on how to setup the YOLO neural network, Create custom dataset, Train and test the model 
https://github.com/sbperceptron/YOLOv2--custom-dataset\

The products of such a initiative are,
1. Leg Detection for smart cane project : 
Applying Computer vision to detect objects in the environment and assist blind people to navigate through busy environments. The dataset developed essentially consists of a single class, which are hand annoted images of legs of persons.
# Results:
[![Leg Detection](https://github.com/sbperceptron/Object-Detection-Using-YOLO/blob/master/Screenshot%20(4).png)](https://www.youtube.com/watch?v=XO6vIVuBunY)

2. Real time object detection of personal and equipment in under ground mines:
Underground mines are places which are very harsh for people to work in. This project is part of the idea to automate the work and improve personal safety in underground mines. In addition to creating the datset, Improvements are made to the existing tiny-YOLO model to able real-time object detection on a Jetson TX2 embedded onto a mobile robot. A dataset consisting of 5 classes is developed. Which constitute persons,hardhat, fire extinguisher, powerbox and safety valves After training the YOLO neural network on the dataset deveoped the model is deployed onto a mobile robot for testing in underground mine conditions. From the tests conducted it is observed that the model performaned well for the application developed

# Results:
Cannot share the results as the data is internal to Colorado school of mines

References:
https://pjreddie.com/darknet/
