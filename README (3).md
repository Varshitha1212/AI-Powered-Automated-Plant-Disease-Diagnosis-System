
# 🌿 AI-Powered Automated Plant Disease Diagnosis System

This repository contains an AI-powered system that automatically detects plant leaf diseases from images using a Convolutional Neural Network (CNN) and provides actionable care recommendations.

---

## 🚀 Features
- 📷 Image-based Plant Disease Detection using CNN  
- 🌱 Supports diseases in tomato, potato, and pepper plants  
- 🧠 Trained on the PlantVillage dataset  
- 📊 Predicts disease + confidence score  
- 🩺 Provides prevention tips, chemicals, watering advice, and plant-care suggestions  
- 🌍 Streamlit web interface for real-time use  

---

## 🧱 Project Structure
```
AI-Powered-Automated-Plant-Disease-Diagnosis-System/
│
├── plant_leaf_detection_updated.py
├── Plant_Leaf_detection_jpsf.ipynb
├── app.py
├── plant_leaf_diseases_model.h5
└── README.md
```

---

## 📂 Dataset
This project uses the **PlantVillage Dataset** from Kaggle.  
Organize it as:

```
datasett/dataset/
├── train/
├── validation/
└── test/
```

---

## 🧠 Model Training
Run the training script:

```
python plant_leaf_detection_updated.py
```

Outputs:
- Trained model saved as **plant_leaf_diseases_model.h5**

---

## ▶ Running the Streamlit App
To start the web app:

```
streamlit run app.py
```

---

## 📦 Requirements
Create a virtual environment and install dependencies:

```
pip install -r requirements.txt
```

---

## 📜 License
This project is for educational and research purposes.

---

## ✨ Author
Developed by **Varshitha**  
GitHub: https://github.com/Varshitha1212
