# Tute-Dude-Ds-Assignment-5
# Naive Bayes Titanic Survival Prediction

This project demonstrates the implementation of the Naive Bayes classification algorithm using the Titanic dataset to predict passenger survival.

## Project Workflow

### 1. Data Exploration
- Loaded the Titanic dataset using Pandas
- Inspected:
  - Dataset structure
  - Data types
  - Missing values

### 2. Data Preprocessing
- Filled missing values in:
  - Age column using mean
  - Embarked column using mode
- Dropped the Cabin column due to excessive missing values
- Encoded categorical variables:
  - Sex
  - Embarked

### 3. Train-Test Split
- Divided the dataset into:
  - Training set
  - Testing set

### 4. Naive Bayes Model
- Implemented Gaussian Naive Bayes classifier
- Trained the model using training data

### 5. Model Evaluation
- Calculated:
  - Accuracy score
  - Confusion matrix
  - Classification report

### 6. Visualization
- Displayed confusion matrix using Matplotlib

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
