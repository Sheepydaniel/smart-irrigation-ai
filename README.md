# Smart Irrigation AI

Machine learning project focused on predicting crop irrigation needs using environmental sensor data.

## Live Demo

Try the deployed Smart Irrigation AI dashboard on Hugging Face Spaces:

[Smart Irrigation AI Dashboard](https://huggingface.co/spaces/Sheepydaniel/smart-irrigation-ai-v2)

## Overview

This project explores how machine learning can support smarter irrigation decisions and sustainable agriculture.

The system uses environmental sensor data such as soil moisture, temperature, rainfall, humidity, sunlight exposure, and NDVI vegetation index to predict whether irrigation is recommended.

The project includes both:

- a research-style Kaggle notebook for model exploration and evaluation
- a deployed interactive dashboard for real-time irrigation prediction

## Project Features

- Smart irrigation prediction
- Environmental sensor input analysis
- Machine learning model comparison
- F1 score evaluation
- Feature importance analysis
- Water stress scoring
- Interactive Hugging Face dashboard
- Crop condition recommendations

## Models Tested

The notebook compares multiple machine learning models:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

Logistic Regression achieved the strongest performance on the dataset, likely because the engineered environmental features created a highly separable irrigation decision boundary.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Streamlit
- Hugging Face Spaces
- Kaggle
- GitHub

## Dataset Features

The model uses the following environmental inputs:

| Feature | Description |
|---|---|
| `soil_moisture_%` | Soil moisture percentage |
| `temperature_C` | Environmental temperature |
| `rainfall_mm` | Rainfall measurement |
| `humidity_%` | Atmospheric humidity |
| `sunlight_hours` | Daily sunlight exposure |
| `NDVI_index` | Vegetation health indicator |

## Results

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Cross-validation
- Feature importance analysis

The deployed dashboard allows users to adjust sensor inputs and receive an irrigation recommendation with a watering probability and water stress score.

## Future Improvements

Planned upgrades include:

- real-time weather API integration
- live IoT sensor support
- larger agricultural dataset training
- crop-specific irrigation models
- historical trend visualization
- automated irrigation scheduling
- AI agent-based farm management

## Goal

The goal of this project is to explore how AI and machine learning systems can support precision agriculture, improve water efficiency, and assist smarter environmental resource management.
