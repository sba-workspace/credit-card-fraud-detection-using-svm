# Credit Card Fraud Detection using SVM

This project implements a machine learning solution for detecting fraudulent credit card transactions using Support Vector Machines (SVM). The model is trained on a dataset containing credit card transactions, where it learns to distinguish between legitimate and fraudulent transactions.

## Project Overview

The project uses a Support Vector Machine classifier to identify potentially fraudulent credit card transactions. The implementation includes data preprocessing, model training, and evaluation steps to create an effective fraud detection system.

### Features

- Data preprocessing and scaling
- Feature selection and engineering
- SVM model implementation
- Model evaluation using various metrics
- Handling imbalanced dataset
- Visualization of results

## Requirements

- Python 3.x
- Required libraries:
  - numpy
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/credit-card-fraud-detection-using-svm.git
cd credit-card-fraud-detection-using-svm
```

2. Install the required packages:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

1. Open and run the Jupyter notebook `credit-card-fraud-detection-using-svm.ipynb`
2. Follow the step-by-step implementation including:
   - Data loading and preprocessing
   - Feature scaling
   - Model training
   - Evaluation and visualization

## Model Details

The project implements:
- Support Vector Machine (SVM) classifier
- Feature scaling using StandardScaler
- Cross-validation for model evaluation
- Performance metrics including:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

## Results

The model achieves high accuracy in detecting fraudulent transactions while maintaining a good balance between precision and recall. Detailed performance metrics and visualizations are available in the notebook.

## Contributing

Feel free to fork this repository and submit pull requests to contribute to this project. You can also open issues for any bugs found or improvements suggested.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- The dataset used in this project is from Kaggle's Credit Card Fraud Detection dataset
- Thanks to all contributors who helped in improving this project
