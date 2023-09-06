# Air Quality Index (AQI) Prediction Model

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [License](#license)

## Introduction

The Air Quality Index (AQI) Prediction Model is a machine learning project designed to predict the air quality index at a specific location based on historical air quality data and various environmental features. This project aims to provide valuable insights into air quality trends and enable better decision-making regarding environmental conditions. For instance, we use Banglore air quality data in this notebook.

## Project Overview

- **Data Collection**: We gathered air quality data from various sources, including government agencies, sensors, and weather stations.

- **Data Preprocessing**: Extensive data preprocessing was performed, including data cleaning, feature engineering, and handling missing values.

- **Feature Selection**: We selected relevant features that have a significant impact on air quality prediction.

- **Model Development**: We developed machine learning models, including regression algorithms, to predict the AQI based on the selected features.

- **Model Evaluation**: The models were evaluated using various metrics, such as Mean Absolute Error (MAE) and Root Mean Square Error (RMSE), to assess their performance.
<!-- 
- **Deployment**: The best-performing model is deployed as a web service/API to make real-time AQI predictions. -->

## Dataset

<!-- We used a comprehensive dataset for training and testing our models. This dataset includes the following information:

- Air quality measurements (PM2.5, PM10, CO, SO2, NO2, O3)
- Meteorological data (temperature, humidity, wind speed, etc.)
- Geographic information (latitude, longitude)
- Date and time stamps -->

The dataset is available [here](https://github.com/92-vasim/datasets/blob/main/aqi-dataset/air%20quality%20data.csv).

## Requirements

To run this project locally or deploy it, you need the following dependencies:

- Python 3.6+
- Jupyter Notebook
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- XGBoost
- CatBoost 

You can install these dependencies using the instructions in the next section.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/92-vasim/air-quality-index-prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd air-quality-prediction
   ```

3. Create a virtual environment (recommended):

   ```bash
   python -m venv .venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

5. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Data Preprocessing**: Before training the model, preprocess the data by running the Jupyter Notebook in the `notebooks` directory. Follow the instructions provided in the notebook.

2. **Train the Model**: Train the AQI prediction model by running the Jupyter Notebook.

3. **Make Predictions**: Use the trained model to make air quality predictions for a given set of features.

## Model Performance

Our model achieved the following performance metrics on the test dataset:

- Mean Absolute Error (MAE): X.XX
- Root Mean Square Error (RMSE): X.XX

These metrics demonstrate the accuracy of the AQI predictions made by our model.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---