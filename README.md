# Airline Customer Satisfaction Predictor

This project implements a machine learning model to predict airline customer satisfaction using the LightGBM algorithm. The model is deployed using Streamlit for interactive use.

## Features
- Predicts customer satisfaction based on features such as flight details, service ratings, and customer information.
- Uses the LightGBM algorithm, known for its high efficiency and accuracy in handling large datasets.
- Deployed on Streamlit for a simple web interface to input data and get predictions.

## Technologies Used
- **Machine Learning**: LightGBM
- **Web App**: Streamlit
- **Programming Language**: Python
- **Data Science Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib
- **Modeling Libraries**: LightGBM

## Setup Instructions

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/airline-customer-satisfaction.git

2.) Install the required dependencies:
pip install -r requirements.txt


3.) Run the Streamlit app:
  streamlit run app.py

4.) The app will launch in your default web browser. You can input customer data to see the satisfaction prediction.

## Model Training
1.) The model is trained using the LightGBM algorithm, which efficiently handles large datasets and supports parallel learning.

2.) Features such as flight type, service ratings, and customer demographics were used to train the model.

3.) Evaluation metrics such as accuracy, precision, recall, and F1-score were used to assess model performance.

## Results 
The model achieves an accuracy of 94%
It's optimized for performance and can handle a variety of input data types for prediction.
