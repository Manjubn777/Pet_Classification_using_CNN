# Pet_Classification_using_CNN

DESCRIPTION

Build a CNN model that classifies the given pet images correctly into dog and cat images. 

Project Description and Scope 

following resources that can be used as inputs for your model: 

1. A collection of images of pets, that is, cats and dogs. These images are of 

different sizes with varied lighting conditions. 2. Code template containing the following code blocks: 

a. Import modules (part 1) b. Set hyper parameters (part 2) c. Read image data set (part 3) d. Run TensorFlow model (part 4) 

Requirement is to write the code for CNN image classification model (between Parts 3 and 4) using TensorFlow that trains on the data and calculates the accuracy score on the test data. 

Project Guidelines 

Begin by extracting ipynb file and the data in the same folder. The CNN model (cnn_model_fn) have the following layers: 

● Input layer 

● Convolutional layer 1 with 32 filters of kernel size[5,5] 

● Pooling layer 1 with pool size[2,2] and stride 2 

● Convolutional layer 2 with 64 filters of kernel size[5,5] 

● Pooling layer 2 with pool size[2,2] and stride 2 

● Dense layer whose output size is fixed in the hyper parameter: fc_size=32 

● Dropout layer with dropout probability 0.4 

Predict the class by doing a softmax on the output of the dropout layers. 

● For the evaluation step, Predict classes

