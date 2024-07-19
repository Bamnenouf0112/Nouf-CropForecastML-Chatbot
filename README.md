# Nouf-CropForecastML-Chatbot
# CropForecastML

*CropForecastML* is a machine learning project designed to predict agricultural crop yields using advanced predictive analytics. The goal is to provide accurate forecasts based on historical data, helping farmers and agricultural professionals make informed decisions and optimize their farming practices.

URL-https://nouf-cropforecastml-chatbot.streamlit.app/

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Models](#models)
- [Contributing](#contributing)

## Project Overview
This project leverages machine learning techniques to predict crop yields. By analyzing historical agricultural data, the system generates forecasts that can assist in planning and improving agricultural productivity. The project includes data preprocessing, model training, and evaluation.

## Features
- Predict crop yields based on historical data
- Support for various machine learning models
- Data visualization and analysis
- Easy integration with data sources

## Installation
1. *Clone the repository:*
   bash
   git clone https://github.com/Bamnenouf0112/Nouf-CropForecastML-Chatbot.git
   cd CropForecastML

2. *Install the required packages:*
   bash
   pip install -r requirements.txt
   The required packages that you should mention in your project README file are the dependencies needed to run your project. These may include:

1. Programming languages (e.g., Python, Java, Node.js)
2. Libraries (e.g., NumPy, pandas, React)
3. Frameworks (e.g., Django, Flask, Express.js)
4. Databases (e.g., MySQL, MongoDB, PostgreSQL)
5. Testing frameworks (e.g., JUnit, PyUnit, Jest)
6. Build tools (e.g., Webpack, Gulp, Maven)
7. Version control systems (e.g., Git, SVN)
8. Operating system dependencies (e.g., Linux, Windows, macOS)
9. Other software dependencies (e.g., graphics drivers, external libraries)
   

## Usage
Start the application by running:
   
    ```bash
       streamlit run WEB APP.py

   Input Features
    Year: Year for which crop yield prediction is required.
    Average Rainfall (mm per year): Annual average rainfall in millimeters.
    Pesticides (tonnes): Quantity of pesticides used in tonnes.
    Average Temperature (°C): Average temperature in degrees Celsius.
    Area: Select the geographic area from the provided options.
    Item: Choose the type of crop from the available options.

   Example
   After launching the Streamlit app, input the required features and click "Predict" to view the predicted Crop yield.
   

## Models
The prediction model used is a Decision Tree Regressor trained on historical crop yield data. The dtr (1).pkl file contains the model parameters and is loaded during runtime to predict crop yields based on user inputs..

## Contributing
We welcome contributions to this project! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your fork.
5. Open a pull request with a clear description of your changes.

## Contact
For any questions or feedback, please contact [noufbamne@gmail.com].

---

Feel free to adjust the sections according to your project's specifics!
