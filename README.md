# Jena Climate Temperature Prediction
A machine learning project that utilizes LSTM (Long Short-Term Memory) networks to predict temperatures based on historical climate data from the Jena Climate dataset.

## Project Overview
- Dataset: [Jena Climate dataset](https://www.kaggle.com/datasets/mnassrib/jena-climate), containing 14 different weather features recorded every 10 minutes from 2009 to 2016.
- Objective: Predict the temperature based on past weather features using sequence models.
- Model: LSTM-based deep learning model built with TensorFlow and Keras.

## Features
The dataset contains the following weather features:

- Atmospheric Pressure (p (mbar))
- Temperature in Celsius (T (degC))
- Dew Point Temperature (Tdew (degC))
- Relative Humidity (rh (%))
- Specific Humidity (VPmax (mbar))
- Vapor Pressure (VPact (mbar))
- Saturation Vapor Pressure (VPdef (mbar))
- Air Density (sh (g/kg))
- Water Vapor Concentration (H2OC (mmol/mol))
- Vertical Wind Speed (wv (m/s))
- Horizontal Wind Speed (max. wv (m/s))
- Wind Direction in Degrees (wd (deg))

## Real-world Testing
For real-world testing, collect weather data for a specific day, preprocess it in the same manner as the training data, and pass it to the trained model to predict temperatures. After the day passes, you can compare the model's predictions to the actual temperatures to assess its performance.
