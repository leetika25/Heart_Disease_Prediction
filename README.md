## 📌 Project Statement

Heart disease is one of the most common and dangerous health problems worldwide.
The goal of this project is to develop a **Machine Learning based Heart Disease Prediction System** that predicts whether a patient is likely to have heart disease based on medical data.
The model learns patterns from historical healthcare datasets and predicts the risk of heart disease for new patient data.

---

## 📥 Input Features

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

## 📤 Output

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

## 🛠 Technologies Used

The following technologies are used in this project:

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🤖 Machine Learning Models Used

The following classification algorithms are used:

* **Logistic Regression**
* **Decision Tree Classifier**
* **Random Forest Classifier**

These models learn the relationship between patient health attributes and heart disease risk.

---

## 📊 Model Evaluation

Model performance is evaluated using the following metrics:

* **Accuracy Score**
* **Confusion Matrix**
* **Precision**
* **Recall**
* **Classification Report**

These metrics help determine how accurately the model detects heart disease cases.

---

## 🔍 Key Insights

Important insights from the project:

* Age and cholesterol levels significantly influence heart disease risk.
* High blood pressure and abnormal heart rate are strong indicators.
* Machine learning models can detect useful patterns in medical data.
* Early prediction can support better healthcare decision-making.

---

## 📂 Project Structure

```text
Heart-Disease-Prediction
│
├── Heart_disease_prediction.ipynb   # Machine Learning notebook
├── heart.xls                        # Dataset
├── requirements.txt                 # Required libraries
└── README.md                        # Project documentation
```

---

## 🚀 Future Improvements

Possible improvements for the project:

* Implement **Deep Learning models (Neural Networks)**
* Use a **larger healthcare dataset**
* Build a **web application using Flask or Streamlit**
* Deploy the model on **cloud platforms**
* Develop a **real-time heart disease risk prediction system**
