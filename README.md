# Medicinal Plant Leaf Classification Project

This repository contains the final-year project notebook for **Medicinal Plant Leaf Image Classification** using deep learning.  

## Project Overview
- **Goal:** Classify different medicinal plant species based on leaf images.
- **Dataset:** Segmented medicinal leaf images (Kaggle dataset).
- **Approach:**
  - Data preprocessing and augmentation
  - Resnet50 Model 
  - Performance evaluation using accuracy, confusion matrix, and visualization
  - Saving trained model and artifacts for reuse

## Technologies & Libraries
- Python
- TensorFlow/Keras
- scikit-learn
- pandas, numpy
- matplotlib, seaborn, plotly
- PIL (image handling)

## Project Structure
- `final-year-project.ipynb` — Main notebook with the full workflow
- `Model/model.h5` — Trained deep learning model (saved)
- `artifacts/class_names.npy` — Numpy file with class labels
- Example dataset path: `/kaggle/input/medicinal-plant/Segmented Medicinal Leaf Images/...`

## Results
- The trained model successfully classifies medicinal plants from leaf images.
- Evaluation includes accuracy metrics and visualizations.

## Future Work

- Deploy as a web or mobile app for real-time plant recognition.
- Expand dataset to cover more species.

