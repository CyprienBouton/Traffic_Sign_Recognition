# Introduction

In this project, I use pytorch and python to classify 50km/h Traffic Signs among a set of images where the location of signs was already found.

# Table of contents

- [Dataset](#dataset)
- [Installation](#installation)
- [Development](#development)
- [Conclusion](#conclusion)

# Dataset

This project uses the German Traffic Sign Recognition Benchmark. The set of images can be downloaded [here](https://sid.erda.dk/public/archives/daaeac0d7ce1152aea9b61d9f1e19370/GTSRB_Final_Training_Images.zip) or you can directly run the first cells of the notebooks to get the images on your computer.

The dataset contains 43 different type classes of traffic signs and 39 209 images.

# Installation

To use this project, first clone the repo on your device using the command below:
```
git clone git@github.com:CyprienBouton/Traffic_Sign_Recognition.git
```
After create and activate a virtual environment. 
The library required are installed when the first cell of the notebook is executed.

# Development

Main steps of the notebook:
- Get and prepare images
- Investigate and visualize data
- Train a CNN network
- Visualize results

# Conclusion

In the end, we are able to recognize a 50km/h sign with a accuracy above 0.98 for our test set.

This type of algorithm could be useful for a self-driving car to recognize traffic signs. However, the car must first know where the traffic signs are. 
```



