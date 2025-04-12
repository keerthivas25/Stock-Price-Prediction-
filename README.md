# Stock Price Prediction

## Project Description: Advanced Machine Learning Models for Time Series Forecasting

This project focuses on implementing and training advanced machine learning models to predict stock prices with high accuracy. The models used include:

- **XGBoost (Extreme Gradient Boosting):** A robust ensemble learning method known for handling large datasets and complex patterns efficiently.
- **LSTM (Long Short-Term Memory Networks):** A type of recurrent neural network (RNN) designed to capture temporal dependencies in sequential data, making it ideal for time series forecasting.
- **WGAN-GP (Wasserstein GAN with Gradient Penalty):** An advanced generative adversarial network architecture that generates realistic synthetic data by learning the underlying distribution of stock prices.

---

## Data Preprocessing Pipelines

To optimize model performance, comprehensive data preprocessing pipelines were implemented:

- **Normalization:** Standardized data to ensure all features are on the same scale, improving convergence for gradient-based algorithms.
- **Dataset Splitting:** Divided data into training, validation, and test sets to evaluate performance accurately and prevent overfitting.
- **Feature Engineering with Fourier Transforms:** Extracted meaningful features using Fourier transforms to capture periodic patterns and trends, enhancing predictive power.

---

## Hyperparameter Optimization

Rigorous hyperparameter tuning techniques were employed to maximize model performance:

- **GridSearchCV for XGBoost:** Exhaustively searched through a parameter grid to find the optimal hyperparameters.
- **Custom Training Loops for GANs:** Tailored training procedures for WGAN-GP, including strategies for adjusting learning rates, alternating optimization of generator and discriminator, and incorporating gradient penalties for stable training.

---

## Model Evaluation and Visualization

Model predictions were evaluated using detailed metrics and visualizations:

- **RMSE (Root Mean Square Error):** Measured prediction accuracy by comparing predicted values with actual stock prices.
- **Detailed Plots:** Visualized predictions against actual stock prices over time to assess model reliability and performance.

These techniques significantly improved the accuracy and reliability of stock price forecasts, demonstrating the potential of machine learning in financial time series forecasting.

---

## Final Results

### LSTM  
<img width="408" alt="LSTM Predictions" src="https://github.com/user-attachments/assets/afd41c23-85b7-44c0-99d0-77df75a39552">

### XGBoost  
<img width="452" alt="XGBoost Predictions" src="https://github.com/user-attachments/assets/86997036-5e7f-4ca6-9945-35f2ec4bcef7">

### WGAN-GP  
<img width="452" alt="WGAN-GP Predictions" src="https://github.com/user-attachments/assets/72fe858a-d595-4fa7-a83f-02b2efe2aff3">

---

This project provides a strong foundation for further advancements in financial forecasting and showcases the effectiveness of machine learning in predicting stock prices.
