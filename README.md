# Behavior Cloning

The goal of the project was to train a Deep Network to replicate the human steering behavior while driving.
This was done using a simulator provided by [Udacity](https://www.udacity.com/). 
The network takes the frame of the frontal camera as input and predicts the steering direction at each instant.

## Overview

The code is structured as follows:
- config.py: project configuration and hyperparameters
- model.py: model definition and training
- drive.py: interaction with the simulator (actually drive the car)
- load_data.py: definition of data generator + handling data augmentation
- visualize_data.py: exploratory visualization of the dataset, used in this readme
- visualize_activations.py: visualization of the trained network activations, used in the demo video above

## The dataset
The data was obtained from Udacity's training set.

A future improvement could be to predict the car throttle along with the steering angle. 
