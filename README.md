# 🖼️ Image Classification Project

This repository contains a deep learning project for **image classification** using **TensorFlow/Keras**.  
The notebook (`code.ipynb`) demonstrates dataset preparation, model training, evaluation, and visualization.

---

## 🚀 Features
- Dataset loading & preprocessing with `ImageDataGenerator`
- Convolutional Neural Network (CNN) training
- Model performance tracking across epochs
- Visualisation of training accuracy and loss
- Evaluation on unseen test data

---

## 📊 Dataset
Within my Drive: https://drive.google.com/drive/folders/1BHmOFqlkxvJpgmocPkOqjOVpBYQn7R6I?usp=sharing

Get to known more within the notebook
---

## Result:
1. Image Classification
- Test Accuracy: 84.71%

2. Object Detection
                 Class     Images  Instances      Box(P          R      mAP50  mAP50-95):
   
                   all        307        962      0.845      0.728      0.825      0.519
   
                  boat        240        392      0.829      0.703      0.807      0.477
   
                   car         27         27      0.726      0.689      0.742      0.458
   
                  dock         24         42      0.968      0.709      0.892      0.606
   
                jetski         63         90        0.8      0.711      0.799      0.442
   
                  lift        217        411      0.902      0.827      0.885      0.612
   

Evaluation Metrics:

Mean Precision: 0.845

Mean Recall: 0.728

mAP@0.5: 0.825

mAP@0.5:0.95: 0.519
