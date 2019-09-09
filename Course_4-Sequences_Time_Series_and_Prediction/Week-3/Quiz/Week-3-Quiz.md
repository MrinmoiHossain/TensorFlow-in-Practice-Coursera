#### 1. If X is the standard notation for the input to an RNN, what are the standard notations for the outputs?
##### Ans: Y(hat) and H
#### 2. What is a sequence to vector if an RNN has 30 cells numbered 0 to 29
##### Ans: The Y(hat) for the last cell
#### 3. What does a Lambda layer in a neural network do?
##### Ans: Allows you to execute arbitrary code while training
#### 4. What does the axis parameter of tf.expand_dims do?
##### Ans: Defines the dimension index at which you will expand the shape of the tensor 
#### 5. A new loss function was introduced in this module, named after a famous statistician. What is it called?
##### Ans: Huber loss
#### 6. What’s the primary difference between a simple RNN and an LSTM
##### Ans: In addition to the H output, LSTMs have a cell state that runs across all cells 
#### 7. If you want to clear out all temporary variables that tensorflow might have from previous sessions, what code do you run?
##### Ans: tf.keras.backend.clear_session()  
#### 8. What happens if you define a neural network with these two layers?
```python
tf.keras.layers.Bidirectional(tf.keras.layers.LSTM(32)),
tf.keras.layers.Bidirectional(tf.keras.layers.LSTM(32)),
tf.keras.layers.Dense(1),
```
##### Ans: Your model will fail because you need return_sequences=True after the first LSTM layer