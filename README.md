# Lung Cancer Detection using Deep Learning 🫁

This project is a web-based application that detects lung cancer from medical images using a deep learning model.  
The model classifies images into **Normal** or **Abnormal** and displays the prediction with a confidence score through a Flask web interface.

---

## 📌 Features
- Upload lung image through a web UI
- Deep Learning model for image classification
- Binary prediction: **Normal / Abnormal**
- Confidence score for each prediction
- Simple and user-friendly interface

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Flask
- OpenCV
- NumPy
- HTML, CSS (Bulma)

---

## 📂 Project Structure

LUN-CANCER/
│
├── app.py
├── model_vgg.json
├── model_vgg.weights.h5
├── templates/
│ ├── home.html
│ └── classify.html
├── static/
│ ├── images/
│ └── script.js
├── uploads/
├── README.md
└── requirements.txt


---

## ▶️ How to Run the Project

### Step 1: Install dependencies

pip install -r requirements.txt

Step 2: Run the Flask application
python app.py

Step 3: Open in browser
http://127.0.0.1:5000

📊 Output

Normal → No lung cancer detected

Abnormal → Possible lung cancer detected

Confidence score is shown for each prediction
