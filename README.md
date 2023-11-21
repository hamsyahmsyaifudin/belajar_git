# TUTORIAL Data Analytics Pandas

Tutorial ini akan mengolah data titanic menjadi data yang siap untuk dilakukan pemodelan

## Prerequisites

1. Download Data [Here](https://www.kaggle.com/datasets/brendan45774/test-file)
2. Instalasi dengan `pip install requirements.txt`

## Getting Started
- Dataset Splitting
- Dataset Training
- Model Validation

### Dataset Splitting
split data into training, validation and test set

```code
X_train, y_train, X_test, y_test = dataset_splitting()
X_train.shape, y_train.shape

## References
1. Di scikit-learn documentation

