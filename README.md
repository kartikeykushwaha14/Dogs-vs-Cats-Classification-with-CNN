# 🐱🐶 Cat vs Dog Classifier (TensorFlow CNN)

A **Convolutional Neural Network (CNN)** built using **TensorFlow/Keras** to classify images of **cats** and **dogs**.  
This project demonstrates the complete pipeline from **dataset preparation → model building → training → evaluation → prediction**.  

---

## 📌 Features
- ✅ GPU-accelerated training with TensorFlow  
- ✅ Dataset download & preprocessing with **ImageDataGenerator**  
- ✅ Custom CNN model built from scratch  
- ✅ Training + validation accuracy and loss visualization  
- ✅ Model saving and loading for future inference  
- ✅ Predict multiple images at once with visualization  

---

## 📂 Dataset
We use the **Cats and Dogs filtered dataset** (subset of Microsoft’s dataset).  
It contains **2000 training images** and **1000 validation images** split into two classes:

- 🐱 Cats → `cats_and_dogs_filtered/train/cats/`  
- 🐶 Dogs → `cats_and_dogs_filtered/train/dogs/`  

📥 Download automatically:
```bash
wget https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip
unzip cats_and_dogs_filtered.zip
