# Human Mood Recognition using Deep Learning

This project focuses on recognizing human moods from facial images using convolutional neural networks (CNNs). It's developed as a summer research project and demonstrates the application of transfer learning, data augmentation, and various CNN architectures.

---

## 📌 Objectives

- Build a robust system to recognize moods (happy, sad, angry, etc.) from images
- Compare performance of different pre-trained CNN models

---

## Dataset

- Link :- https://www.kaggle.com/datasets/muhammadhananasghar/human-emotions-datasethes?select=EmotionsDataset_Splitted
  

## 🧠 Models Used

- ✅ VGG-16
- ✅ VGG-19
- ✅ ResNet-50
- ✅ EfficientNetB4


---

## ⚙️ Tools & Technologies

- Python 3  
- TensorFlow & Keras  
- Google Colab (GPU: T4)  
- ImageDataGenerator for data augmentation  
- Transfer Learning & Fine-tuning  

---

## 🧪 Data Preprocessing

- Resized images to target size (e.g., 224x224 or 380x380)
- Normalized and augmented images (rotation, zoom, flip, shift)
- Split dataset into training and validation sets

---

## 📊 Model Performance

| Model          | Validation Accuracy | Loss |
|----------------|---------------------|------|
| VGG-16         | 74.62%              | 0.58 |
| VGG-19         | 74.49%              | 0.59 |
| ResNet-50      | 73.60%              | 0.59 |
| EfficientNetB4 | 65.36%              | 0.73 |


---

## 📈 Visualizations

- Training vs Validation Accuracy Curves
- Loss Curves
- Confusion Matrix
- Grad-CAM Heatmaps for model interpretability

---


## 📁 Repository Contents

- human mood recognition file
- Dataset
- images of different visulizations


