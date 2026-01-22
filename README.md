Handwritten Digit Recognition Using SVM

Overview
This project implements a Support Vector Machine (SVM) classifier to recognize handwritten digits using the Digits dataset from scikit-learn. The model is trained on image data, evaluates classification performance, and demonstrates digit prediction on a sample image.
The notebook was created using Google Colab.

Dataset
Source: sklearn.datasets.load_digits
Number of classes: 10 (digits 0–9)
Image size: 8 × 8 pixels
Features: Flattened pixel intensity values
Labels: Digit values (0–9)

Data Preprocessing
Loaded the digits dataset from scikit-learn
Flattened image data used as input features
Applied standardization using StandardScaler
Split the dataset into:
Training set: 80%
Testing set: 20%

Model
Algorithm: Support Vector Machine (SVM)
Classifier: SVC
Kernel: Default (RBF)
Gamma: scale

Model Evaluation
The model performance is evaluated using:
Confusion Matrix
Classification Report
Precision
Recall
F1-score
Accuracy

Example Prediction
The model predicts a digit from the test dataset by reshaping a single image and passing it to the trained classifier.

Libraries Used
numpy
matplotlib
scikit-learn

How to Run
Install required dependencies:
pip install numpy matplotlib scikit-learn
Run the notebook in Google Colab or Jupyter Notebook.
The dataset is loaded automatically from scikit-learn.

Output
Confusion matrix of predicted vs actual digits
Detailed classification report
Predicted digit for a sample test image

License
This project is intended for educational purposes.
