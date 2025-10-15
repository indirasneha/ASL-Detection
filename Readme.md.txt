# American Sign Language (ASL) Detection

## Project Description
This project uses Convolutional Neural Networks (CNN) to detect 29 ASL signs (A-Z + SPACE, DELETE, NOTHING) from hand images.

## Dataset
- Source: [ASL Alphabet Dataset on Kaggle](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)

## Features
- CNN-based image classification
- Data augmentation for bottom-performing classes
- Fine-tuning and evaluation
- Saved trained model for deployment

## Tech Stack
- Python, TensorFlow/Keras, OpenCV, NumPy, Matplotlib

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Open `notebooks/ASL_Detection.ipynb` in Jupyter Notebook
3. Run all cells to train/evaluate model
