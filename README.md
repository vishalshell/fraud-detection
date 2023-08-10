# Fraud Detection Model using Machine Learning

This repository contains a Python script that demonstrates building and evaluating fraud detection
models using various machine learning algorithms.
The code uses popular libraries like `pandas`, `scikit-learn`, and `imbalanced-learn`.

## Getting Started

To use this code:

1. Clone the repository:
   ```sh
    git clone https://github.com/vishalshell/fraud-detection.git
   ```

2. Install the required Python packages:
   ```sh
   pip install pandas scikit-learn imbalanced-learn matplotlib
   ```

3. Place your dataset file named `fraud_detection1.csv` in the same directory as the script.

4. Run the Python script:
   ```sh
   python fraud_detection_model.py
   ```

## Features

- Loads and preprocesses fraud detection dataset.
- Implements Logistic Regression, Decision Tree, and Random Forest models.
- Uses SMOTE to handle class imbalance.
- Evaluates models' performance with Accuracy, Precision, Recall, and F1-score.
- Displays evaluation results and Accuracy graph.

## Dependencies

- pandas
- scikit-learn
- imbalanced-learn
- matplotlib

## datasource Link
Its from Kaggle and can be found at https://www.kaggle.com/datasets/chitwanmanchanda/fraudulent-transactions-data

## Contributing

Contributions are welcome! Feel free to open a pull request with your enhancements or bug fixes.

## Acknowledgments

This code serves as a demonstration for building fraud detection models. Further enhancements and real-world data considerations are encouraged.
