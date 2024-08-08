<h1>  Breast Cancer Prediction Using Neural Networks</h1>
<p> This project involves building a neural network model using TensorFlow and Keras to predict whether a tumor is malignant or benign based on various features. 
The dataset used is the Breast Cancer Wisconsin dataset from scikit-learn.
</p>
<h3>Summary</h3>
<h4>Data Collection & Processing:</h4>
The Breast Cancer dataset is loaded using sklearn.datasets.load_breast_cancer().
The dataset is converted into a pandas DataFrame with appropriate column names.
Data preprocessing steps include checking for missing values, analyzing the distribution of the target variable, and separating the features and target variable.

<h4> Data Splitting & Standardization: </h4>
The dataset is split into training and testing sets using train_test_split with 80% training data and 20% testing data.
Feature scaling is done using StandardScaler to standardize the data.

<h4> Model Building:</h4>

A simple neural network is created using Keras, consisting of one input layer, one hidden layer, and one output layer.
The model is compiled using the Adam optimizer and sparse categorical cross-entropy as the loss function.
The model is trained for 10 epochs with validation data.

<h4> Model Evaluation: </h4>
The model’s accuracy and loss are plotted to visualize the training process.
The model is evaluated on the test data to determine its accuracy.

<h4> Prediction System: </h4>
A prediction system is built to input data and predict whether the tumor is malignant or benign.
