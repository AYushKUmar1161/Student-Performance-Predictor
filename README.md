# Student-Performance-Predictor
# 📊 Student Performance Prediction - Machine Learning

This project applies various machine learning classification models to analyze and predict factors that influence student performance. The dataset includes multiple features such as nationality, grade level, number of hands raised in class, attendance, and hours studied.

The goal is to determine which factors most significantly impact student grades and visualize the performance of different ML models.

---

## 📁 Dataset

- Format: CSV
- Features include:
  - Nationality
  - Grade level
  - Number of hands raised
  - Attendance
  - Study hours
  - Class participation, etc.
- Target: Student final grade/performance level

---

## 🧠 ML Models Used

The following classifiers were implemented and compared:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)

---

## 📈 Visualizations

To better understand model performance and data distribution, the project includes:

- Confusion Matrices  
- Accuracy Scores  
- Feature Importance Graphs  
- Correlation Heatmap

---

## 🛠️ Tech Stack

- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-Learn  

---

## 🔍 Key Findings

- Models were evaluated on accuracy and generalization capability.  
- Behavioral factors like **attendance** and **study hours** showed strong correlation with grades.  
- Ensemble models such as **Random Forest** performed best in this case.

---

🚀 Getting Started
Clone this repository:

bash
Copy
Edit
git clone https://github.com/AYushKUmar1161/StudentPerformancePrediction-ML.git
cd StudentPerformancePrediction-ML
Install dependencies:

nginx
Copy
Edit
pip install -r requirements.txt
Run the notebook or script:

css
Copy
Edit
python main.py
Or open the Jupyter notebook:

nginx
Copy
Edit
jupyter notebook StudentPerformancePrediction.ipynb


📌 To Do
Hyperparameter tuning

Model deployment (Flask or Streamlit)

Add support for user-uploaded CSV files

📄 License
This project is licensed under the MIT License.

👨‍💻 Author
Ayush Kumar


