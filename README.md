# Face Mask Detection using CNN 😷🚀

This project is a Deep Learning solution to detect whether a person is wearing a face mask or not in real-time. It uses a Convolutional Neural Network (CNN) built with TensorFlow/Keras.
- <img width="936" height="328" alt="image" src="https://github.com/user-attachments/assets/a0a42cb7-cf7f-4a55-bb19-6bd707320f42" />
## 📊 Project Performance
- **Training Accuracy:** 99.73%
- **Validation Accuracy:** 98.29%
- **Test Accuracy:** 99.09%

## 🛠️ Dataset & Methodology
The dataset was sourced from Kaggle. I implemented a custom data engineering pipeline:
1. **Data Cleaning:** Removed pre-existing test/validation splits to ensure a fresh distribution.
2. **Data Splitting:** Re-partitioned the data into **80% Train, 10% Validation, and 10% Test**.
3. **Preprocessing:** Standardized all images to **256x256** and normalized pixels to [0, 1].

## 🏗️ Model Architecture
- **Input Layer:** 256x256 RGB images.
- **Feature Extraction:** Multiple Conv2D and MaxPooling2D layers.
- **Regularization:** Dropout layer (0.5) to prevent overfitting.
- **Output Layer:** Sigmoid activation (0 = Mask, 1 = No Mask).

## 🚀 Features
- **Real-time Detection:** Integrated with OpenCV and YOLO-style tracking.
- **High Precision:** Minimal loss (0.0082) ensuring reliable predictions.
- **Visual Feedback:** Bounding boxes with confidence scores and unique IDs.

