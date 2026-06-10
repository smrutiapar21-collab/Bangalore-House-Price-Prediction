# Real Estate Price Prediction

## Overview

Real Estate Price Prediction is a Machine Learning web application that predicts house prices in Bangalore based on key property features such as location, total square footage, number of bedrooms (BHK), and bathrooms. The project combines data preprocessing, model training, and a user-friendly web interface to provide accurate property price estimates.
<img width="1899" height="1002" alt="image" src="https://github.com/user-attachments/assets/44faf8d5-46a3-4b48-aef6-480b6b042087" />

## Features

* Predicts house prices using a trained Machine Learning model
* Interactive web interface for user input
* Data preprocessing and feature engineering
* Model training and evaluation using Scikit-learn
* REST API integration using Flask
* Real-time prediction generation

## Tech Stack

### Machine Learning

* Python
* Pandas
* NumPy
* Scikit-learn

### Backend

* Flask

### Frontend

* HTML
* CSS
* JavaScript

### Data Visualization

* Matplotlib

## Project Structure

```text
Real-Estate-Price-Prediction/
│
├── client/
│   ├── app.html
│   ├── app.css
│   └── app.js
│
├── model/
│   ├── Bangalore_price_prediction.ipynb
│   ├── bengaluru_house_prices.csv
│   └── columns.json
│
├── server/
│   ├── server.py
│   ├── util.py
│   └── artifacts/
│       ├── bangalore_home_prices_model.pickle
│       └── columns.json
│
└── README.md
```

## Dataset

The project uses the Bengaluru House Price Dataset containing property details such as:

* Location
* Total Square Feet
* Number of Bedrooms (BHK)
* Number of Bathrooms
* Price

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Outlier Detection and Removal
5. Model Training
6. Model Evaluation
7. Model Serialization
8. Web Application Deployment

## Model Performance

The model was trained using Scikit-learn regression techniques and evaluated using cross-validation and performance metrics to ensure reliable predictions.

## Installation

### Clone the Repository

```bash
git clone https://github.com/smrutiapar21-collab/Bangalore-House-Price-Prediction.git
cd Bangalore-House-Price-Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Flask Server

```bash
python server/server.py
```

### Open the Application

Open `client/app.html` in your browser.

## Future Enhancements

* Deploy the application on cloud platforms
* Improve model accuracy with advanced algorithms
* Add interactive visualizations and analytics
* Support multiple cities and property types
* Build a responsive mobile-friendly interface

## Author

**Smruti Apar Behera**

Aspiring Software Engineer | Machine Learning Enthusiast | Python Developer


