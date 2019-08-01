#### 1. How do you use Image Augmentation in TensorFLow
##### Ans: Using parameters to the ImageDataGenerator
#### 2. If my training data only has people facing left, but I want to classify people facing right, how would I avoid overfitting?
##### Ans: Use the ‘horizontal_flip’ parameter
#### 3. When training with augmentation, you noticed that the training is a little slower. Why?
##### Ans: Because the image processing takes cycles
#### 4. What does the fill_mode parameter do?
##### Ans: It attempts to recreate lost information after a transformation like a shear
#### 5. When using Image Augmentation with the ImageDataGenerator, what happens to your raw image data on-disk.
##### Ans: Nothing, all augmentation is done in-memory
#### 6. How does Image Augmentation help solve overfitting?
##### Ans: It manipulates the training set to generate more scenarios for features in the images
#### 7. When using Image Augmentation my training gets...
##### Ans: Slower
#### 8. Using Image Augmentation effectively simulates having a larger data set for training.
##### Ans: True