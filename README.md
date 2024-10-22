# Cats vs Dogs Image Classification using SVM

## Project Overview

This project implements a **Support Vector Machine (SVM)** algorithm to classify images of cats and dogs. The dataset used in this project is sourced from the Kaggle "Dogs vs. Cats" competition, which contains thousands of labeled images of cats and dogs. This model aims to help distinguish between the two types of animals using image classification.

## Dataset

The dataset is sourced from Kaggle: [Dogs vs. Cats Dataset](https://www.kaggle.com/c/dogs-vs-cats/data). It contains images with the following characteristics:

- **Cat Images**: Labeled as cats (0).
- **Dog Images**: Labeled as dogs (1).

Each image is resized and converted to grayscale for feature extraction and classification purposes.

## Prerequisites

Before running the project, install the required dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib opencv-python

## Steps to Run the project 
1. Clone the repository: 
```bash 
git clone https://github.com/Rohan10112004/dogs-vs-cats.git
cd dogs-vs-cats

2. Download the dataset from Kaggle and extract it to the data/ directory. 

3. Preprocess the dataset by resizing images and converting them to grayscale for SVM compatibility. 

4. Run the Python script to train and evaluate the SVM model. 
