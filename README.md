# Phishing-Website-Detection-Using SVM and Light GBM
Detect phishing websites using machine learning based on URL features. Includes model training, prediction script, and dataset for end-to-end detection.
Phishing-Website-Detection-ML/
├── dataset/ → Contains the dataset CSV
├── models/ → Trained ML model
├── notebooks/ → Jupyter notebook for EDA and training
├── src/ → Python scripts
│ ├── train_model.py → Model training script
│ └── predict.py → Predict phishing from URL
├── requirements.txt → Required packages
├── README.md → Project documentation
└── architecture.png → Architecture diagram

🔍 Features
Extracts meaningful features from URLs

Detects phishing vs legitimate websites

Uses Random Forest Classifier

Includes training and prediction scripts

Clean architecture and reusable code

📦 Installation
bash
Copy
Edit
git clone https://github.com/<your-username>/Phishing-Website-Detection-ML.git  
cd Phishing-Website-Detection-ML  
pip install -r requirements.txt
📊 Dataset
Dataset: UCI Phishing Websites Data Set
URL: https://archive.ics.uci.edu/ml/datasets/phishing+websites
Place it as: dataset/phishing_dataset.csv

🧠 Model Training
bash
Copy
Edit
python src/train_model.py
This creates phishing_model.pkl in the models/ directory.

🔍 URL Prediction
bash
Copy
Edit
python src/predict.py "http://example.com"
Output: Phishing or Legitimate

🖼️ Architecture Diagram

🛠️ Technologies Used
Python

Scikit-learn

Pandas, NumPy

Joblib

Jupyter Notebook
