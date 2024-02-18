# CIFAR-10 Gray to Color Autoencoder

## Description
This repository contains Python code to train an autoencoder model on the CIFAR-10 dataset to convert grayscale images to color images. The model architecture is based on the autoencoder architecture.

## Requirements
- Python 3.x
- Keras
- NumPy
- OpenCV
- Matplotlib

## Usage
1. **Clone the Repository**: Clone this repository to your local machine using the following command:
git clone https://github.com/Mahdi-Savoji/cifar10-gray2color-autoencoder.git


2. **Install Dependencies**: Install the required dependencies using `pip`:
pip install -r requirements.txt

3. **Dataset Preparation**: The CIFAR-10 dataset will be automatically downloaded and preprocessed by the code.

5. **Evaluation**: After training, the script will display some sample colorized images for evaluation.

6. **Prediction**: Use the trained model for colorization. You can download model and use it to load your own grayscale images and generate colorized versions.

## Model Architecture
The autoencoder model architecture consists of convolutional layers for encoding and decoding grayscale images.

## Results
Sample colorized images from the test dataset will be displayed after training the model.

## Acknowledgements
- The CIFAR-10 dataset is used for training and evaluation.
- The model architecture is inspired by autoencoder architectures.

## Author
- [Mahdi Savoji](https://github.com/Mahdi-Savoji)

