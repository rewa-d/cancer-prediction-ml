# 🧠 Cancer Detection and Classification using Machine Learning

## Highlights
- Built end-to-end machine learning pipelines for classification tasks  
- Applied both traditional ML and deep learning techniques  
- Developed deployable applications using Flask and Streamlit  
- Worked with structured (CSV) and image-based datasets  

---

## 📌 Overview
This project focuses on detecting and classifying cancer using machine learning techniques. It includes two modules:

- Lung Cancer Risk Prediction using structured survey data  
- Blood Cancer Cell Classification using deep learning on image data  

The project demonstrates the complete workflow from **data preprocessing to model deployment**.

---

## 🎯 Objectives
- Predict lung cancer risk using patient data  
- Classify blood cancer cell types from images  
- Apply ML and deep learning models  
- Build simple applications for real-time predictions  

---

## 📁 Project Modules

### 🌬️ Lung Cancer Risk Prediction
- Used survey dataset to predict cancer likelihood  
- Performed data cleaning, encoding, and feature scaling  
- Implemented models:
  - K-Nearest Neighbors (KNN)  
  - Support Vector Machine (SVM)  
  - Logistic Regression  
- Evaluated using accuracy and confusion matrix  

---

### 🩸 Blood Cancer Cell Classification
- Built CNN model for image classification  
- Applied preprocessing and normalization  
- Classified different blood cell types  
- Generated predictions with probability scores  

---

## 🌐 Applications

### 📊 Flask App (Lung Cancer Prediction)
- User inputs health-related data via form  
- Loads trained ML model and scaler  
- Predicts cancer risk in real-time  

---

### 🖼️ Streamlit App (Blood Cancer Classification)
- Upload image of blood cell  
- Model predicts cell type using CNN  
- Displays prediction with confidence score  

---

## 🧱 Project Structure

```bash
cancer-detection-machine-learning/
│
├── blood_cancer/
│   ├── BloodCancer.ipynb
│   ├── app_IMG.py
│   └── dataset/
│
├── lung_cancer/
│   ├── LungCancer.ipynb
│   ├── app_CSV.py
│   ├── survey_lung_cancer.csv
│   └── templates/
│       └── index.html
│
├── screenshots/
│   ├── BloodCancer.ipynb
│   ├── app_IMG.py
│   └── dataset/ 
├── requirements.txt
└── README.md

```
---

## 🧰 Tech Stack

**Programming Language**
- Python  

**Libraries**
- Pandas, NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- OpenCV  

**Visualization**
- Matplotlib  
- Seaborn  

**Deployment**
- Flask  
- Streamlit  

---

## 📊 Key Outcomes
- Developed classification models for cancer prediction  
- Applied deep learning for image-based classification  
- Evaluated models using standard metrics  
- Built deployable applications for real-time use  

---

## 🚀 How to Run

### 1. Clone the Repository
git clone https://github.com/your-username/cancer-prediction-ml.git
cd cancer-prediction-ml

### 2. Install Dependencies
pip install -r requirements.txt

### 3. Run Jupyter Notebooks
jupyter notebook

Open:
- blood_cancer/BloodCancer.ipynb
- lung_cancer/LungCancer.ipynb

### 4. Run Flask App (Lung Cancer Prediction)
cd lung_cancer
python app_CSV.py

Open in browser:
http://127.0.0.1:5000

### 5. Run Streamlit App (Blood Cancer Classification)
cd blood_cancer
streamlit run app_IMG.py

---

## 📸 Screenshots

To be added soon.

---

## 📢 Notes
- Trained model files are not included due to size limitations  
- Models can be shared upon request  

---

## 👩‍💻 Author
Rewa Dambal  
GitHub: https://github.com/rewa-d
