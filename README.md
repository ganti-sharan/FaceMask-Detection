# FaceMask-Detection
There are 3 steps in this project : 
 1. data preprocessing
 2. Training the cnn
 3. Detecting the mask
 The images are dividing into 2 catagories with_mask as 0 and without_mask as 1.
All the images are converted to grey scale and are resized to 100*100
Then we create a convolution neural network
We reshape the data and split the data using test_train_split and we fit the data to the model
Hardcascade classifier is used to classify the faces.

