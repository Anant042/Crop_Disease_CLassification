# Potato Disease Classification using CNN

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Requirements](#requirements)
- [How to Use](#how-to-use)
- [Project Structure](#project-structure)
- [Results](#results)
- [Examples](#examples)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project uses Convolutional Neural Networks (CNNs) to classify potato leaves into three categories:
- **Early Blight**
- **Late Blight**
- **Healthy**

## Dataset
The dataset consists of images of potato leaves affected by:
- Early Blight
- Late Blight
- Healthy leaves
You can download the dataset from [Kaggle](https://www.kaggle.com/datasets](https://www.kaggle.com/datasets/muhammadardiputra/potato-leaf-disease-dataset).

## Model Architecture
The model is built using a CNN with the following layers:
- Convolutional Layers
- Max Pooling Layers
- Fully Connected Layers
- Softmax Activation for Classification

## Requirements
To run this project, ensure you have the following dependencies installed:
```bash
pip install -r requirements.txt
