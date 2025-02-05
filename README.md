# Logistic Regression Model

## Overview

This project implements a **Logistic Regression Model** for binary classification. The model is trained on a synthetic dataset generated using `make_classification` and optimized using **hyperparameter tuning** techniques.

## Features

- **Data Preprocessing** (handling missing values, scaling features)
- **Synthetic Data Generation** using `sklearn.datasets.make_classification`
- **Model Training using Logistic Regression**
- **Hyperparameter Tuning** using **GridSearchCV** and **RandomizedSearchCV**
- **Performance Evaluation** (Accuracy, Precision, Recall, F1-Score, Confusion Matrix)
- **Data Visualization** using **Matplotlib** and **Seaborn**

## Dataset

- The dataset is synthetically generated with 1000 samples and 10 features.
- It is a binary classification problem with two classes.

## Installation

To run this project, install the required dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/kumarmohit0911/logistic_regression_model.git
   ```
2. Navigate to the project directory:
   ```bash
   cd logistic_regression_model
   ```
3. Open and run the **logi\_reg.ipynb** notebook:
   ```
   jupyter notebook logi_reg.ipynb
   ```

## Model Evaluation

The model's performance is assessed using:

- **Accuracy Score**
- **Confusion Matrix**
- **Precision, Recall, and F1-Score**
- **Hyperparameter tuning results**

## Results

The model achieved satisfactory performance, and hyperparameter tuning further improved its accuracy. Detailed analysis and visualizations are available in the notebook.

## Contributing

Feel free to contribute by improving the model, adding more features, or testing with different datasets. Fork the reposit[ory and sub](https://www.linkedin.com/in/kumar-mohit-20324827b/)mit a pull request!

## License

This project is open-source and available under the **MIT License**.

## Author

[Kumar Mohit](https://www.linkedin.com/in/kumar-mohit-20324827b/)

