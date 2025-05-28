# Rock-Scissors-Paper Image Detection ✊✌️✋


---

## Project Overview 📖

This project implements a Convolutional Neural Network (CNN) to detect and classify images of hand gestures representing Rock, Scissors, and Paper. It uses a dataset of 8,774 labeled images and applies image preprocessing, augmentation, and deep learning to accurately recognize these gestures.

The model can be applied to interactive games, gesture recognition systems, and educational tools requiring real-time hand gesture classification.

---

## Dataset 📂

The dataset contains 8,774 images categorized into three classes:

- Rock
- Paper
- Scissors

Images are sourced from the [Rock-Paper-Scissors dataset](https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip).

---

## Features ⚙️

- Image preprocessing with resizing and normalization
- Real-time data augmentation using Keras `ImageDataGenerator`
- Deep CNN architecture for feature extraction and classification
- Model training with Adam optimizer and categorical cross-entropy loss
- Validation and evaluation with accuracy metric
- Model saving for future inference
