📘 Overview

The Heart Disease Prediction System is a machine learning application designed to predict the likelihood of a patient having heart disease based on medical features such as age, cholesterol level, and resting blood pressure.
It uses a Random Forest Classifier trained on clinical datasets and provides an interactive Streamlit web interface for user input and real-time prediction.


🎯 Objectives
To demonstrate the practical application of machine learning in medical diagnostics.

To provide a simple and accurate system for early detection of heart disease risk.

To implement a user-friendly prediction dashboard using Streamlit.



⚙️ Features 

✅ Accepts medical input data such as age, blood pressure, cholesterol, etc.
✅ Preprocesses and scales input data for model prediction.
✅ Uses a trained Random Forest model for classification.
✅ Displays prediction results in an intuitive web app interface.
✅ Easy to extend with additional models or datasets.



🧰 Tech Stack

Category	Tools / Libraries
Programming Language	Python
Data Analysis	Pandas, NumPy
Machine Learning	Scikit-learn
Visualization	Matplotlib, Seaborn
Web App	Streamlit
Model Storage	Pickle (random_forest_model.pkl)


🧠 Dataset

The dataset used in this project contains various medical features associated with heart disease diagnosis, including:

Age

Sex

Chest pain type

Resting blood pressure

Cholesterol level

Fasting blood sugar

Maximum heart rate achieved

Exercise-induced angina

Oldpeak (ST depression)

Slope, Ca, Thal

(Dataset source: UCI Heart Disease Dataset
 or equivalent open-source dataset.)



📈 Model Training

The notebook Heart Disease Prediction.ipynb includes:

Data cleaning and preprocessing

Feature correlation analysis

Model training using Random Forest Classifier

Accuracy evaluation and confusion matrix visualization

Model export via Pickle (random_forest_model.pkl) for deployment

Final Model Accuracy: ~88–90% (varies with dataset split)



🚀 How to Run Locally

Clone this repository:

git clone https://github.com/<your-username>/heart-disease-prediction-system.git
cd heart-disease-prediction-system


Install required packages:

pip install -r requirements.txt


Run the Streamlit app:

streamlit run Heart_Disease_Prediction.ipynb


or (if you have a dedicated app.py):

streamlit run main.py


Open your browser and visit
👉 http://localhost:8501



🧾 Requirements

All dependencies are listed in requirements.txt.
Key libraries include:

pandas

numpy

scikit-learn

streamlit

matplotlib

seaborn

joblib



🧪 Example Prediction

Feature	Example Input
Age	54
Sex	Male
Cholesterol	250
Resting BP	130
Max Heart Rate	150

Model Output:

The patient is likely at risk of heart disease. (Predicted class: 1)



🔮 Future Improvements

Add more advanced models (XGBoost, Neural Networks).

Integrate database for saving user input and results.

Deploy as a web service on Render or Streamlit Cloud.

Include detailed interpretability metrics (SHAP, LIME).



👨🏾‍💻 Author

Chukwuedo Emmanuel Ikechukwu
Computer Science Graduate | Machine Learning & AI Enthusiast
📍 Lagos, Nigeria



This project is licensed under the MIT License — free for educational and open-source use.
