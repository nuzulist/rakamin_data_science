# Tutorial Modeling Data Titanic

Tutorial ini akan mengolah data titanic menjadi data yang siap untuk dilakukan pemodelan

## Prerequisites

1. download data [here](https://www.kaggle.com/datasets/fossouodonald/titaniccsv)
2. instalasi dengan `pip install requirements.txt`

## Getting Started

- Dataset Splitting
- Training
- Model Validation

### Dataset Splitting

split data into training, validation and test sets

```code
x_train, y_train, x_test, y_test = dataset_splitting()
x_train.shape, y_train.shape

```

## Reference
1. scikit-learn documentation 