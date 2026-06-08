# 🍽️ AI Food Calorie Recognition

## 📌 Project Overview

AI Food Recognition & Nutrition Analyzer is a Deep Learning-based image classification system that identifies food items from uploaded images and provides nutritional information such as calories, protein, and sugar content.

The project uses MobileNetV2 Transfer Learning for accurate food classification and Streamlit for an interactive web interface.

---

## 🚀 Features

✅ Food Image Recognition

✅ Deep Learning-based Classification

✅ Nutrition Information Display

✅ Confidence Score Prediction

✅ Interactive Streamlit Web Application

✅ Transfer Learning using MobileNetV2

---

## 🛠️ Tech Stack

- Python
- TensorFlow
- MobileNetV2
- NumPy
- Scikit-Learn
- Joblib
- Streamlit
- Pillow

---

## 📂 Project Structure

food-recognition-nutrition-analyzer/

├── app.py

├── predict.py

├── nutrition_data.py

├── train_model.py

├── split_dataset.py

├── requirements.txt

├── dataset/

│ ├── train/

│ └── val/

├── models/

│ ├── final_food_model.h5

│ └── label_map.pkl

└── README.md


## 🍕 Supported Food Categories

- Chowmein
- Curd Rice
- Dosa
- Donut
- Fritter
- Gulab Jamun
- Ice Cream
- Idli
- Maggi
- Pastry
- Pizza
- Sandwich
- Veg Burger
- White Sauce Pasta
- Wrap

## 🧠 Model Architecture

- MobileNetV2 (Pre-trained on ImageNet)
- Global Average Pooling Layer
- Dense Layer (128 Neurons)
- Softmax Output Layer

Transfer Learning is used to improve accuracy while reducing training time.


## 🔄 Workflow

1. Collect Food Image Dataset
2. Split Dataset into Training and Validation Sets
3. Apply Data Augmentation
4. Train MobileNetV2 Model
5. Save Trained Model
6. Upload Food Image
7. Predict Food Category
8. Display Nutrition Information


## 📊 Nutrition Information

The application provides:

- Calories (kcal)
- Protein (g)
- Sugar (g)

for detected food items.


## ▶️ Installation

### Clone Repository

```bash
git clone https://github.com/Parul-kumari089/food-calorie-recognition.git
cd food-calorie-recognition
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

## 📷 Application Output

Upload a food image and get:

- Predicted Food Name
- Confidence Score
- Calories
- Protein Content
- Sugar Content


## 🎯 Future Improvements

- Add More Food Categories
- Calorie Estimation Based on Portion Size
- Real-Time Camera Detection
- Cloud Deployment
- Meal Recommendation System


## 👩‍💻 Author

Parul Kumari

B.Tech Computer Science Engineering

Rajasthan College of Engineering for Women (RCEW)
