# 🌱 Crop Recommendation System

A Machine Learning-based Crop Recommendation System that predicts the most suitable crop for cultivation using soil nutrients and environmental conditions. The application is built with Flask and provides an easy-to-use web interface for generating crop recommendations.

---

## 📌 Project Overview

Choosing the right crop based on soil and climatic conditions is essential for improving agricultural productivity. This project uses a trained Machine Learning model to recommend the most suitable crop based on user-provided soil and weather parameters.

The application is developed using **Python**, **Flask**, and **Scikit-learn**, with a responsive frontend built using **HTML** and **Bootstrap**.

---

## ✨ Features

- 🌱 Predicts the most suitable crop for cultivation.
- 📊 Uses Machine Learning for crop recommendation.
- 🌡️ Accepts real-time soil and weather parameters.
- 💻 Simple and user-friendly web interface.
- ⚡ Fast prediction using a pre-trained ML model.
- 🎨 Responsive frontend built with Bootstrap.

---

## 🛠️ Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- Joblib
- HTML5
- Bootstrap 5

---

## 📊 Input Parameters

The model takes the following inputs:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature (°C)
- Humidity (%)
- pH Value
- Rainfall (mm)

---

## 🌾 Supported Crops

The system can recommend the following crops:

- Rice
- Maize
- Jute
- Cotton
- Coconut
- Papaya
- Orange
- Apple
- Muskmelon
- Watermelon
- Grapes
- Mango
- Banana
- Pomegranate
- Lentil
- Blackgram
- Mungbean
- Mothbeans
- Pigeonpeas
- Kidneybeans
- Chickpea
- Coffee

---

## 📂 Project Structure

```text
Crop-Recommendation-System/
│
├── app.py
├── model.pkl
├── standscaler.pkl
├── minmaxscaler.pkl
├── Crop_recommendation.csv
├── templates/
│   └── index.html
├── static/
│   └── img.jpg
└── README.md
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/avineetpal185/Crop-Recommendation-System.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd Crop-Recommendation-System
```

### 3️⃣ Install the Required Libraries

```bash
pip install flask numpy pandas scikit-learn joblib
```

### 4️⃣ Run the Flask Application

```bash
python app.py
```

### 5️⃣ Open Your Browser

Visit:

```
http://127.0.0.1:5000
```

---

## 🖥️ How to Use

1. Enter the following values:
   - Nitrogen
   - Phosphorus
   - Potassium
   - Temperature
   - Humidity
   - pH Value
   - Rainfall

2. Click the **Get Recommendation** button.

3. The system will display the recommended crop for cultivation.

---

## 📷 Output

The application predicts and displays the most suitable crop based on the provided soil and environmental parameters.

> **Note:** Screenshots of the application will be added in future updates.

---

## 🎯 Future Improvements

- Improve prediction accuracy using advanced Machine Learning models.
- Add fertilizer recommendation.
- Add crop disease prediction.
- Deploy the application online.
- Improve the UI/UX.
- Add authentication and user history.

---

## 👨‍💻 Author

**Avineet Pal Singh**

- GitHub: https://github.com/avineetpal185

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
