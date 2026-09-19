# 🌱 Plant-disease-detection
Plant Disease Detection is a deep learning project that uses a pretrained MobileNetV2 model to classify plant diseases. The PlantVillage dataset is preprocessed and augmented before training. The model predicts 38 disease classes and evaluates performance using training and validation accuracy and loss.

# 🌱 Plant Disease Detection Using Pretrained Model

## 📌 Project Overview

Plant Disease Detection is a deep learning project that identifies plant diseases from leaf images using a pretrained **MobileNetV2** model. The project uses the **PlantVillage dataset**, image preprocessing, data augmentation, and transfer learning to classify plant images into **38 different disease classes**.

## 🎯 Objective

The main objective of this project is to build an image classification model that can automatically detect plant diseases from leaf images and provide the predicted disease class.

## 🛠️ Technologies & Skills

* 🐍 Python
* 🧠 Deep Learning
* 🤖 TensorFlow / Keras
* 📱 MobileNetV2
* 🔄 Transfer Learning
* 🖼️ Image Classification
* 📊 NumPy
* 📈 Matplotlib
* 📂 PlantVillage Dataset
* 🔧 Data Augmentation

## 📂 Dataset

The project uses the **PlantVillage dataset**, downloaded using KaggleHub.

The dataset contains training and validation images organized into different plant disease classes.

## 🔄 Project Workflow

1. 📥 Download the PlantVillage dataset
2. 🧹 Load and preprocess image data
3. 🖼️ Resize images to **160 × 160**
4. 🔄 Apply data augmentation
5. 🧠 Load pretrained **MobileNetV2**
6. ❄️ Freeze the pretrained base model
7. 🔗 Add custom classification layers
8. 🎯 Train the model for disease classification
9. 📊 Evaluate training and validation performance
10. 🔍 Predict disease from a new plant image

## 🧠 Model Architecture

The project uses **MobileNetV2 pretrained on ImageNet** as the base model.

Additional layers include:

* Global Average Pooling
* Dropout (0.3)
* Dense layer with 128 neurons
* Softmax output layer with 38 classes

## 📊 Model Training

The model is compiled using:

* **Optimizer:** Adam
* **Learning Rate:** 0.0001
* **Loss Function:** Sparse Categorical Crossentropy
* **Metric:** Accuracy
* **Epochs:** 100

## 📈 Performance Evaluation

Training and validation performance is visualized using:

* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss

These graphs help analyze the model's learning behavior during training.

## 🔍 Prediction

After training, the model can process a new plant leaf image and predict its corresponding disease class.

Example:

**Input:** Plant leaf image
⬇️
**MobileNetV2 Model**
⬇️
**Predicted Disease Class**

## 🚀 Future Improvements

* Improve model accuracy using fine-tuning
* Add more plant disease datasets
* Deploy the model using Flask or Streamlit
* Create a user-friendly web interface
* Add real-time plant disease detection
* Display prediction confidence scores

## 👨‍💻 Project Type

**Deep Learning | Computer Vision | Image Classification | Transfer Learning**

## 📌 Conclusion

This project demonstrates how transfer learning with MobileNetV2 can be used for plant disease classification. By combining image preprocessing, augmentation, and a pretrained CNN model, the system can classify plant leaf images into multiple disease categories.

![ml](https://github.com/rushikeshwalode06-cod/Plant-disease-detection/blob/main/Plant%20Image.png?raw=true)
