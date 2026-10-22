# daily-rainfall-prediction-lstm
Daily rainfall prediction using LSTM and the IMD Rainfall Dataset 2022.
# Daily Rainfall Prediction Using LSTM

## Project Description
This project predicts daily rainfall using the IMD Rainfall Dataset 2022. An LSTM deep learning model learns rainfall patterns from the previous seven days to predict the next day's rainfall.

## Objectives
- Preprocess rainfall data and handle missing values.
- Normalize rainfall measurements.
- Create time-series sequences using the previous seven days.
- Train an LSTM model to predict rainfall.
- Evaluate performance using MAE and RMSE.

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- TensorFlow/Keras
- LSTM Neural Network

## Model Architecture
LSTM (64 units) → Dropout (0.2) → Dense (32, ReLU) → Dense (1)

## Loss Function
Mean Squared Error (MSE)

## Optimizer
Adam

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Dataset
IMD Rainfall Dataset 2022 from Kaggle:
https://www.kaggle.com/datasets/ankitgaikar1995/imd-rainfall-dataset-2022

## How to Run
1. Open the notebook in Google Colab.
2. Upload the rainfall CSV dataset when prompted.
3. Select a district and run the notebook cells in order.
4. View the evaluation metrics, graphs, and future predictions.

## Conclusion
The project demonstrates the use of LSTM for daily rainfall time-series prediction.
