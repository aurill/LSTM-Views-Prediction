# LSTM-Views-Prediction
This repository contains a machine learning model built to forecast the number of views for TikTok's biggest influencers over the next 30 days. The model employs Long Short-Term Memory (LSTM) neural networks, a powerful architecture for sequence prediction, to capture temporal dependencies and predict aggregated daily views.

## **Overview**
This repository houses a machine learning model designed to forecast the future views of TikTok's biggest influencers using Long Short-Term Memory (LSTM) neural networks. The model aims to predict aggregated daily views for the next 30 days, providing valuable insights for effective cloud computing cost planning.

This is crucial so that TikTok can plan for cloud computing costs (more users more processing power needed). Therefore they need to know now before our systems crash. How can this be done.

## **Table of Contents**

- Background
- Getting Started
- Prerequisites
- Installation
- Data Collection and Preprocessing
- Model Architecture
- Training the Model
- Evaluation and Performance Metrics
- Forecasting Future Views
- Limitations
- Usage
- Contributing
- License
- Acknowledgments

## **Background**

In the dynamic world of influencer marketing on TikTok, accurately predicting future views is crucial for effective cloud computing cost planning. This project utilizes LSTM neural networks to capture temporal dependencies and patterns in historical aggregated daily views data, enabling the model to make informed predictions.

## **Getting Started**

**Prerequisites**
Python 3.12.0
Google Colab (for model training)
Required Python packages (install using pip install -r requirements.txt)

## **Installation**
Clone the repository:
bash
Copy code
git clone https://github.com/aurill/LSTM-Views-Prediction.git
cd LSTM-Views-Prediction

## **Data Collection and Preprocessing**

The dataset includes influencer details such as ID, category, views, likes, and followers. Data cleaning procedures, normalization, and sequence preparation are conducted to ensure the dataset is suitable for training.

## **Model Architecture**

The LSTM model consists of two layers of 50 units each, incorporating dropout regularization to enhance robustness. A sequence length of 10 is chosen to consider the last 10 aggregated daily views when predicting the next value.

## **Training the Model**
The model is trained using the provided Jupyter Notebook. Early stopping and dropout regularization techniques are employed to mitigate overfitting.

## **Evaluation and Performance Metrics**

The model's performance is evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE) on both training and test sets. Results suggest good generalization to the test set.

## **Forecasting Future Views**

The model provides a forecast for the total number of views in the next 30 days, aiding in cloud computing cost planning.

## **Limitations**

Acknowledges limitations such as dataset size, noise sensitivity, and the black-box nature of LSTM models.

## **Usage**

Instructions on how to use the model for forecasting future views, along with guidelines for customization and experimenting with hyperparameters.

## **Contributing**

Contributions are welcome! Open issues, submit feature requests, or contribute code through pull requests.

## **License**

This project is licensed under the MIT License.

## **Acknowledgments**

This project is inspired by the need for accurate forecasting in influencer marketing on TikTok. We thank the community for their valuable feedback and contributions.

Feel free to customize this template further to include specific details about your project, additional sections, or any other information you find relevant.
