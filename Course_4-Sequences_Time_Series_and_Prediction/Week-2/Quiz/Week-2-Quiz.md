#### 1. What is a windowed dataset?
##### Ans: A fixed-size subset of a time series 
#### 2. What does ‘drop_remainder=true’ do?
##### Ans: It ensures that all rows in the data window are the same length by cropping data
#### 3. What’s the correct line of code to split an n column window into n-1 columns for features and 1 column for a label
##### Ans: dataset = dataset.map(lambda window: (window[:-1], window[-1:]))
#### 4. What does MSE stand for?
##### Ans: Mean Squared error
#### 5. What does MAE stand for?
##### Ans: Mean Absolute Error
#### 6. If time values are in time[], series values are in series[] and we want to split the series into training and validation at time 1000, what is the correct code?
##### Ans: 
```
time_train = time[:split_time]
x_train = series[:split_time]
time_valid = time[split_time:]
x_valid = series[split_time:]
```
#### 7. If you want to inspect the learned parameters in a layer after training, what’s a good technique to use?
##### Ans: Assign a variable to the layer and add it to the model using that variable. Inspect its properties after training
#### 8. How do you set the learning rate of the SGD optimizer? 
##### Ans: Use the lr property
#### 9. If you want to amend the learning rate of the optimizer on the fly, after each epoch, what do you do?
##### Ans: Use a LearningRateScheduler object in the callbacks namespace and assign that to the callback 