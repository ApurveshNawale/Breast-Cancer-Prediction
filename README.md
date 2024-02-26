# Breast-Cancer-Prediction
This repository contains a Python script for predicting breast cancer using machine learning techniques. The script loads the breast cancer dataset from scikit-learn, preprocesses the data, and trains different models to classify tumors as malignant or benign.


## Prerequisites

To run the code in this repository, you need to have the following Python packages installed:

- numpy
- pandas
- scikit-learn
- scipy
- matplotlib

You can install these packages using pip:

```bash
  pip install numpy pandas scikit-learn scipy matplotlib

```

## Dataset
The dataset is upload on Github


## Usage

Clone the project

```bash
  git clone https://github.com/ApurveshNawale/Breast-Cancer-Prediction.git
```

Navigate to the project directory:


```bash
  cd breast-cancer-prediction
```

Run the Python script:

```bash
  python breast_cancer_prediction.py
```

The script will perform the following tasks:

- Load and preprocess the breast cancer dataset
- Create additional features (e.g., area_perimeter_interaction, radius_texture_interaction)
- Train a Random Forest Classifier with hyperparameter tuning
- Evaluate the Random Forest model's performance (accuracy, feature importance)
- Train and evaluate a Support Vector Machine (SVM) classifier


## Result
The script will output the following results:

- Confusion matrix and classification report for the SVM classifier
- Accuracy of the best Random Forest model on the test set
- Feature importance plot for the Random Forest model
- Selected features based on importance threshold


## Acknowledgments
- The breast cancer dataset is obtained from the UCI Machine Learning Repository.
- This project uses the scikit-learn library for machine learning tasks.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

