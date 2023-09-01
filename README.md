# Semantic Segmentation for Self Driving Car

Semantic Segmentation for Self Driving Cars is a project focused on pixel-level image segmentation for autonomous vehicles. The goal is to accurately classify each pixel in an image, assigning it to a specific object class, such as road, vehicle, pedestrian, or obstacle. This repository contains the code, models, and data for training and evaluating the semantic segmentation model.

## Table of Contents

  - [About](#about)
  - [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Contributing](#contributing)
  - [License](#license)

## About

Semantic segmentation is a critical component of self-driving car systems. It provides a detailed understanding of the road environment, allowing autonomous vehicles to make informed decisions. This project explores state-of-the-art deep learning techniques, including U-Net and ResNet-based architectures, for achieving high-precision semantic segmentation.

## Getting Started

Follow these instructions to set up and run the project on your local machine. Please note that this project requires a GPU for efficient training.

## Prerequisites

  - Python 3.10.11
  - TensorFlow (2.12.0)
  - NumPy
  - Matplotlib
  - GPU for training (recommended for faster training)

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/ArnabKumarRoy02/Semantic-Segmentation-SDC.git
   cd Semantic-Segmentation-SDC
   ```

2. Create a virtual environment (preferably using Conda):
   ```sh
    conda create -n venv
    conda activate venv
    ```
3. Download the data from [Kaggle](https://www.kaggle.com/datasets/kumaresanmanickavelu/lyft-udacity-challenge)


## Contribution

Contributions are welcome! If you'd like to improve this project or fix any issues, please open a pull request or create an issue.

## License

This project is licensed under the [MIT License](LICENSE).
