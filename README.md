# 🧠 Brain Stroke Prediction System

## 📌 Overview

The **Brain Stroke Prediction System** is a Machine Learning-based web application designed to predict the risk of stroke in patients based on medical and lifestyle parameters.

This project uses a **Decision Tree algorithm** trained on healthcare data and integrates it with a **Flask web application** to provide real-time predictions through a user-friendly interface.

---

## 🚀 Features

* 🔐 User Login Authentication (Admin-based access)
* 🧠 Real-time Stroke Risk Prediction
* 📊 Probability Score Output
* 🖥️ Interactive Web Interface
* ⚙️ Backend Integration using Flask
* 📁 Structured Project Architecture
* 📈 Model Evaluation (Accuracy & Confusion Matrix)

---

## 🏗️ Project Architecture

```
Brain-Stroke-Prediction/
│
├── app/
│   ├── app.py
│   ├── templates/
│   │   ├── index.html
│   │   └── login.html
│   └── static/
│
├── models/
│   └── dt.sav
│
├── data/
│   └── healthcare-dataset-stroke-data.csv
│
├── notebooks/
│   └── Stroke_Prediction.ipynb
│
├── requirements.txt
└── README.md
```

---

## 🧠 Machine Learning Model

* **Algorithm Used:** Decision Tree Classifier
* **Dataset:** Healthcare Stroke Dataset
* **Input Features:**

  * Age
  * Gender
  * Hypertension
  * Heart Disease
  * BMI
  * Average Glucose Level
  * Smoking Status
  * Work Type
  * Residence Type

---

## ⚙️ Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Flask (Python)
* **Machine Learning:** Scikit-learn
* **Data Processing:** Pandas, NumPy

---

## ▶️ Installation & Setup

### 1️⃣ Clone Repository

```
git clone https://github.com/your-username/brain-stroke-prediction.git
cd brain-stroke-prediction
```

### 2️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Run Application

```
python app/app.py
```

### 4️⃣ Open in Browser

```
http://127.0.0.1:5000
```

---

## 🔐 Login Credentials

```
Username: admin
Password: admin
```

---

## 📊 Model Evaluation

* Accuracy Score
* Confusion Matrix

Access via:

```
http://127.0.0.1:5000/report
```

---

## 📷 Screenshots (Add your images here)

* Login Page
* Prediction Form
* Result Output

---

## 🎯 Future Enhancements

* 📈 Add ROC Curve & Graphs
* 🤖 Compare Multiple ML Algorithms
* 🌐 Deploy on Cloud (Render/Heroku)
* 📄 Generate PDF Reports
* 📱 Mobile Responsive UI

---

## ⚠️ Disclaimer

This project is developed for **educational purposes only** and should not be used as a substitute for professional medical advice.

---

## 👨‍💻 Author

* **Your Name**
* Final Year B.Sc (MPCs) Student
* Passionate about Machine Learning & Web Development

---

## ⭐ Acknowledgements

* Healthcare Stroke Dataset (Kaggle)
* Scikit-learn Documentation
* Flask Framework

---

## 📌 Conclusion

This project demonstrates how Machine Learning can be integrated with web technologies to build real-world healthcare applications that assist in early detection and decision-making.

---

⭐ *If you like this project, don’t forget to star the repository!*
