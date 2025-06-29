# REVOLUTIONIZING-LIVER-CASE-PREDICTING-LIVER-CIRRHOSIS-USING-ADVANCED-MACHINE


🧠 REVOLUTIONIZING LIVER CASE: Predicting Liver Cirrhosis Using Advanced Machine Learning

A machine learning-powered web app designed to predict liver cirrhosis risk based on biochemical attributes.
This intelligent tool uses a Random Forest Classifier to analyze patient health data and deliver real-time, accurate predictions via a simple web interface.


---

🚨 Use Case:

Helps doctors and healthcare professionals assess liver disease risks quickly.

Patients can self-check liver health risk based on test reports.

Aims to support early diagnosis and reduce manual errors in interpretation.



---

🧪 How It Works

1. 🔢 Enter medical attributes like bilirubin, albumin, enzymes, etc.


2. 🤖 Model processes the input using trained machine learning logic.


3. 📊 Prediction is shown whether the user is at high or low risk of liver cirrhosis.




---

🚀 Features

✅ Real-time prediction with Random Forest Classifier
✅ Clean and simple UI (can be hosted via Streamlit)
✅ High accuracy (100% on training data)
✅ Easy deployment using Google Colab and GitHub
✅ Model saved and reused via .pkl files


---

🧰 Tech Stack

Layer	Tools Used

👨‍💻 Backend	Python, Scikit-learn (Random Forest), Pandas
📦 ML Tools	Random Forest, Normalizer, Joblib
📊 IDE/Training	Google Colab
🌐 Version Control	GitHub
📺 Deployment (optional)	Streamlit Cloud



---

📂 Project Structure

📁 Liver_Cirrhosis_Prediction
├── data/
│   └── indian_liver_patient.csv
├── model/
│   ├── liver_model.pkl
│   └── normalizer.pkl
├── app.py
├── requirements.txt
├── README.md


---

💻 Run Locally

Clone the repository:

git clone https://github.com/MaheshReddy-7/REVOLUTIONIZING-LIVER-CASE-PREDICTING-LIVER-CIRRHOSIS-USING-ADVANCED-MACHINE.git
cd REVOLUTIONIZING-LIVER-CASE-PREDICTING-LIVER-CIRRHOSIS-USING-ADVANCED-MACHINE

Create a virtual environment and activate it:

python -m venv venv
venv\Scripts\activate  # For Windows
source venv/bin/activate  # For macOS/Linux

Install the dependencies:

pip install -r requirements.txt

Run the app (if using Streamlit or Flask):

streamlit run app.py
# or
python app.py


---

🧪 Model Accuracy

Achieved 100% accuracy on training data

Requires real-world validation for deployment in clinical scenarios


---

🌟 Future Enhancements

Add visual input (e.g., ultrasound images)

Expand dataset diversity for broader accuracy

Create a mobile app for patients

Integrate with hospitals and diagnostic centers



---
📋 Stages of the Project

1. Data Collection and Preprocessing


2. Feature Selection and Normalization


3. Training Random Forest Classifier


4. Saving the Model and Normalizer as .pkl files


5. Front-End Interface (optional: Streamlit)


6. Integration and Prediction Flow




---

📂 Dataset

Source: Indian Liver Patient Dataset (ILPD)

Total Records: 583 patients

Attributes: Age, Gender, Total Bilirubin, Direct Bilirubin, Alkaline Phosphotase, etc.

Stored in:
/data/indian_liver_patient.csv


Example class mapping:

{ "low risk": 0, "high risk": 1 }
----
🧪 Technologies Used

Python

Scikit-learn (Random Forest)

Pandas, NumPy

Google Colab (for training)

Flask / Streamlit (optional frontend)

GitHub



---

📊 Model Performance

✅ Accuracy: 100% on training data

⚠️ Requires external validation for clinical deployment

🔍 Model used: RandomForestClassifier from sklearn

💾 Saved files: liver_model.pkl, normalizer.pkl
---
🎯 Context

Liver Cirrhosis is a chronic condition that can go undiagnosed in early stages.
This project helps solve the problem by:

Automating prediction using biochemical attributes

Providing early warnings for liver health risks

Assisting doctors and health workers with decision-making
