# 🐱🐶 Cat vs Dog Classifier (TensorFlow CNN)

A Convolutional Neural Network (CNN) built using **TensorFlow/Keras** to classify images of **cats** and **dogs**.  
This project demonstrates the complete pipeline from **dataset preparation → training → evaluation → prediction**.  

---

## 📌 Features
- ✅ GPU-accelerated training with TensorFlow  
- ✅ Data loading and preprocessing using **ImageDataGenerator**  
- ✅ Custom CNN model built from scratch  
- ✅ Training + validation accuracy and loss visualization  
- ✅ Model saving for future inference  
- ✅ Prediction on multiple images with visualization  

---

## 📂 Dataset
We use the **Cats and Dogs filtered dataset** (subset of Microsoft’s dataset).  
It contains **2000 training images** and **1000 validation images** split into two classes:

- 🐱 Cats  
- 🐶 Dogs  

Download automatically with:
```bash
wget https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip
unzip cats_and_dogs_filtered.zip
