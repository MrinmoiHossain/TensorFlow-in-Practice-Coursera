#### 1. If I put a dropout parameter of 0.2, how many nodes will I lose?
##### Ans: 20% of them
#### 2. Why is transfer learning useful?
##### Ans: Because I can use the features that were learned from large datasets that I may not have access to
#### 3. How did you lock or freeze a layer from retraining?
##### Ans: layer.trainable = false
#### 4. How do you change the number of classes the model can classify when using transfer learning? (i.e. the original model handled 1000 classes, but yours handles just 2)
##### Ans: When you add your DNN at the bottom of the network, you specify your output layer with the number of classes you want
#### 5. Can you use Image Augmentation with Transfer Learning Models? 
##### Ans: Yes, because you are adding new layers at the bottom of the network, and you can use image augmentation when training these
#### 6. Why do dropouts help avoid overfitting?
##### Ans: Because neighbor neurons can have similar weights, and thus can skew the final training 
#### 7. What would the symptom of a Dropout rate being set too high?
##### Ans: The network would lose specialization to the effect that it would be inefficient or ineffective at learning, driving accuracy down
#### 8. Which is the correct line of code for adding Dropout of 20% of neurons using TensorFlow
##### Ans: tf.keras.layers.Dropout(0.2),