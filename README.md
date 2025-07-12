 

#  HemoVue

**Hemorrhage Detection from Brain CT Scans using Machine Learning**

**HemoVue** is an AI-driven solution for detecting brain hemorrhages from CT scan images. By combining imaging features with patient demographics, it improves diagnostic accuracy using multiple machine learning models.

---

## Highlights

* Trained and compared 6 ML models:
  Logistic Regression, SVM, Random Forest, Gradient Boosting, XGBoost, Neural Network
* **Top performers:** XGBoost and Neural Network
* Metrics: Accuracy, Log Loss, Precision, Recall, F1-Score
* Dataset includes labeled CT scans for binary classification (hemorrhage / no hemorrhage)

---

##  Dataset

**Source:** [Kaggle - CT Brain Images](https://www.kaggle.com/datasets/vbookshelf/computed-tomography-ct-images)
**Structure:**

```
dataset/
├── hemorrhage/
├── no_hemorrhage/
```

---

##  How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/hemovue.git
cd hemovue
```

2. Install required libraries:

```bash
pip install -r requirements.txt
```

3. Launch the notebook:

```bash
jupyter notebook hemorrhage_detection.ipynb
```

---

##  Tech Stack

* Python
* TensorFlow, Keras
* NumPy, OpenCV, Matplotlib
* scikit-learn

---

##  Future Enhancements

* Multi-class hemorrhage detection (e.g., subdural, epidural)
* 3D CT scan analysis
* Web deployment using Streamlit or Flask

---

## 🙌 Acknowledgements

* [CT Brain Images – Kaggle Dataset](https://www.kaggle.com/datasets/vbookshelf/computed-tomography-ct-images)
 
---
 
