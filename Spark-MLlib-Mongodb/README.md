# Spark-MLlib-Mongodb
## Data 
The used dataset is [Room Occupancy detection](https://www.kaggle.com/datasets/kukuroo3/room-occupancy-detection-data-iot-sensor)      
Data is stored as collections within a MongoDB Atlas cloud service.       
## Python code 
### Libraries 
+ `pymongo`: for interacting with MongoDB
+ `pyspark`: for Apache Spark functionalities
### Functionality
+ Connects to a MongoDB database and retrieves sensor readings (temperature, humidity, light, CO2, humidity ratio) along with occupancy labels.               
+ Transforms the data into a Spark DataFrame suitable for machine learning.        
+ Uses a VectorAssembler to combine relevant features into a single vector.         
+ Splits the data into training and testing sets.         
+ Trains a Linear Regression model to predict occupancy based on the sensor data.        
+ Evaluate the model's performance using Root Mean Squared Error (RMSE).          
