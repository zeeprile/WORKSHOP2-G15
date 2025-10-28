# 🌱 Intelligent Crop Disease Detection System Using Deep Learning  
**Workshop 2 — Group 15**  
**Universiti Teknikal Malaysia Melaka (UTeM)**  

---

## 🧠 Overview
This project aims to develop an **Intelligent Crop Disease Detection System** using **deep learning**.  
The system enables farmers or agricultural users to **capture or upload leaf images** and instantly detect possible diseases. It provides **disease information and treatment recommendations**, empowering farmers to make data-driven decisions.

The mobile app is built using **Flutter** (for Android/iOS), integrating a **TensorFlow Lite model** trained on the **PlantVillage dataset**.

---

## 🎯 Project Objectives
1. **Develop a CNN-based model** that can classify crop leaf diseases with high accuracy.  
2. **Design a mobile application interface** for users to capture/upload images and view results.  
3. **Integrate and test the trained deep learning model** in a real-time mobile environment.

---

## 🧩 Project Modules

### **Module 1 — User Interface (Flutter App)**
- Design user-friendly mobile interface (Home, Upload, Result, About)
- Implement navigation & image upload/camera capture features
- Ensure responsive layout for both Android and iOS

### **Module 2 — Model Development (Python + TensorFlow)**
- Train CNN model using **PlantVillage dataset**
- Apply **Transfer Learning (MobileNetV2)** for efficient training
- Convert trained model (`.h5`) to **TensorFlow Lite (`.tflite`)**
- Notebook created in Google Colab  
  🔗 [Model Training Notebook (Google Colab)](https://colab.research.google.com/drive/12aE5MlaaCavnbNX5g17LTCFjLZP_E7aU?usp=sharing)

### **Module 3 — Integration & Testing**
- Connect Flutter app with TensorFlow Lite model
- Perform testing using sample images
- Evaluate system performance and prediction accuracy

---

## ⚙️ Tech Stack

| Component | Technology |
|------------|-------------|
| Frontend | Flutter (Dart) |
| Machine Learning | TensorFlow / Keras |
| Deployment Model | TensorFlow Lite |
| Dataset | PlantVillage |
| Database | Firebase / SQLite |
| IDE | Android Studio / VS Code / Google Colab |
| Version Control | GitHub |

---

## 👥 Team (Group 15)

| Name | Matric No. | Role |
|------|-------------|------|
| **Elango A/L Vellasamy** | B032310233 | Team Leader, Flutter UI Developer |
| **Muhammad Faiz Bin Mohd Salleh** | B032420081 | CNN Model Development |
| **Yew Zhi Yu** | B032310595 | Dataset Management & Testing |
| **Abdulaziz Ali Salem Awadh** | B032310888 | Documentation & Integration Support |

**Supervisor:** Ts. Dr. Mazlan Mohamed  

---
                                              
