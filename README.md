# **Home Credit Default Risk - Applied Machine Learning Project**
* The project focuses on predicting whether a client can repay a loan or not, using the “Home Credit Default Risk” Kaggle Competition dataset.
* The aim is to improve the loan experience for clients who have insufficient credit histories by using additional information, such as telco and transactional data.
* Following extensive exploratory data analysis(EDA), We performed feature engineering, introduced three new features, trained final features on various models such as Logistic Regression, Random Forest and Decision tree with hyper parameter tuning using gridsearch cv.
* For the final phase of the project, three neural networks were implemented using PyTorch Lightning for classification.
* The dataset was transformed into a tensor using the 'Data_pre_nn' function, and ReLU was used as the activation function, along with the Adam optimizer.
* The binary cross-entropy loss function was used, and backward propagation was implemented to minimize the loss.
* Neural Network 1, with 4 hidden layers, 400 epochs, and a batch size of 100, gave the best results.
* Neural Network 2 had the same architecture as Neural Network 1, but with 100 epochs and a batch size of 128.
* Neural Network 3 had a different architecture, with 3 hidden layers and 2 sigmoid output layers.
* The first neural network performed better compared to other 2 with accuracy of 0.938 and AUC score of 0.580
