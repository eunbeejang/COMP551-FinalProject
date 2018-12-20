# COMP551- Fall 2018 FinalProject: T1 - 06: "Effective Use of Word Order for Text Categorization with CNN"
Sentiment Classification using SVM, NB, NB-SVM, and MultiLayer Perceptron Neural Networks

Contents of this repo:

1. 'Dataset' folder contains all the input data files of the IMDB review dataset to be used.
2. 'NB_and_NBSVM.ipynb' contains all the code for the model Naive Bayes implementation and Naive Bayes SVM implementation.
3. 'SVM_model.ipynb' contains all the code for the model SVM implementation.
4. 'NeuralNetwork.ipynb' contains all the code for the model MultiLayer Perceptron Neural Network implemented using Keras.

NOTE: ALL NOTEBOOK FILES ALREADY CONTAIN THEIR RESPECTIVE DATA PREPROCESSING. THERE IS NO EXTERNAL DATA PREPROCESSING FILE.

Set-up:

1. First setup your folder directory such that you have all notebook files in same level.
2. Create folder called 'Dataset' on same level as all notebook files if not already created.
3. Create folder called 'Input' child folder of 'Dataset' folder if not already created.
4. Within the 'Input' folder, store the 'IMDB-train.txt', 'IMDB-valid.txt', and 'IMDB-test.txt' files.

Run this code:

1. Run the notebook file of the corresponding model you wish to test in the chronological order of the cells as setup within the notebook files.

NOTE: PLEASE PAY ATTENTION TO MARKDOWNS IN THE MODELS' CODE BECAUSE THEY CONTAIN IMPORTANT INFO ON HOW TO REFORMAT DATA AFTER EVERY TIME A MODEL IS FIT.
