# Support Vector Regression (SVR)
This notebook demonstrates the implementation of Support Vector Regression (SVR) using the dataset Wellbeing.csv for predicting target values.

## **Dataset**
The dataset, Wellbeing.csv, includes the following columns:
1. Features: Columns containing various parameters related to wellbeing.
2. Target: The wellbeing score.

## **Description**
SVR is employed to predict numerical values based on a set of features from the Wellbeing.csv dataset. The notebook showcases the following steps:
- Importing necessary libraries.
- Preprocessing the dataset by encoding categorical data and splitting it into training and test sets.
- Feature scaling for better model performance.
- Training the SVR model using the radial basis function (RBF) kernel.
- Making predictions on the test set.
- Evaluating the model performance using the R-squared (R2) score.

## **Usage**
1. Clone or download the repository containing the notebook and the Wellbeing.csv dataset.
2. Open the notebook in a Jupyter environment or any compatible platform.
3. Ensure that the dataset file Wellbeing.csv is placed in the same directory as the notebook.
4. Run the notebook cells sequentially to observe the SVR model implementation and evaluation.

## **Files**
Support Vector Regression_Devansh Gupta.ipynb: Jupyter notebook containing the SVR implementation.
Wellbeing.csv: Dataset used for training and testing the SVR model.

## **Results**
The SVR model achieves an R-squared score of approximately **0.993**, indicating strong predictive performance.
