# 🌱 Crop Leaf Disease Detection Using Deep Learning  

![Python](https://img.shields.io/badge/Python-3.8-blue?logo=python)  
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-CNN-orange)  
![Framework](https://img.shields.io/badge/Framework-PyTorch-red?logo=pytorch)  
![Flask](https://img.shields.io/badge/Backend-Flask-green?logo=flask)  

A **Crop Leaf Disease Detection System** built using **Deep Learning** to help farmers identify crop diseases from **leaf images** quickly and accurately.  
This project uses a **Convolutional Neural Network (CNN)** implemented in **PyTorch** to classify images of crop leaves into **39 disease categories**.  
The trained model is deployed as a **Flask web application** for real-time predictions.  

---

## 🛑 Problem Statement  

Farmers face multiple challenges in managing crop health:  

- 🌾 **Early Detection Difficulty:** Many crop diseases are hard to detect at an early stage from the leaves, leading to reduced yield.  
- ⏱️ **Time-Consuming Inspections:** Manual inspection of leaves over large fields is slow and inefficient.  
- 💰 **High Losses:** Delayed or wrong treatment of diseased crops can cause significant financial losses.  
- 📚 **Lack of Expert Knowledge:** Not all farmers have access to agricultural experts to identify diseases accurately.  

---

## 🌟 How This Project Helps Farmers  

This system solves the above problems by providing:  

- 🖼️ **Leaf-based Detection:** Farmers can take a photo of a crop leaf and get instant disease classification.  
- 📊 **Accurate Results:** CNN-based model trained on PlantVillage dataset ensures high prediction accuracy.  
- 💡 **Early Intervention:** Enables timely treatment to prevent crop damage and yield loss.  
- 🌐 **Accessible Anywhere:** Web app powered by Flask can be accessed from any device.  
- 📓 **Learning Tool:** Farmers can learn about diseases and recommended treatments by analyzing leaf images.  

---

## 🚀 Features  

- 🌿 **Classifies 39 crop diseases** using **leaf images**  
- 🧠 **CNN-based Deep Learning Model** built with **PyTorch**  
- 📊 Trained on **PlantVillage Dataset** for high accuracy  
- 🌐 **Flask-powered Web App** for real-time inference  
- 🖼️ **Supports custom leaf image uploads**  
- 📓 **Jupyter Notebook** provided for experimentation  

---

## 📂 Project Structure  

```bash
Crop-Leaf-Disease-Detection/
│
├── Flask Deployed App/       # Flask web app files
│   ├── static/               # CSS, JS, images
│   ├── templates/            # HTML templates
│   ├── app.py                # Flask app entry point
│
├── Model/                    # Jupyter notebooks & model training code
│   ├── Crop_Disease_Model.ipynb
│   └── utils.py
│
├── requirements.txt
└── README.md
```

## 📦 Dataset

We use the PlantVillage Dataset, which contains labeled crop leaf images for training and validation.
📚 Dataset Link

## ⚡ Getting Started

Follow these steps to set up and run the project on your machine:

## 🔑 Prerequisites

Python 3.8+ installed

pip package manager

(Optional) Jupyter Notebook for model exploration

1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Crop-Leaf-Disease-Detection.git
cd Crop-Leaf-Disease-Detection
```

2️⃣ Create and Activate Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

3️⃣ Install Dependencies
```bash
# Install default CPU version
pip install -r requirements.txt

# (Optional) For GPU version:
# 1. Uncomment the GPU lines in requirements.txt
# 2. Then run:
# pip install -r requirements.txt
```

4️⃣ Download Pre-trained Model

Download the trained model file from the link below and place it inside the Flask Deployed App folder.

🔗 Download Model (.pt file)

5️⃣ Run Flask App
```bash
cd "Flask Deployed App"
python3 app.py
```
Now visit 👉 http://127.0.0.1:5000/
 in your browser to access the web app.
 🎯 Future Enhancements

🔄 Improve accuracy with transfer learning (ResNet, EfficientNet)

🖼️ Support real-time camera input for leaf images

📱 Build a mobile-friendly interface

☁️ Deploy on Heroku/AWS/Render for public access

🔔 Add disease treatment suggestions based on leaf image predictions
