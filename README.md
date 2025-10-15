# American Sign Language (ASL) Detection

## 🎯 Project Objective
Build a machine learning system to **detect hand signs from images** and classify them into ASL letters or symbols.  
This is a **multiclass image classification problem** with 29 classes (A–Z + SPACE, DELETE, NOTHING).

---

## 📦 Dataset
- **Source:** [ASL Alphabet Dataset on Kaggle](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)
- **Classes:** 29 (A–Z, SPACE, DELETE, NOTHING)
- **Format:** Images organized in separate folders per class, resized to 224x224 (or 160x160)

---

## 🛠 Tech Stack
- **Language:** Python  
- **Libraries:** TensorFlow, Keras, OpenCV, NumPy, Matplotlib  
- **Techniques:** CNN, Data Augmentation, Transfer Learning (MobileNetV2)

---

## 📋 Implementation Steps
1. **Load dataset** and explore sample images
2. **Preprocessing & Data Augmentation** using `ImageDataGenerator`
3. **Build CNN model** with MobileNetV2 (pre-trained)  
4. **Train model** with training & validation generators
5. **Evaluate performance** (accuracy & loss plots)
6. **Test predictions** on new ASL images
7. **Save the trained model** as `asl_model.h5`
8. **Deploy (optional)** for real-time ASL detection

---

## 📈 Results
- Model achieved **~95% validation accuracy** (can vary based on epochs and augmentation)
- Successfully detects 29 ASL signs (A–Z + SPACE, DELETE, NOTHING)

---

## 📂 Folder Structure
