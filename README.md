# TheCorruptionImpact

Here you will find the jupyter-notebook for conducting the experiments as well as the figures described in the paper:   
**The corruption impact**

## Content

1. The Final_Code_The_Effect_of_Corrupted_Data_on_Modern_ML_Models.ipynb notebook for creating the all the tables and figures in the paper.
2. The Pictures folder contains all the confusion matrices associated with all the accuracies of the neural networks. 

## Setup

The experiments were run on an RTX 3090 with 40GB disk space and 25GB RAM.

Each training and evaluating process finishes in maximum 20 minutes depending on the network size. 

# How to reproduce the reults
Rent an RTX 3090 with 40GB disk space and 25GB RAM from VAST.ai, upload the noteook of your choice and run as is line by line.

## Requirements

1. Tensorflow 2.4.0 
2. Keras 2.4.0
3. Numpy 1.17.3
4. Scikit-learn 0.20
5. Python 2.7

In addition, 24GB of RAM and 40GB of disk space is needed.

## Acknowledgement

The above code makes use of and adapt the code available at:
1. https://github.com/keras-team/keras
