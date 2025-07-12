# Hemovue
 Intelligent Hemorrhage Detection from CT Scans using Machine Learning

HemoVue is an AI-powered diagnostic tool designed to detect brain hemorrhages from CT scan images. By combining medical imaging with demographic insights, this project evaluates multiple machine learning models to identify the most effective approach for real-world clinical use.

Overview

Early and accurate detection of brain hemorrhage is vital for patient care. Manual analysis of CT scans can be slow and subjective. HemoVue aims to assist radiologists by automating hemorrhage classification through data-driven insights.

Objectives

Build a machine learning pipeline to classify hemorrhage from CT scans.

Compare six ML models to determine the best-performing ones.

Integrate imaging features with patient demographics for enhanced accuracy.

Ensure robust evaluation using cross-validation and regularization techniques.

Models Evaluated

Logistic Regression

Support Vector Machine (SVM)

Random Forest

Gradient Boosting

XGBoost

Artificial Neural Network (ANN)

Top Performers: XGBoost and Neural Network delivered the highest accuracy and lowest log loss values.

Methodology

Data Preprocessing

Normalization of CT images

Encoding categorical demographic variables

Handling missing values

Training Strategy

Stratified k-fold cross-validation

Model-specific hyperparameter tuning

Regularization to control overfitting

Evaluation Metrics

Accuracy

Log Loss

Precision / Recall / F1-score

Confusion Matrix

Experimental Results

Model	Accuracy	Log Loss	Notes
Logistic Regression	Moderate	Higher	Performs poorly with complex features
SVM	Lower	Higher	Underperformed overall
Random Forest	Good	Moderate	Balanced but slower
Gradient Boosting	High	Low	Strong performance
XGBoost	High	Low	Most stable and accurate
Neural Network	Very High	Slightly Higher	Near-perfect accuracy

Dataset

This project uses the CT Scans for Hemorrhage Detection dataset from Kaggle, which contains thousands of brain scan images labeled for hemorrhage presence.

Dataset link: https://www.kaggle.com/datasets/vbookshelf/computed-tomography-ct-images

Dataset structure:
dataset/
├── hemorrhage/
│ ├── img1.png
│ ├── ...
├── no_hemorrhage/
├── img1.png
└── ...

Demo

CT Image Input	Prediction
sample1.png	Hemorrhage
sample2.png	No Hemorrhage

Replace with your actual result images.

Key Highlights

Dual-Modal Data Fusion: Combines demographic data with image-based features.

Model Comparison: Benchmarks six ML models under identical conditions.

Top Accuracy: Neural Net and XGBoost deliver strong predictive power.

Scalable Pipeline: Can be extended to multi-class classification or 3D CT slices.

Future Scope

Multi-class Hemorrhage Detection (e.g., subdural, epidural)

3D Volumetric Analysis across CT slices

Transfer Learning from pre-trained CNNs

Attention Mechanisms to focus on bleeding areas

GAN-based Data Augmentation for rare case synthesis

Deployment via Flask or Streamlit

Requirements

Install dependencies using:

pip install -r requirements.txt

Packages used:

TensorFlow

Keras

NumPy

OpenCV

Matplotlib

scikit-learn

How to Run

Clone this repository:
git clone https://github.com/your-username/hemovue.git
cd hemovue

Add your dataset under the dataset/ directory.

Run the Jupyter notebook:
jupyter notebook hemorrhage_detection.ipynb

Train models and view output predictions.

License

This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements

Kaggle dataset: CT Brain Images (https://www.kaggle.com/datasets/vbookshelf/computed-tomography-ct-images)

TensorFlow and Keras open-source frameworks

Contact

For questions or collaborations, reach out via GitHub: https://github.com/your-username
