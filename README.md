# ML-Project
# 📊 Student Attendance Prediction and Recommendation System

---

## 🎯 Problem Statement

The objective of this project is to analyze student-related data and predict attendance using Machine Learning and Deep Learning models. Based on the prediction results, a recommendation system is developed to provide personalized suggestions to improve student performance and engagement.

---

## ⚙️ Pipeline Diagram

Data Collection → Data Preprocessing → Feature Scaling → Train-Test Split → Machine Learning Models → Deep Learning Model → Evaluation → Recommendation System

---

## 📂 Dataset Details

- **Source:** Synthetic dataset
- **Description:**
  The dataset contains various student attributes such as:
  - Age
  - Gender
  - Course
  - Year
  - Parent Education
  - Internet Access
  - Study Hours
  - Sleep Hours
  - Travel Time
  - Attendance (Target Variable)

---

## 🤖 Model Details

### 🔹 Machine Learning Models
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest (Ensemble Model)  
- Support Vector Machine (SVM)  
- Naive Bayes  

### 🔹 Deep Learning Model (Final Model)
- Artificial Neural Network (ANN)
  - Dense layers with ReLU activation
  - Sigmoid output layer
  - Dropout used to reduce overfitting

---

## 📊 Model Comparison

Random Forest is used as the baseline ensemble model.  
The Neural Network model is compared against it to evaluate performance improvement.

---

## ▶️ Steps to Run the Project

1. Clone the repository:
https://github.com/prithvivortex-collab/ML-Project

2. Open the project in Google Colab or Jupyter Notebook

3. Install required libraries:
pip install -r requirements.txt

4. Run all cells in the notebook to:
- Preprocess data
- Train ML and DL models
- Evaluate performance
- Generate recommendations

---

## 📦 Required Dependencies

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

---

## 📸 Sample Outputs

Model accuracy results
<img width="779" height="354" alt="image" src="https://github.com/user-attachments/assets/1da0a522-fb6a-48cd-92c9-1a3b3fb3e0e6" />
Classification report
<img width="756" height="251" alt="image" src="https://github.com/user-attachments/assets/1d23075e-e863-4b47-b041-1388602ec67b" />
Neural network training output
<img width="943" height="74" alt="image" src="https://github.com/user-attachments/assets/92a7c58e-1463-473d-aa9c-9651159fcf09" />
Model comparison (Random Forest vs Neural Network)
<img width="772" height="123" alt="image" src="https://github.com/user-attachments/assets/99dcba09-dffd-4076-91ee-26ddc142bbc7" />
Student recommendation output
<img width="696" height="989" alt="image" src="https://github.com/user-attachments/assets/23a2e32e-18f4-4ace-a391-408b49149451" />

---

## 👨‍💻 Team Members

- Jai Prithvi B (24BIT043)
- Hariprasath M (24BIT039)
- Hariharan S (24BIT037)

---

## 🏆 Conclusion

This project successfully integrates Machine Learning and Deep Learning techniques to analyze student behavior, predict attendance, and generate personalized recommendations. The deep learning model demonstrated improved performance compared to baseline models.
