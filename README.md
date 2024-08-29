# SIH Hackathon
## Crop Recommendation System

### Project Overview:

The Crop Recommendation System is designed to help farmers choose the most suitable crop based on various environmental and soil conditions. The system uses machine learning algorithms to predict the best crop to grow in a specific location.

###Model Overview

![Crop Model](https://github.com/user-attachments/assets/970c82d7-f0e1-4a6e-ab85-21f5a08c3faa)

### Features:

- Input parameters include soil conditions (NPK levels), temperature, humidity, pH, and rainfall.
- Outputs the recommended crop based on the input conditions.
- Utilizes a trained machine learning model for accurate predictions.

### Technologies Used:

- **Programming Language:** Python
- **Libraries:** Scikit-learn, Pandas, NumPy, Flask for the web interface
- **Model:** GaussianNB (or any other ML algorithm as per implementation)

### Dataset:

The dataset contains information about different crops and their ideal growing conditions. Features include Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall.

### Model Training:

- The dataset is preprocessed to handle missing values and outliers.
- The data is split into training and testing sets.
- A Random Forest Classifier is trained on the dataset.
- The model is evaluated using accuracy and other relevant metrics.

### Web Application:

The Flask framework is used to create a simple web interface. Users can input soil and weather conditions to get a crop recommendation.
