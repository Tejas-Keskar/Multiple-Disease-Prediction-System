# **Multiple Disease Prediction System**  
*A Machine Learning-powered web application for predicting multiple diseases using patient data.*  

## 📌 **Overview**  
The **Multiple Disease Prediction System** is a machine learning-based application that predicts the likelihood of various diseases, including:  
✅ **Diabetes**  
✅ **Heart Disease**  
✅ **Parkinson's Disease**  
✅ **Breast Cancer**  

Built with **Python, Machine Learning, and Streamlit**, this project provides an **easy-to-use web interface** where users can input their medical data and get real-time predictions.  

---

## 📜 **Features**  
✔ **Early Disease Detection**: Uses machine learning models to predict diseases at an early stage.  
✔ **User-Friendly Interface**: Built with **Streamlit** for an intuitive web experience.  
✔ **Multi-Disease Prediction**: Supports multiple diseases with dedicated models.   

---

## 🛠 **Technologies Used**  
- **Python** 🐍  
- **Scikit-learn** (Machine Learning)  
- **Pandas & NumPy** (Data Processing)  
- **Streamlit** (Web App Development)  
- **Pickle** (Model Serialization)  

---

## ⚙️ **Installation & Setup**  
### 🔹 **Prerequisites**  
Make sure you have **Python 3.x** installed. You can download it from [Python.org](https://www.python.org/downloads/).  

### 🔹 **Install Required Packages**  
Run the following command to install dependencies:  
```sh
pip install -r requirements.txt
```
If requirements.txt is not available, manually install the required libraries:
```sh
pip install pandas numpy scikit-learn streamlit
```

### 🔹 **Run the Application** 
After installing the dependencies, execute:
```sh
streamlit run app.py
```
This will launch the Multiple Disease Prediction System in your web browser.

## 📊 Machine Learning Models Used  
The application uses different machine learning models for predicting diseases:  

| **Disease Type**        | **ML Model Used**              |
|-------------------------|--------------------------------|
| **Diabetes**           | Support Vector Machine (SVM)    |
| **Heart Disease**      | Logistic Regression             |
| **Parkinson's Disease**| Support Vector Machine (SVM)    |
| **Breast Cancer**      | Logistic Regression             |

Each model is **trained on medical datasets** and optimized for accuracy.  

---

## 🖥️ Web Interface (Streamlit)  
The **Streamlit-based web app** provides an **interactive UI** for users to:  
- **Input medical parameters** related to their health  
- **Get real-time disease predictions**  
- **View probability scores** for each disease  

---

## 📝 How It Works?  
1️⃣ **The user selects a disease prediction module** (e.g., Diabetes, Heart Disease, etc.).  
2️⃣ **They enter medical details** (e.g., blood pressure, glucose levels, etc.).  
3️⃣ **The system processes the input using trained ML models.**  
4️⃣ **Prediction is displayed instantly with probability scores.**  

---

## 💡 Future Enhancements  
🔹 **Improve Model Accuracy** by using advanced deep learning techniques.  
🔹 **Integrate More Diseases** to expand predictive capabilities.  
🔹 **Real-time Data Integration** for continuously updated predictions.  
🔹 **Mobile-Friendly UI** for better accessibility.  

---

## 📞 Contact  
If you have any questions or suggestions, feel free to reach out:  
📧 **Email:** keskartejas01@gmail.com  
📌 **LinkedIn:** https://github.com/Tejas-Keskar
