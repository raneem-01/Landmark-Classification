# CNN Landmark Classification Project 



## Overview

This project implements a Convolutional Neural Network (CNN) to predict the locations of images based on discernible landmarks. It aims to address the challenge faced by photo-sharing services when location metadata is unavailable, enabling automatic tagging and organization of images.


## Objectives

- Build a CNN model to detect and classify landmarks in user-supplied images.
- Create a user-friendly application that suggests the top k relevant landmarks from a predefined set of 50 landmarks worldwide.
- Understand the complexities of developing a data processing pipeline with multiple models.


## Motivation

With the increasing number of images uploaded to various platforms, the lack of location metadata poses a significant challenge. This project seeks to leverage deep learning to automate the location inference process, enhancing user experience with improved tagging and organization of photos.


## Methodology

1. **Training a CNN Model from Scratch**
   - A Convolutional Neural Network (CNN) is created to classify landmarks. This step involves visualizing the dataset, preparing it for training, and building the network architecture from scratch. Emphasis is placed on the decision-making process regarding data processing and the structure of the network. The best-performing model is then exported using Torch Script.
   - **Corresponding Jupyter Notebook:** [cnn_from_scratch.ipynb](https://github.com/raneem-01/Landmark-Classification/blob/main/cnn_from_scratch.ipynb)

2. **Using Transfer Learning**
   - A CNN is established for landmark classification using Transfer Learning. Various pre-trained models are explored, and a specific model is selected for the classification task. This process includes training and testing the transfer-learned network, along with an explanation of the rationale behind choosing the pre-trained model. The optimal transfer learning solution is exported using Torch Script.
   - **Corresponding Jupyter Notebook:** [transfer_learning.ipynb](https://github.com/raneem-01/Landmark-Classification/blob/main/transfer_learning.ipynb)


## Getting Started

1. Clone the repository.
   
2. Create and activate a new conda environment:
   
   - Run the following command:
    ```bash
    conda create --name cnn_landmark_project -y python=3.7.6
    conda activate cnn_landmark_project
    
3. Install the required packages:
   
   - Run the following command:
   ```bash
   pip install -r requirements.txt
   
4. Launch Jupyter Lab:
   
   - Run the following command:
   ```bash
   pip install jupyterlab
   jupyter lab


##
**This project is for the CNN Udacity course.**
