# LSTM-Views-Prediction
This repository contains a machine learning model built to forecast the number of views for TikTok's biggest influencers over the next 30 days. The model employs Long Short-Term Memory (LSTM) neural networks, a powerful architecture for sequence prediction, to capture temporal dependencies and predict aggregated daily views.

Contents:
Data Collection and Preprocessing:

Raw data includes influencer details such as ID, category, views, likes, and followers.
Data cleaning procedures, including whitespace removal and normalization, are applied to prepare the dataset for training.
Model Training and Architecture:

The LSTM model is defined with two layers of 50 units each, incorporating dropout regularization for improved robustness.
Early stopping is implemented to mitigate overfitting concerns during training.
Input/Output Structure:

A sequence length of 10 is chosen to consider the last 10 aggregated daily views when predicting the next value.
The model is designed for single-step forecasting, estimating the next aggregated view based on the preceding 10 views.
Evaluation and Performance Metrics:

The model's performance is evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE) on both training and test sets.
The Metric results suggest good generalization to the test set. 

Forecasting Future Views:

The model provides a forecast for the total number of views in the next 30 days, aiding in cloud computing cost planning.
Limitations:

Acknowledges limitations such as dataset size, noise sensitivity, and the black-box nature of LSTM models.
Usage:

Instructions on how to use the model for forecasting future views.
Guidelines for customization and experimenting with hyperparameters.
Contributing:

Guidelines for contributing to the project, including bug reports, feature requests, and pull requests.
License:

Information about the license under which the code is distributed.
Getting Started:
Clone the Repository:

bash
Copy code
git clone https://github.com/aurill/LSTM-Views-Prediction.git
cd LSTM-Views-Prediction
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Train the Model:

Follow the instructions in the training notebook to train the LSTM model.
Forecast Future Views:

Use the provided forecasting script to predict future views.
License:
This project is licensed under the MIT License.

Contributions:
Contributions are welcome! Feel free to open issues, submit feature requests, or contribute code through pull requests.

Acknowledgments:
This project is inspired by the need for accurate forecasting in the dynamic world of influencer marketing on TikTok. We thank the community for their valuable feedback and contributions.
