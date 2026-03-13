# ❤️ Heart Disease Prediction System

## 📌 Project Statement

Heart disease is one of the most common and dangerous health problems worldwide.
The goal of this project is to develop a **Machine Learning based Heart Disease Prediction System** that predicts whether a patient is likely to have heart disease based on medical data.

The model learns patterns from historical healthcare datasets and predicts the risk of heart disease for new patient data.

---

# 🌐 Live Web Application

⚠️ This application runs locally using **Streamlit**.

Run the following command in the project directory:

```bash
streamlit run app.py
```

After running the command, open this link in your browser:

```
http://localhost:8501/#heart-disease-prediction-system
```

---

# 🎥 Demo Video

Watch the working demo of the Heart Disease Prediction Web App.

<video src="demo_video.mp4" controls width="750"></video>

---

# 📂 Project Structure

```text
Heart-Disease-Prediction/
│
├── app.py
│   └── Streamlit web application for heart disease prediction
│
├── heart.csv
│   └── Dataset used for training the machine learning model
│
├── Heart_disease_prediction.ipynb
│   └── Jupyter Notebook containing data analysis, preprocessing,
│       model training, and evaluation
│
├── requirements.txt
│   └── List of Python libraries required to run the project
│
├── demo_video.mp4
│   └── Screen recording demonstrating how the web app works
│
└── README.md
    └── Project documentation and usage instructions
```

---

# 📥 Input Features

The model uses the following patient medical attributes as input:

| Feature  | Description                          |
| -------- | ------------------------------------ |
| age      | Patient's age                        |
| sex      | Gender (male/female)                 |
| cp       | Chest pain type                      |
| trestbps | Resting blood pressure               |
| chol     | Serum cholesterol level              |
| fbs      | Fasting blood sugar                  |
| restecg  | Resting electrocardiographic results |
| thalach  | Maximum heart rate achieved          |
| exang    | Exercise induced angina              |
| oldpeak  | ST depression induced by exercise    |

### Example Input

```text
Age: 52
Sex: Male
Chest Pain Type: 2
Cholesterol: 230
Max Heart Rate: 150
```

---

# 📤 Output

The model performs **binary classification**.

| Output | Meaning                |
| ------ | ---------------------- |
| 0      | No Heart Disease       |
| 1      | Heart Disease Detected |

### Example Output

```text
Prediction: Heart Disease
```

---

# 🛠 Technologies Used

The following technologies are used in this project:

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# 🤖 Machine Learning Models Used

The following classification algorithms are used:

* **Logistic Regression**
* **Decision Tree Classifier**
* **Random Forest Classifier**

These models learn the relationship between patient health attributes and heart disease risk.

---

# 📊 Model Evaluation

Model performance is evaluated using the following metrics:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* Classification Report

These metrics help determine how accurately the model detects heart disease cases.

---

# 🔍 Key Insights

Important insights from the project:

* Age and cholesterol levels significantly influence heart disease risk.
* High blood pressure and abnormal heart rate are strong indicators.
* Machine learning models can detect useful patterns in medical data.
* Early prediction can support better healthcare decision-making.

---

# 🚀 Future Improvements

Possible improvements for the project:

* Implement **Deep Learning models (Neural Networks)**
* Use a **larger healthcare dataset**
* Improve the **UI of the web application**
* Deploy the model on **cloud platforms**
* Develop a **real-time heart disease risk prediction system**

---

# 👩‍💻 Author

Developed by **Leetika**

Machine Learning Project | Healthcare AI
