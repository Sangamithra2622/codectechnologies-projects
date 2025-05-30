## 🔍 Machine Learning Internship Projects by Sangamithra

This repository includes two distinct machine learning projects developed during my internship, showcasing applications of both traditional and deep learning models.

---

### 1. 📊 *Stock Market Trend Estimator*

*Overview:*
This project focuses on forecasting stock market trends by utilizing historical stock data. A Linear Regression model is employed to estimate future stock prices based on past performance. The dataset is dynamically pulled using the yfinance API, and exploratory data analysis is conducted to understand the behavior of the time series.

*Tools & Libraries:*

* Python
* yfinance
* pandas
* matplotlib
* scikit-learn

*Execution Steps:*

1. Launch stock_price_predictor.ipynb on Google Colab.
2. Execute the notebook cells in order.
3. You can input different ticker symbols (e.g., 'AAPL', 'GOOG') to test predictions for other stocks.

*Highlights:*

* Real-time data acquisition
* Linear regression model for trend prediction
* Visual comparison of real vs. predicted values

---

### 2. 🧠 *Deep Learning-Based Digit Classifier*

*Project Summary:*
This application leverages a Convolutional Neural Network (CNN) to identify handwritten digits from the MNIST dataset. Designed using TensorFlow and Keras, the model demonstrates efficient learning and high accuracy. The notebook also includes visual output to verify predictions on unseen test images.

*Frameworks & Resources:*

* Python
* TensorFlow / Keras
* MNIST dataset
* matplotlib

*How to Use:*

1. Open handwritten_digit_recognizer.ipynb in Google Colab.
2. Run all cells from top to bottom.
3. The model will train and evaluate performance on test data.
4. View the predicted outputs alongside the true labels.

*Notable Features:*

* CNN architecture optimized for image classification
* Performance metrics and accuracy visualization
* Real-time prediction previews of test digits
