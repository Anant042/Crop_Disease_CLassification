# Potato Disease Classification using CNN

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Requirements](#requirements)
- [How to Use](#how-to-use)
- [Project Structure](#project-structure)


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
- You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/muhammadardiputra/potato-leaf-disease-dataset).

## [Model Architecture](https://github.com/Anant042/Crop_Disease_CLassification/blob/main/model.ipynb).
The model is built using a CNN with the following layers:
- Convolutional Layers
- Max Pooling Layers
- Fully Connected Layers
- Softmax Activation for Classification

## How to Use
1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/potato-disease-classification.git
    cd potato-disease-classification
    ```

2. **Create and Activate a Virtual Environment**
    - Create a virtual environment:
        ```bash
        python -m venv venv
        ```
    - Activate the virtual environment:
        - On Windows:
            ```bash
            .\venv\Scripts\activate
            ```
        - On macOS and Linux:
            ```bash
            source venv/bin/activate
            ```

3. **Install the Required Packages**
    ```bash
    pip install -r requirements.txt
    ```

4. **Prepare the Dataset**
    - Download the dataset from [Kaggle](https://www.kaggle.com/datasets).
    - Place the dataset in the `data/` directory.

5. **Train the Model**
    ```bash
    python scripts/train.py
    ```

6. **Evaluate the Model**
    ```bash
    python scripts/evaluate.py
    ```

7. **Run the Flask Server**
    - Start the Flask server to serve the model:
        ```bash
        python app.py
        ```
    - The server will run on `http://127.0.0.1:5000/` by default.

8. **Make Predictions**
    - You can make predictions by sending a request to the local Flask server:
        ```bash
        curl -X POST -F "file=@path_to_image" http://127.0.0.1:5000/predict
        ```

## Project Structure

