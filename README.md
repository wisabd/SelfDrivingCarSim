# SelfDrivingCarSim 
First CV project

Goal of the project: Train a self-driving car using a CNN

Concept (developed by NVIDIA): The model is given the inputs of steering angle, and three camera inputs (left, center, right) for it to learn driving. 

Data Collection: Drive the car using Udacity's simulator and collect the data
      1.  Go to Udacity, open simulator, select settings
      2.  Go to training mode, Use autonomoys mode post training
      3.  Go to first track, then on second for generalization
      4.  Run the track 3 to 5 times each
      5.  Record the values using the button. This creates images files containing left, center, right cameras, in addition to a drivinglog csv file containing paths to the images (center, left, right), steering angle, throttle, brake, speed. To train the model, we use center images and steering angle.

Data preprocessing: 



