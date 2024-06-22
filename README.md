# Dog Breed Identification Using Deep Learning

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Contributing](#contributing)

## Introduction

This project aims to identify more than 120 dog breeds using an image. The model is trained using transfer learning with the MobileNetV2 architecture. The training dataset consists of over 10,000 images and the model achieved a high accuracy of 94%.

## Features

* Identifies over 120 dog breeds from images.
* High accuracy of 94%.
* Utilizes transfer learning with the MobileNetV2 model.
* Easy-to-use Google Colab notebook for training and inference.
  
## Installation

### Prerequisites

* Google Colab
* Basic understanding of Python and deep learning
* Internet connection for downloading datasets and model weights
  
### Steps

1. Clone the repository:
   ```sh
   git clone https://github.com/anish0094/Dog-vision.git

3. Open the Google Colab file (Dog_Breed_Identification.ipynb) in Google Colab.

4. Follow the instructions in the notebook to set up the environment, download the dataset, and train the model.

## Usage
1. Open the Google Colab file (Dog_Breed_Identification.ipynb) in Google Colab.
2. Execute the cells sequentially to set up the environment and train the model.
3. Use the provided inference functions to identify the breed of a dog from an image.

## Model Details
The model used in this project is based on the MobileNetV2 architecture, which is known for its efficiency and accuracy in image classification tasks. Transfer learning is employed to leverage the pre-trained weights of MobileNetV2, fine-tuned on our dataset of over 10,000 dog images.

## Performance
* Training Accuracy: 94%
* Validation Accuracy: 93%
* Test Accuracy: 94%

## Dataset
The dataset consists of over 10,000 images spanning 120 different dog breeds. The images are sourced from the Kaggle.

## Contributing
We welcome contributions to improve the functionality and accuracy of this project. If you are interested in contributing, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes and commit them (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature-branch).
5. Create a new Pull Request.
