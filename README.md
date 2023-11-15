# Suitable_crop_prediction.yt
## Key Features

- Predicts the most suitable crop based on soil type and climate conditions.
- Utilizes machine learning algorithms to provide accurate recommendations.
- Helps farmers optimize crop selection, fertilizer use, and irrigation methods.
- Contributes to increased yields, reduced waste, and improved profitability in agriculture.

## Getting Started
Objective: The primary goal of the project is to develop a predictive model that can recommend the most suitable crop to grow based on specific soil and climate conditions. This is crucial because choosing the right crop can significantly impact yield and profitability for farmers.

Data Collection: The project involves collecting and analyzing a wide range of data, including soil type, weather patterns, temperature, rainfall, and other relevant variables. This data forms the foundation for creating the predictive model.

Machine Learning: The heart of the Agricultural Production Optimization Engine is a machine learning algorithm that processes the input data and generates crop recommendations. Machine learning models can identify patterns and relationships in the data that may not be apparent through traditional methods.

---

# Agricultural Crop Dataset

## Overview
This dataset offers comprehensive information about various agricultural crops, encompassing their nutrient composition and growth conditions. It encompasses details for 22 different types of crops, each characterized by multiple parameters.

## Content
The dataset consists of the following columns:

- `N`: Nitrogen content (measured in ppm - parts per million)
- `P`: Phosphorus content (measured in ppm)
- `K`: Potassium content (measured in ppm)
- `temperature`: Temperature (measured in Celsius)
- `humidity`: Humidity (measured in %)
- `ph`: Soil pH level
- `rainfall`: Rainfall (measured in mm)
- `label`: Type of crop

## Usage
This dataset serves various agricultural analysis purposes, such as:
- **Predictive Modeling**: Determine suitable crops based on prevailing environmental conditions.
- **Correlation Studies**: Examine relationships between nutrient content and crop types for optimized growth.
- **Environmental Impact Analysis**: Understand the influence of weather factors on crop development.

## Data Statistics
- **Total Entries**: 2200
- **Types of Crops**:
    - rice, maize, jute, cotton, coconut, papaya, orange, apple, muskmelon, watermelon, grapes, mango, banana, pomegranate, lentil, blackgram, mungbean, mothbeans, pigeonpeas, kidneybeans, chickpea, coffee
    - Each crop type contains 100 entries.

## Model Performance Analysis

### Model Comparison
The dataset has been subjected to multiple classification algorithms, each providing distinct accuracy results.

#### Logistic Regression
- **Average Accuracy (Cross-Validation):** 96.85%
- **Algorithm Description:** Logistic Regression with a maximum iteration of 10,000.

#### Random Forest Classifier
- **Average Accuracy (Cross-Validation):** 99.39%
- **Algorithm Description:** Utilized the Random Forest Classifier with a random state of 1.

#### K-Nearest Neighbors (KNN)
- **Average Accuracy (Cross-Validation):** 97.58%
- **Algorithm Description:** Employed the K-Nearest Neighbors Classifier.

#### Support Vector Classifier (SVC) with Linear Kernel
- **Average Accuracy (Cross-Validation):** 98.18%
- **Algorithm Description:** Utilized Support Vector Classifier with a linear kernel.

### Best Performing Model: Random Forest Classifier
The Random Forest Classifier exhibited the highest accuracy among all models, attaining an average cross-validation accuracy of 99.39%.

#### Performance Metrics
- **Training Accuracy:** 100%
- **Cross-Validation Accuracy:** 99%
- **Testing Accuracy:** 100%

## Average Feature Values
For reference, the dataset's average feature values are as follows:
- `N`: 50.55
- `P`: 53.36
- `K`: 48.15
- `Temperature`: 25.62°C
- `Humidity`: 71.48%
- `pH`: 6.47
- `Rainfall`: 103.46 mm

## Usage of Results
The high accuracy achieved by the Random Forest Classifier suggests its suitability for predicting crop types based on the given features. Users can leverage this model for precise crop type prediction in agricultural scenarios.

## Data Source
The original dataset was obtained from [Kaggle].

