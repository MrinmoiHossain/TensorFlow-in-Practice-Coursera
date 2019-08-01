#### 1. What does flow_from_directory give you on the ImageGenerator?
#### Ans: 
- The ability to easily load images for training
- The ability to pick the size of training images
- The ability to automatically label images based on their directory name
- All of the above
#### 2. If my Image is sized 150x150, and I pass a 3x3 Convolution over it, what size is the resulting image?
#### Ans: 148x148
#### 3. If my data is sized 150x150, and I use Pooling of size 2x2, what size will the resulting image be?
#### Ans: 75x75
#### 4. If I want to view the history of my training, how can I access it?
#### Ans: Create a variable ‘history’ and assign it to the return of model.fit or model.fit_generator
#### 5. What’s the name of the API that allows you to inspect the impact of convolutions on the images?
#### Ans: The model.layers API
#### 6. When exploring the graphs, the loss levelled out at about .75 after 2 epochs, but the accuracy climbed close to 1.0 after 15 epochs. What's the significance of this?
#### Ans: There was no point training after 2 epochs, as we overfit to the training data
#### 7. Why is the validation accuracy a better indicator of model performance than training accuracy?
#### Ans: The validation accuracy is based on images that the model hasn't been trained with, and thus a better indicator of how the model will perform with new images.
#### 8. Why is overfitting more likely to occur on smaller datasets?
#### Ans: Because there's less likelihood of all possible features being encountered in the training process.