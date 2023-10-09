# SVMErrorAnalysis: Understanding SVM Classification Error Dynamics

## Overview
SVMErrorAnalysis is a project developed as part of the Statistical Machine Learning module in the MSc Data Analytics course at Aston University. The project systematically explores the influence of the regularization parameter \( C \) on the classification error of a Linear Support Vector Machine (SVM). Its primary aim is to provide empirical insights into the SVM's behavior under different regularization strengths.

## Academic Context
This project was conceived and executed as a hands-on assignment for the Statistical Machine Learning module. It offers students a practical and insightful experience in training, validating, and analyzing classification errors associated with SVMs.

## Tasks
The project is structured into the following key tasks:
1. **Train a Linear SVM:** Train a linear SVM using `training.csv` for ( C = 1, 2, 3,..., 20 ). Extract and store the parameters \( w_C \) and \( b_C \) for each \( C \).
2. **Validation and Error Calculation:** Load `validation.csv` and divide it into 10 subsets of equal size. Compute the expectation and variance of the classification error for each subset using the parameters obtained from the training phase.
3. **Error Analysis Visualization:** Create a plot of the estimated classification error (with its standard deviation) as a function of \( C \).

## Dataset
- `training.csv`: Consists of 200 entries, each with an input vector in \( R^2 \) and a binary label.
- `validation.csv`: Comprises 800 entries, structured similarly to `training.csv`.

## Technologies and Libraries
- Python
- Pandas
- NumPy
- scikit-learn
- Matplotlib


## Conclusion
SVMErrorAnalysis elucidates the intricate dynamics of classification error in relation to the regularization parameter \( C \) within a Linear SVM framework. Through meticulous training, validation, and error analysis processes, the project reveals that the classification error estimate exhibits subtle fluctuations across different values of \( C \). These variations are captured and visualized effectively to provide a comprehensive understanding of the error landscape.

The analysis indicates that the classification error does not vary significantly with changes in the regularization parameter, remaining relatively stable across different levels of \( C \). This observation is crucial as it suggests that the model's performance is somewhat insensitive to the regularization strength within the examined range, providing valuable insights for practitioners and researchers in selecting appropriate regularization parameters for SVM models in similar contexts.

Furthermore, the project computes and visualizes the standard deviation of the classification error, offering additional layers of understanding regarding the model's reliability and performance consistency. The standard deviation values observed are relatively small, indicating that the classification error is not only low on average but also stable, with limited variability across different subsets of the data.


