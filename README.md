# Malicious-script-prediction

The project Aims at detecting the XSS attacks present in the HTML Scripts using the various Machine Learning Algorithms and Neural Networks.

The Implementation of the Project is present in the Code.ipynb file ,this jupyter file can be run to classify the scripts as malicious and non-malicious.

To run the Code File,first modify the path of the downloaded dataset according to your directory where you store it.

The dataset file is present in this Folder itself with name XSS_dataset.csv.

The Implementation begins with the Loading of the Dataset.After Loading the dataset ,the Pre-processing starts where we convert the sentences to its ASCII value equivalent and then convert the dataset into a matrix of size 100x100.
Now ,split the data into test and train split of 20 -80.
The next step is of Model Building ,where we will be compiling the CNN model by adding the layers to our model one by one.

We have a total of 11 layers and 3 convolutional layers and after this we will compile the model and  Use Adam Optimization and Binary cross-entropy loss function.

After this import the necessary libraries related to Machine learning algorithms.The algorithms now need to be trained on the train dataset and then we will predict the values using the trained model.

After getting the values,we will calculate the Accuracy,Precision and Recall to compare the results obtained by various models.

Finally ,our Model is ready to Predict the malicious scripts and detect the XSS attacks.
