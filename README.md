🧠 HemoVue
Hemorrhage Detection from Brain CT Scans using Machine Learning

HemoVue is an AI-based tool that automates the detection of brain hemorrhages from CT scan images using machine learning. It integrates imaging and patient demographic data to improve diagnostic accuracy.

🔍 Project Highlights
Built and evaluated 6 ML models: Logistic Regression, SVM, Random Forest, Gradient Boosting, XGBoost, Neural Network.

Best models: XGBoost and Neural Network showed the highest accuracy.

Uses CT scan data and patient demographics for prediction.

Evaluation based on accuracy, log loss, precision, recall, and F1-score.

📁 Dataset
Source: Kaggle – CT Brain Images

Binary classification: hemorrhage/ and no_hemorrhage/

Copy
Edit
dataset/
├── hemorrhage/
├── no_hemorrhage/
🧪 How to Run
Clone this repo:

bash
Copy
Edit
git clone https://github.com/your-username/hemovue.git
cd hemovue
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:

bash
Copy
Edit
jupyter notebook hemorrhage_detection.ipynb
🛠️ Tech Stack
Python, TensorFlow, Keras

NumPy, OpenCV, Matplotlib

scikit-learn

🚀 Future Scope
Multi-class hemorrhage classification

3D CT scan support

Web deployment using Streamlit or Flask
 

🙌 Acknowledgements
Kaggle Dataset

TensorFlow, Keras community
