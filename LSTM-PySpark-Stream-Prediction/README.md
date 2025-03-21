# LSTM PySpark Stream Prediction
This project leverages LSTM (Long Short-Term Memory) networks for time-series sales prediction while utilizing PySpark Streaming for real-time data processing.
## Data 
The used data is [Store Item](https://www.kaggle.com/code/dimitreoliveira/deep-learning-for-time-series-forecasting) on kaggle.
## Technologies
+ **Deep Learning**: `TensorFlow`/`Keras`
+ **Big Data & Streaming**: Apache `PySpark`
+ **Data Processing & Analysis**: `Pandas`, `NumPy`, `Scikit-learn`
+ **Visualization**: `Matplotlib`, `Plotly`
## Steps
1. Data Preprocessing:
    - Load and clean the dataset using PySpark.
    - Split data into training and testing sets.
2. Model Development:
    - Build an LSTM model using Keras.
    - Train the model on historical sales data.
3. Evaluation & Visualization:
    - Evaluate model performance using MSE (Mean Squared Error).
    - Visualize predictions with Matplotlib & Plotly.
4. Real-Time Streaming & Prediction:
    - Implement PySpark Streaming to process incoming sales data.
    - Dynamically update predictions based on new inputs.