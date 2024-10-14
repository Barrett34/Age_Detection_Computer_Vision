# Age_Detection_Computer_Vision
The supermarket chain Good Seed would like to explore whether Data Science can help them adhere to alcohol laws by making sure they do not sell alcohol to people underage. We will build a model with the ImageDataGenerator and a GPU Platform to train the model. 

## Data Description
`/datasets/faces/labels.csv`
`/datasets/faces/final_files/`

## Conclusion

By utilizing a generator for the train and test sets and leveraging the power of the GPU platform, we successfully trained a convolutional neural network using the ResNet50 architecture from TensorFlow. We observed that the model did not exhibit overfitting, as indicated by the decreasing loss and mean absolute error on both the training and testing sets. Remarkably, the achieved mean absolute error (MAE) score on the test set was an impressive 6.4786.

This accomplishment demonstrates the effectiveness of computer vision techniques when applied to datasets comprising photos of individuals. Consequently, the developed model can be leveraged to determine the age of a person based on a photo. Such a model holds tremendous value for Good Seed, a supermarket chain, as it aids in age verification, ensuring compliance with alcohol laws by preventing the sale of alcohol to underage individuals.
