# Wine-quality-prediction-analysis-using-regression

Note: For source code refer to Question-1 of 23m1084_a2.ipynb file

## Overview

This project involves predicting wine quality using regression models and evaluating their performance on out-of-distribution data. The dataset used is the Wine Quality dataset, which includes both red and white wines. The tasks completed in this project include data exploration, model training, and validation with various regression techniques.

## Project Structure

- **Data Exploration and Pre-processing**: Notebook for exploring, visualizing, and pre-processing the wine quality datasets.
- **Model Training and Validation**: Notebook for training, validating, and testing the following models:
  - Random Forest Regressor
  - Support Vector Regression with RBF Kernel
- **Feature Importance Analysis**: Notebook for determining and comparing the importance of features across different models.
- **Out-of-Distribution Testing**: Notebook for testing model performance with red wine data on white wine and vice versa.

## Dataset

The Wine Quality datasets can be downloaded from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality). The datasets include:

- **Red Wine Quality**: `winequality-red.csv`
- **White Wine Quality**: `winequality-white.csv`

## Steps Completed

1. **Data Exploration and Pre-processing**
   - Downloaded the wine quality datasets.
   - Explored and visualized the data.
   - Pre-processed the data as necessary for modeling.

2. **Model Training and Validation**
   - Trained and validated the following models:
     - Random Forest Regressor
     - Support Vector Regression with RBF Kernel
     - Neural Network with a single hidden layer (output layer with linear activation)
   - Varied at least one hyperparameter for validation.

3. **Feature Importance Analysis**
   - Investigated how to determine the importance of each variable.
   - Analyzed feature importance for the final models and compared across models.

4. **Out-of-Distribution Testing**
   - Tested models trained on red wine data with white wine data and vice versa.
   - Commented on the applicability of the models between red and white wines.

## Results and Findings

- The models were evaluated based on their performance metrics.
- Feature importance was analyzed, revealing how different features impact the predictions.
- The applicability of red wine models to white wine data and vice versa was assessed.

## Contributing

Contributions to improve the analysis or add additional features are welcome. Please submit issues or pull requests as needed.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- UCI Machine Learning Repository for providing the Wine Quality datasets.
- [Any other relevant acknowledgments]

