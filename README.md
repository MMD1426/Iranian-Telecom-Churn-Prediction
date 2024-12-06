# Iranian Telecom Churn Prediction

## Overview
This project predicts customer churn for an Iranian telecom company. Using customer data such as tariff plans, complaints, age group, and other features, it identifies which customers are likely to churn, allowing for proactive customer retention strategies.

## Features
- **Data Preprocessing**:
  - Encodes categorical features such as `Tariff plan` and `Complaints` using `LabelEncoder`.
  - Normalizes numerical features with `StandardScaler`.
  - Transforms the `Age group` column into numerical categories.
- **Deep Learning Model**:
  - Implements a neural network with dropout layers to prevent overfitting.
  - Optimized with the SGD optimizer and `BinaryCrossentropy` loss for binary classification.
- **Performance Evaluation**:
  - Provides detailed metrics like accuracy, precision, recall, and F1-score using `classification_report`.
  - Includes confusion matrix visualization with Seaborn for better understanding of predictions.

## Requirements
- Python 3.x
- Required libraries:
  - `pandas`
  - `numpy`
  - `seaborn`
  - `matplotlib`
  - `scikit-learn`
  - `tensorflow`

## Results
- The model achieved a high level of accuracy on the validation set.
- Visualizations include:
  - Learning curves to track loss and accuracy over epochs.
  - Heatmap of the confusion matrix for better interpretability of predictions.

## Future Work
- Fine-tune the model by testing different architectures and optimizers.
- Add more features to the dataset, such as customer tenure and usage patterns, for improved accuracy.
- Develop a web-based interface for business use cases.

## License
This project is licensed under the MIT License.

## Contributions
Contributions are welcome! Feel free to open issues or submit pull requests.
