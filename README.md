# Loan-Prediction
We have various independent variables ranging from Education, Income, Loan Amount, Credit History etc. and one target variable Loan Status. Since we have two values in our target variable ‘Y’ which represent Loan Approved and ’N’ which represents Loan Not Approved.
STEP 1: DATA PREPROCESSING STEP:
-Filling null values / missing values .
-Converting categorical values into number.
-Bring all variables to same scale between (0 to 1) which reduces computation time and helps neural network to converge faster.
STEP 2: STEPS TO BUILD NEURAL NETWORK:
-Loading the data.
-Creating training and validation data: We will train on train data and validate on validation data.
-Defining the architecture of our model: We will define how many input neurons, nos. of neurons in hidden layer and output layer.
-Compile the model (loss function / optimizers): Here we will be defining our cost function which will be used during backward propagation.
-Train the model: We will train our model and define nos. of epochs.
-Evaluate models performance on training and validation data.
STEP #:VISUALZING RESULTS (LOSS & ACCURACY)
