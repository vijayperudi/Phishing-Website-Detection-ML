# Phishing-Website-Detection-Using SVM and Light GBM
Detect phishing websites using machine learning based on URL features. Includes model training, prediction script, and dataset for end-to-end detection.
📌 About the Project
A machine learning-based web utility that detects whether a given website is legitimate or phishing. This classification is performed using two powerful ML algorithms: Support Vector Machine (SVM) and Light Gradient Boosting Machine (LightGBM). The models are trained on website features such as URL structure, domain information, and site behavior.

The goal is to help users or systems identify potentially harmful websites before they can do damage.

🧰 Technologies
Python

Jupyter Notebook

Scikit-learn

LightGBM

Pandas

NumPy

Matplotlib & Seaborn (for visualization)

Machine Learning Algorithms:

Support Vector Machine (SVM)

LightGBM

📚 Libraries Used
scikit-learn

lightgbm

pandas

numpy

matplotlib

seaborn

📂 Dataset Used
Phishing Website Dataset

Contains multiple features like:

URL length

Use of HTTPS

Having IP in URL

Redirect count

Anchor tag links

Domain age

and more...

✅ Available on UCI Repository or Kaggle

⚙️ How It Works
The dataset is loaded and preprocessed.

Features are extracted from each website record.

Data is split into training and testing sets.

Both SVM and LightGBM models are trained.

Performance is evaluated using accuracy, F1-score, and confusion matrix.

Feature importance is visualized.

The better-performing model is saved for deployment or API integration.

📊 Output
After training the models, the application will:

Predict whether a site is Phishing or Legitimate

Show accuracy, precision, recall, and ROC-AUC score

Display feature importance

📸 Screenshots
📍 Initial Data Analysis
Insert image of dataset preview or feature distribution here

📍 Model Training Output
Insert image of training accuracy and confusion matrix

📍 Final Results
Insert image of comparison between SVM and LightGBM performance

🚀 Run Locally
bash
Copy
Edit
git clone https://github.com/yourusername/phishing-detection-svm-lightgbm.git
cd phishing-detection-svm-lightgbm
pip install -r requirements.txt
jupyter notebook
🌐 Live Demo (Optional)
[Upload a notebook on Google Colab or deploy model via Flask for live demo]

Let me know if you'd like:

A ZIP file of this project

Code and notebook with visualizations

Architecture diagram for GitHub image section

I can generate or edit these too.











Tools


