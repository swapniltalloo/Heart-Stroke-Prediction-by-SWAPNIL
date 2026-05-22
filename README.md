Heart Stroke Prediction System

A Machine Learning based Heart Stroke Prediction Web Application built using Python, Streamlit, and Scikit-Learn.

This application predicts whether a person has a High Risk or Low Risk of heart disease using medical parameters.

---

Features

- Interactive Streamlit Web App
- Real-time Heart Disease Prediction
- Machine Learning Model using KNN
- Clean and Responsive UI
- Feature Scaling using StandardScaler
- One-Hot Encoding for Categorical Features
- Model Persistence using Joblib
- Compared Multiple Classification Algorithms

---

Technologies Used

- Python
- Streamlit
- Pandas
- Scikit-Learn
- Joblib
- KNN Classifier

---

Project Structure

```bash
Project1/
│── app.py
│── heart.csv
│── knn_heart_model.pkl
│── heart_scaler.pkl
│── heart_columns.pkl
│── HeartdiseaseFinal.ipynb
│── README.md
```

---

Installation

Clone the Repository

```bash
git clone https://github.com/your-username/heart-stroke-prediction.git
```

Navigate to the Folder

```bash
cd heart-stroke-prediction
```

Create Virtual Environment

```bash
python -m venv .venv
```

Activate Virtual Environment

Windows

```bash
.venv\Scripts\activate
```

Mac/Linux

```bash
source .venv/bin/activate
```

---

Install Dependencies

```bash
pip install streamlit pandas scikit-learn joblib matplotlib
```

---

Run the Application

```bash
streamlit run app.py
```

Then open:

```bash
http://localhost:8501
```

---

Input Features

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak
- ST Slope

---

Machine Learning Workflow

Data Preprocessing

- One-Hot Encoding
- Feature Scaling using StandardScaler

Classification Algorithms Used

Different Machine Learning classification algorithms were tested and compared, including:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

After evaluating model performance, K-Nearest Neighbors (KNN) was selected because it provided the best accuracy and prediction performance for this dataset.

Model Saving

- knn_heart_model.pkl
- heart_scaler.pkl
- heart_columns.pkl

---

Prediction Output

- High Risk of Heart Disease
- Low Risk of Heart Disease

---

Future Improvements

- Add More ML Models
- Deploy on Streamlit Cloud
- Add Prediction Probability
- Improve UI/UX
- Add Data Visualization Dashboard

---

Author

SWAPNIL TALLOO

BTech Electronics & Computer Science Student  
Passionate about Machine Learning and Software Development

---

Support

If you like this project, give it a star⭐ on GitHub!
