# Microsoft Stock Prediction and Forecasting using LSTMs

Objective
The goal of this project is to develop a time series forecasting model using Long Short-Term Memory (LSTM) networks to predict Microsoft's stock closing prices based on historical data.

Dataset
The dataset contains 9082 rows of historical stock prices for Microsoft, spanning from 1986 to March 23, 2022.
It includes columns such as date, open, high, low, close, adjusted close, and volume.
The focus is on using only the date and closing price columns for forecasting.

Data Preprocessing
Load the dataset using pandas and extract the necessary columns (date, close).
Convert the date column from an object (string) to a datetime format.
Set the date column as the index to properly structure the time series data.
Normalize the closing price using Min-Max Scaling to improve model performance.
Split the data into training and testing sets.

Model Architecture
Implement an LSTM-based neural network using TensorFlow and Keras.
The architecture consists of:
LSTM layers to capture sequential dependencies.
Fully connected (Dense) layers to output predictions.
Dropout layers to prevent overfitting.

Training and Evaluation
Train the LSTM model using the historical closing prices.
Evaluate the model using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).
Visualize the actual vs. predicted stock prices.

Future Enhancements
Incorporate additional features such as trading volume, technical indicators, and external market trends.
Implement hyperparameter tuning for optimizing model performance.
Explore other deep learning architectures, such as GRUs and Transformer-based models, for better accuracy.

![image](https://github.com/user-attachments/assets/baaf2e68-a4b2-4a25-84db-2ef163012d07)


![image](https://github.com/user-attachments/assets/bc69e19e-7860-45a7-8a17-009c61bf3a69)


![image](https://github.com/user-attachments/assets/6ec97545-69cd-46a1-9373-1f9c74b5a0e8)


![image](https://github.com/user-attachments/assets/0eb54dcf-10f2-4867-b6e8-a089977fec0f)


![image](https://github.com/user-attachments/assets/4f7e615e-8c2a-4a23-8421-8a9e29676a0c)


![image](https://github.com/user-attachments/assets/e206b610-2225-47cf-a0e9-420732284807)
