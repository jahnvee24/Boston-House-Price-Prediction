# 🏡 Boston House Price Prediction

A Flask-based web application to predict housing prices in Boston using a Machine Learning model.

## 🚀 Demo

![App Screenshot](https://via.placeholder.com/800x400?text=Boston+Price+Prediction+App+UI)  
![House-Price-Prediction-SS1](https://github.com/user-attachments/assets/d83b5f8d-fbda-4ca0-8eaa-f22a3278fc4e)
![House-Price-Prediction-SS2](https://github.com/user-attachments/assets/c652b379-a8ef-439b-aa53-fd8d67eac76e)
![House-Price-Prediction-SS3](https://github.com/user-attachments/assets/28880d31-a2e5-4900-a452-1e1ce97f12a7)



## 📌 Features

- User-friendly web interface to input Boston housing data
- Predicts house prices using a trained Linear Regression model
- Built with Flask, Scikit-learn, NumPy
- Lightweight and beginner-friendly codebase

---

## 🧠 Model Info

- Dataset: Boston Housing Dataset (`sklearn.datasets.load_boston()` or replacement)
- Algorithm: Linear Regression
- Serialized using `pickle` into `model.pkl`

---

## 📁 Project Structure
Boston-House-Price-Prediction/
│
├── static/
│ └── style.css
├── templates/
│ └── index.html
├── app.py
├── model.pkl
├── requirements.txt
├── .gitignore
└── README.md

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/jahnvee24/Boston-House-Price-Prediction.git
cd Boston-House-Price-Prediction
```

### 2. Set Up a Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate  # On Windows
# OR
source venv/bin/activate  # On Linux/macOS
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```
If requirements.txt doesn't exist, create it using:
```bash
pip freeze > requirements.txt
```

### 4. Run the application
```bash
python app.py
```

