# Practical

## Preprocessing

### Encoding categorical values

Encode var 3 using one hot

Encode var 6 using ordinary encoding

Encode var 7 using ???

### Data imputation

Separate rows that have a defined value of var4 from those that dont

Use both Linear Regression and Polynomial regression on the defined set

Somehow:

- select the most optimal regression model and
- fill in the missing values

### Implementing the PCA technique

?? implement the PCA technique for reducing the dimensionality

?? implement it from scratch following the steps described in the lectures.

?? You should show different scatter plots that visualizes the data

## Training

### Model 

Logistic Regression

KNN (try the n neighbors hyperparameters between [1, 10] range)

Naive Bayes

### Cross-Validation 

You should set k = 3 for the K-Fold Cross-Validation technique and calculate the average performance of the model on cross-validation set

### PCA

reducing the dimensions to test if model performs better in this case

repeat training with PCA

# Theoretical

## Regarding the Preprocessing

- Which regression model was the most effective for the missing values, and why? (50 %)
- What encoding technique did you use for encoding the categorical features, and why? (50 %)

## Regarding the training process

- Which classification model performed best, and why? (30 %)
- What were the most critical features with regards to the classification, and why? (20 %)
- What features might be redundant or are not useful, and why? (20 %)
- Did the dimensionality reduction by the PCA improve the model performance, and why? (20 %)
- Additional research: (a) what is a multi-label learning problem? (b) suggest an example in which you
can transform the given problem into a multi-label problem? Will the models work as it is in that case, or
would some changes be required? (10 %)