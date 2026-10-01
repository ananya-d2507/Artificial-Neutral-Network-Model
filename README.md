# Artificial-Neutral-Network-Model

# Objective

To develop an ANN model that predicts diabetes progression using the independent variables in the scikit-learn Diabetes dataset.

# Data Processing

The dataset was loaded using scikit-learn and checked for missing values. The features were standardized using StandardScaler to improve ANN training.

# EDA

The distributions of the features and target were examined using descriptive statistics and visualizations. Scatter plots and a correlation heatmap were used to understand relationships between variables.

# ANN Model

A neural network with hidden layers using ReLU activation was developed. Since diabetes progression is a continuous target, a single output neuron was used for regression.

# Training

The dataset was split into training and testing sets. The ANN was trained using the Adam optimizer and Mean Squared Error (MSE) loss function.

# Evaluation

The model was evaluated using MSE and R² score. MSE measures prediction error, while R² indicates how well the model explains variation in the target.

# Model Improvement

Different architectures and training parameters were tested. The original and improved models were compared using their test MSE and R² scores.

# Conclusion

The improved ANN model performed better than the original model. The MSE decreased from 4,201.8 to 2,843, while the R² score increased from 0.20 to 0.46. This shows that the improved architecture was able to predict diabetes progression more accurately and explain more of the variation in the target variable.
