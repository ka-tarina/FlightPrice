# FlightPrice

Flight Price Prediction

This project aims to predict the prices of airline flights based on various features such as airline, route, duration, departure time, etc. The prediction model is built using machine learning algorithms and is trained on a dataset of historical flight data.

Table of Contents

    Installation
    Dataset
    Usage
    Model Training
    Evaluation
    

Installation

    Clone the repository:

    git clone https://github.com/ka-tarina/FlightPrice.git


Install the required dependencies:

    pip install -r requirements.txt

Dataset

The dataset used for this project is located in the data directory. It contains historical flight data including various features such as airline, route, duration, departure time, and the corresponding flight prices. The dataset has been preprocessed and cleaned for analysis.

Usage

The main project file is flight_prediction.ipynb, which is a Jupyter Notebook containing the code for data preprocessing, feature engineering, model training, and evaluation.

To run the notebook:

    Launch Jupyter Notebook:

    jupyter notebook

    Open the flight_prediction.ipynb file in your browser.

    Execute the cells in the notebook sequentially to perform data analysis, model training, and prediction.

Model Training

In the notebook, various machine learning algorithms have been implemented for flight price prediction. The chosen algorithm is Random Forest, which is trained on the dataset using the preprocessed features.

Evaluation

The performance of the trained model is evaluated using suitable evaluation metrics such as mean squared error (MSE), mean absolute error (MAE), and R-squared score. These metrics provide an assessment of the model's accuracy in predicting flight prices.
