# ML Adult Salary Prediction

This repository contains a machine learning project aimed at predicting whether an individual's salary exceeds $50K/year based on various demographic and socio-economic features. The dataset utilized for this project is the Adult Census Income dataset.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling and Evaluation](#modeling-and-evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to develop a classification model that predicts whether a person makes over $50K a year based on features such as age, education, occupation, and more. This project includes the following steps:

- Data exploration and cleaning
- Feature engineering and transformation
- Training various machine learning models
- Hyperparameter tuning and model optimization
- Evaluation of model performance

## Dataset

The dataset used in this project is the [Adult Census Income dataset](https://archive.ics.uci.edu/ml/datasets/adult), which contains the following features:

- Age
- Workclass
- Education
- Marital-status
- Occupation
- Relationship
- Race
- Sex
- Hours-per-week
- Native-country
- Income (target variable)

### Data Preprocessing

The data preprocessing steps include:

- Handling missing values
- Encoding categorical variables
- Scaling numerical features

## Installation

To get started with the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/ansh-vyas/ML-adult-salary-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ML-adult-salary-prediction
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```


## Modeling and Evaluation

The following machine learning models have been implemented and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- Gradient Boosting Classifier

### Performance Metrics

The models are evaluated based on the following metrics:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## Results

The best-performing model is **[your best model]**, with an accuracy of **[accuracy score]** and an ROC-AUC score of **[ROC-AUC score]**. This model has been fine-tuned to improve its performance.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/ansh-vyas/ML-adult-salary-prediction/issues) for open issues.

To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add a new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
