# Flower Classification with CNN

## Overview

This project implements a convolutional neural network (CNN) using TensorFlow to classify images of flowers. The model is trained on a custom flower dataset, allowing for the classification of various flower species. Additionally, users can input external images for real-time classification.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Training the Model](#training-the-model)
- [Classifying External Images](#classifying-external-images)
- [Contributing](#contributing)


## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset

The model is trained on the [Flower Dataset](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz), which contains images of different flower species, including daisies, dandelions, roses, sunflowers, and tulips.

## Installation

To run this project, clone the repository and install the required libraries:

```bash
git clone https://github.com/ahmdmohamedd/CNN-flower-classification.git
cd CNN-flower-classification
pip install tensorflow numpy matplotlib
```

## Usage

To run the project, open the Jupyter notebook `flower_classifier.ipynb`. You can follow the steps outlined in the notebook to train the model and classify images.

### Classifying External Images

Within the notebook, you can find a section that allows users to classify external images. Simply provide the path to the image, and the model will return the predicted flower class.

## Training the Model

The model is defined within `flower_classifier.ipynb`, where it is built, compiled, and trained on the dataset. The training process includes data preprocessing and validation to evaluate performance.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.
