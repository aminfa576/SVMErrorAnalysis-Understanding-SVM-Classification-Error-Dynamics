# SVMErrorAnalysis: Understanding SVM Classification Error Dynamics

## Overview
SVMErrorAnalysis is a project developed as part of the Statistical Machine Learning module in the MSc Data Analytics course at Aston University. The project systematically explores the influence of the regularization parameter \( C \) on the classification error of a Linear Support Vector Machine (SVM). Its primary aim is to provide empirical insights into the SVM's behavior under different regularization strengths.

## Academic Context
This project was conceived and executed as a hands-on assignment for the Statistical Machine Learning module. It offers students a practical and insightful experience in training, validating, and analyzing classification errors associated with SVMs.

## Tasks
The project is structured into the following key tasks:
1. **Train a Linear SVM:** Train a linear SVM using `training.csv` for \( C = 1, 2, 3, \ldots, 20 \). Extract and store the parameters \( w_C \) and \( b_C \) for each \( C \).
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
SVMErrorAnalysis offers a detailed exploration into the variations in classification error and its standard deviation under different regularization parameters in a Linear SVM. The findings and visuals generated from this project are crucial for students, researchers, and practitioners looking to gain a deeper insight into the impact of regularization on SVM's error dynamics.
