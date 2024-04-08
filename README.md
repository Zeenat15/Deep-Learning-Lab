# Deep-Learning-Lab

TITLE : Intel Image Classification

PROBLEM STATEMENT : Build powerful Neural network that can classify image data of Natural Scenes around the world.

EXPLANATION : The Intel Image Classification Dataset provides a collection of images classified into categories representing scenes such as buildings, forests, mountains, and more. The problem statement revolves around developing machine learning models capable of accurately classifying these images into their respective categories. This dataset serves as a resource for training and evaluating image classification algorithms.

Dataset Link: https://www.kaggle.com/datasets/puneet6060/intel-image-classification

STEP 1 : Import necessory libraries

STEP 2 : Import test, train, predit folders

STEP 3 : Checking for total images in train, test and all their subsequent folders of buildings, forest, glacier, mountain, sea, street.

STEP 4 : Assign class labels.

STEP 5 : Checking dimension for all image and calculating their total count.

STEP 6 : Making X_train, Y_train, X_test, Y_test. Appending images to X_train, X_test and Appending labels to y_train, Y_test. Showing images from train and test folder.

STEP 7 : Define a CNN model consisting of convolutional layers with ReLU activation, max pooling, flattening, and dense layers, followed by dropout and softmax activation for multiclass classification.

STEP 8 : Compile model with Adam optimizer, sparse categorical crossentropy loss, and accuracy metric THEN print model details by model accuracy.

STEP 9 : Trains model for 20 epochs with a batch size of 256 on X_train and y_train with displaying progress.

STEP 10 : Evaluate model on test data.
Print test loss and accuracy.
Test loss: 6.31, Test accuracy: 0.25.

STEP 11 : Predicts labels for test data.
Displays shape of prediction.
Processing 94 batches.
Average time per batch: 3 seconds.
Shape of prediction: (3000, 6).

STEP 12 : Predict labels using the trained model.
Display the shape of the prediction results.
At last print images with predicted labels.

CONCLUSION : Successfully implemented CNN model to classify image data of Natural Scenes using tensorflow and keras.
