# Fashion-Detector
The Fashion-MNIST dataset is a dataset of Zalando's article images, with 28x28 grayscale images of 70,000 fashion products from 10 categories, and 7,000 images per category. The training set has 60,000 images, and the test set has 10,000 images.

This was the dataset used:-

Label	  Description
  0	    T-shirt/top
  1	    Trouser
  2	    Pullover
  3	    Dress
  4	    Coat
  5	    Sandal
  6	    Shirt
  7	    Sneaker
  8	    Bag
  9	    Ankle boot

Steps followed by me to build this model :-
1. First I have tried to understand the data. I have used Python and its libraries to load, explore and analyze the data,
2. After that, I'have preprocessed the data. resize, rescale, convert the labels into one-hot encoding vectors and split up the data in    training and validation sets;
3. With all of this done, the neural network model is constructed. Next, i have compiled, trained and evaluate the model, visualizing the accuracy and loss plots;
4. Then, I have checked overfitting and overcame it by adding a dropout layer;
5. With this information, I have revisited the original model and re-train the model. I have re-evaluated the new model and compared the results of both the models;
6. Next, predictions were made on the test data, converted the probabilities into class labels and plotted few test samples that the model correctly classified and incorrectly classified;
7. Finally, I have visualized the classification report which had given me more in-depth intuition about which class was (in)correctly classified by the model.
