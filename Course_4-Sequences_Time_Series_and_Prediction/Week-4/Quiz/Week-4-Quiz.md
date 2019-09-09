#### 1. How do you add a 1 dimensional convolution to your model for predicting time series data?
##### Ans: Use a Conv1D layer type
#### 2. What’s the input shape for a univariate time series to a Conv1D? 
##### Ans: [None, 1]
#### 3. You used a sunspots dataset that was stored in CSV. What’s the name of the Python library used to read CSVs?
##### Ans: CSV
#### 4. If your CSV file has a header that you don’t want to read into your dataset, what do you execute before iterating through the file using a ‘reader’ object?
##### Ans: next(reader)
#### 5. When you read a row from a reader and want to cast column 2 to another data type, for example, a float, what’s the correct syntax?
##### Ans: float(row[2]) 
#### 6. What was the sunspot seasonality?
##### Ans: 11 or 22 years depending on who you ask
#### 7. After studying this course, what neural network type do you think is best for predicting time series like our sunspots dataset?
##### Ans: 
- Convolutions
- DNN
- RNN / LSTM
- A combination of all of the above
#### 8. Why is MAE a good analytic for measuring accuracy of predictions for time series?
##### Ans: It doesn’t heavily punish larger errors like square errors do