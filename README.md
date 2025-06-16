# Phishing-Website-Detection-Using SVM and Light GBM
Detect phishing websites using machine learning based on URL features. Includes model training, prediction script, and dataset for end-to-end detection.
✨ About the Project
A machine learning-based web utility that detects whether a website is legitimate or phishing. This project uses two powerful classification models:

Support Vector Machine (SVM)

Light Gradient Boosting Machine (LightGBM)

The models are trained on features extracted from URLs and domain behaviors such as HTTPS presence, IP usage, domain age, and redirection counts.

This project aims to help users and systems avoid phishing scams by automatically classifying websites using trained ML models.

💻 Technologies Used
Python

Jupyter Notebook

Scikit-learn

LightGBM

Pandas

NumPy

Matplotlib & Seaborn (for data visualization)

📦 Libraries Used
scikit-learn

lightgbm

pandas

numpy

matplotlib

seaborn

🗂️ Dataset Used
Phishing Website Dataset containing multiple features like:

URL length

Use of HTTPS

Having IP in URL

Redirect count

Anchor tag links

Domain age

DNS record availability

📌 Available on UCI Machine Learning Repository or Kaggle.

⚙️ How It Works
Load and preprocess the dataset.

Split the data into training and test sets.

Train SVM and LightGBM classifiers.

Evaluate both models using metrics like:

Accuracy

Precision & Recall

F1-Score

Confusion Matrix

ROC-AUC

Visualize feature importance and model performance.

Save the best-performing model for deployment or reuse.

📊 Output
Once training is completed, the model will:

Predict whether a website is Phishing or Legitimate

Display key performance metrics

Provide feature importance chart to explain influential variables

🧪 Screenshots
🔹 Initial Data Analysis
(Insert image showing feature distribution or class balance)

🔹 Model Training
(Insert confusion matrix or model comparison chart)

🔹 Final Output
(Insert classification result or UI showing prediction)

🚀 Run Locally
bash
Copy
Edit
# Clone the repository
git clone https://github.com/yourusername/phishing-detection-svm-lightgbm.git
cd phishing-detection-svm-lightgbm

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook
🌐 Live Demo
👉 You can test this notebook live on Google Colab
(Upload your notebook and link here if available)

Let me know if you want:

Code ZIP file

Full notebook with visuals

Deployment setup (Flask/Streamlit)

Architecture diagram to include in this README
![image](https://github.com/user-attachments/assets/cf53e831-286c-4095-ad54-d00aa13f275d)

















