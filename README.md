# Parameter-Optimization-SVM

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.

[Electrical Grid Stability Simulated Data Set](https://archive.ics.uci.edu/ml/datasets/Electrical+Grid+Stability+Simulated+Data+)

| Number of Instances:  | 10000 |
|-----------------------|--------|
| Number of Attributes: | 14     |

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.83 | Poly | 7.26 | 7.38 |
| 2 | 0.89 | Poly | 1.80 | 4.96 |
| 3 | 0.73 | Linear | 7.09 | 2.88 |
| 4 | 0.84 | Linear | 4.34 | 2.40 |
| 5 | 0.72 | Linear | 7.81 | 7.05 |
| 6 | 0.76 | Poly | 1.93 | 3.59 |
| 7 | 0.68 | RBF | 3.45 | 4.66 |
| 8 | 0.81 | Poly | 3.34 | 7.38 |
| 9 | 0.70 | Linear | 2.10 | 3.00 |
| 10 | 0.77 | Linear | 2.13 | 2.40 |

## Results

The best parameters of SVC for the given dataset are:
- Kernel : Poly
- Nu : 1.80  
- Epsilon : 4.96   

The above parameter gave a maximum accuracy of 0.89.\

## Convergence Graph
![graph](https://github.com/ree553/Parameter-Optimization-SVM/blob/main/output.png?raw=true)

Mudrika Jain <br>
102017143<br>
CS6


