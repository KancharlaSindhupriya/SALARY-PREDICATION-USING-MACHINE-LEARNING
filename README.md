# 💼 Salary Predictor using Machine Learning & Flask

This project predicts the **salary of an employee** based on their **years of experience**, using a trained Machine Learning model served with **Flask**.

## 📌 Overview

🧠 **Model**: Simple Linear Regression
🧪 **Dataset**: Experience vs Salary dataset (CSV format)
⚙️ **Backend**: Python, Flask
📦 **Model Deployment**: Pickle 
🌐 **Web App**: Lightweight Flask application to take user input and return predicted salary

## 📈 Model

* `model.py` reads the CSV data, trains a **Linear Regression** model, and saves it as `model.pkl`.
* You can retrain the model by running:
python model.py

## 🚀 How to Run the App

### ✅ Prerequisites

* Python 3.x
* Flask
* scikit-learn
* pandas
* pickle

### ⚙️ Setup

1. Clone the repository:

git clone https://github.com/yourusername/flask-salary-predictor.git

cd flask-salary-predictor

2. Install dependencies:

pip install -r requirements.txt


3. Run the Flask App:

python app.py

4. Open browser and go to:
   👉 `http://127.0.0.1:5000/`

## 🌐 App UI

* Enter years of experience
* Click **Predict**
* Get predicted salary in seconds!

## 📦 Example Input & Output

* **Input**: 3 years of experience
* **Output**: Predicted Salary → ₹45,000 (example)

## 👨‍💻 Author

**Sindhupriya Kancharla**
📧 [sindhupriyakancharla04@gmail.com](mailto:sindhupriyakancharla04@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/sindhu-priya-kancharla-0b6666217/)
🔗 [GitHub](https://github.com/KancharlaSindhupriya)



