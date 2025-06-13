# 🏠 Bangalore Real Estate Price Prediction

This is a machine learning project that predicts housing prices in Bangalore based on area (square feet), number of BHKs, bathrooms, and location. The project includes a complete web interface (HTML/CSS/JS frontend) connected to a Python Flask backend using a trained ML model.

---

## 📁 Project Structure
```
Project1_Real_Estate_Prediction/
│
├── client/                     # Frontend (HTML, CSS, JS)
│   ├── app.html
│   ├── app.css
│   └── app.js
│
├── model/                      # Data exploration and model training
│   ├── bengaluru_house_prices_exp.ipynb
│   ├── bangalore_home_prices_model.pickle
│   └── columns.json
│
├── server/                     # Flask backend and utility functions
│   ├── server.py
│   └── util.py
│
├── bengaluru_house_prices.csv # Raw dataset used for training
└── README.md                   # Project documentation (this file)

```

---

## 💡 Features

- Predict house price based on:
  - Total square footage
  - Number of bedrooms (BHK)
  - Number of bathrooms
  - Location
- Interactive UI with dropdown & radio buttons
- Flask backend with trained ML model
- Preprocessed data and cleaned features
- Responsive frontend design

---

## ⚙️ Technologies Used

- **Python** (Pandas, NumPy, Scikit-learn)
- **Flask** for backend API
- **HTML/CSS/JavaScript** for frontend
- **jQuery** for AJAX calls
- **VSCode** as the development environment

---

## 🚀 How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Real-Estate-Prediction.git
cd Real-Estate-Prediction
```
### 2. Set Up Python Environment
```bash
pip install -r requirements.txt
## If you don't have a requirements.txt, install manually:
pip install flask pandas numpy scikit-learn flask-cors
```
### 3. Run the Flask Server
```bash
cd server
python server.py
```
### 4. Open the Web UI
- Open client/app.html in your browser, or serve it using Flask if desired.
---
## 📊 Dataset
- The dataset is from Kaggle: Bengaluru House Data. It contains various features like area, location, number of bathrooms, and price per square foot.
- The dataset is from [Kaggle: Bengaluru House Data](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)

---

## 🔮 Model

- Trained using Linear Regression

- Features selected after cleaning and outlier removal

- Artifacts saved as .pkl and .json for reuse
---
## Author
- Vaibhav
- Passionate about Machine Learning and building real-world ML apps.

