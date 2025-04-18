# Computational-Intel-2025
This project implements neural network models to classify patients as Alzheimer's-positive or not, based on biomedical, demographic, and cognitive data. It includes data preprocessing, feature scaling, model training with various architectures, hyperparameter tuning, regularization, and evaluation using 5-fold cross-validation.


##**Dataset**


The dataset used is the Alzheimer’s Disease Dataset containing records for 2,149 individuals with 35 features, including both numerical and categorical variables such as:

Biomarker measurements

Patient history

Cognitive and behavioral assessments

Demographics (age, gender, ethnicity, etc.)

The target column indicates whether or not the patient has been diagnosed with Alzheimer’s.


##**Project structure**


###**Data Preprocessing**

Handling mixed-type features (continuous, ordinal, categorical)

Feature scaling via normalization, standardization, and centering

One-hot encoding for categorical variables

Ensuring consistent transformations across training and test splits

###**Model Architecture**

Feedforward neural networks trained with the Backpropagation algorithm

One hidden layer (baseline) with experiments on varying neuron counts

Evaluation of activation functions (ReLU, Tanh, SiLU) and output layers (Sigmoid, Softmax)

###**Model Evaluation**

Accuracy, Cross-Entropy Loss, and Mean Squared Error

Use of 5-fold cross-validation to assess model generalization

Experiments with learning rates and momentum (η and μ) to optimize convergence

###**Regularization**

Application of L2 regularization to reduce overfitting

Comparative analysis across different regularization strengths (r values)

###**Deep Neural Networks**

Exploration of architectures with multiple hidden layers

Discussion of layer design heuristics and performance impact


##**Tools/libraries**


Python + Tensorflow, keras, pandas, numpy, matplotlib, seaborn
