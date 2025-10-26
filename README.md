<img width="1411" height="792" alt="Power BI Dashboard" src="https://github.com/user-attachments/assets/1c04491c-eedf-47e8-81d1-419924c85c42" /># 🩺 Healthcare Appointment No-Show Prediction using Machine Learning and Power BI

## 📘 Introduction
Patient no-shows are a major issue in healthcare systems, leading to wasted time, resources, and financial losses. This project aims to predict whether a patient will attend their scheduled medical appointment using machine learning. By leveraging predictive analytics, hospitals can optimize scheduling and resource allocation, improving overall efficiency and patient care.

---

## 🧠 Abstract
This project focuses on predicting healthcare appointment no-shows using a Decision Tree classifier in Python. The dataset contains information such as patient age, gender, appointment date, and SMS reminders. After cleaning and preprocessing the data, the model predicts the likelihood of a patient missing their appointment. The insights are visualized in **Power BI**, helping healthcare providers understand key factors that influence attendance.

---

## 🧰 Tools Used
- **Python** – Data preprocessing, analysis, and model training  
- **Pandas & NumPy** – Data manipulation and transformation  
- **Scikit-learn** – Building and evaluating the Decision Tree classifier  
- **Matplotlib & Seaborn** – Data visualization in Python  
- **Power BI** – Dashboard creation for insight visualization  

---

## ⚙️ Steps Involved in Building the Project
1. **Import and clean the dataset** – Handle missing data, remove duplicates, and correct inconsistencies  
2. **Exploratory Data Analysis (EDA)** – Understand relationships between variables and identify key influencing factors    
3. **Model Building** – Train a **Decision Tree** model to predict appointment no-shows  
4. **Model Evaluation** – Assess performance using accuracy, precision, recall, and confusion matrix  
5. **Visualization with Power BI** – Create dashboards to analyze trends like age, weekday, SMS reminders, and attendance rates  

---

## 📊 Dashboard Overview
The **Power BI dashboard** provides interactive insights including:
- Patient attendance by age, gender, and day of the week  
- Impact of SMS reminders on show-up rates  
- Appointment trends and prediction accuracy  



## 💻 Jupyter Notebook
The **Python notebook** contains all steps from data preprocessing to model evaluation.  
_File: `Python_notebook.ipynb`_

---

## ✅ Conclusion
The model successfully predicts patient no-shows with a high degree of accuracy, helping healthcare providers reduce missed appointments. Integrating these predictive results with Power BI enables better scheduling decisions and efficient use of medical resources.


## 📂 Project Structure
├── Python_notebook.ipynb # Machine learning notebook
├── Healthcare Appointment No-Show Dashboard.pbix # Power BI dashboard
├── Power BI Dashboard.png # Dashboard png
├── Healthcare Appointment No-Show Prediction Report # Project documentation
└── Dataset (Medical Appointment.csv) # Source dataset 
