# Plant Disease Prediction

A machine learning project that predicts plant disease from leaf images. The goal is to help identify plant health issues early using image-based classification.

## Overview
This project applies supervised machine learning to classify leaf images into healthy and diseased categories. The notebook walks through data loading, preprocessing, model training, and evaluation.

## Tech Stack
- Python  
- Jupyter Notebook  
- NumPy  
- Pandas  
- Matplotlib / Seaborn  
- scikit-learn  

## Dataset
Leaf image dataset used for plant disease classification.  


## Approach
1. Load and explore the dataset  
2. Preprocess images (resize and normalize)  
3. Train a classification model  
4. Evaluate performance using accuracy and confusion matrix  
5. Test predictions on sample images  

## Results
- Accuracy: 90

Key observations:
- Model performs well on clear images
- Some confusion between visually similar disease classes
- Dataset imbalance impacts certain predictions

## How to Run

### Run locally
```bash
git clone https://github.com/AnishShirodkar/Plant_Disease_Prediction.git
cd Plant_Disease_Prediction
pip install -r requirements.txt
jupyter notebook
