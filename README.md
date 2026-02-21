<img width="2815" height="1536" alt="IMG_20260222_014420" src="https://github.com/user-attachments/assets/347a3251-b3f9-4b37-9143-b49e627e26bf" />
## PushForm-AI-CNN-LSTM-Based-Push-Up-Form-Classification
CNN-LSTM based push-up form classification using transfer learning and temporal sequence modeling.
## 🏋️ PushForm-AI  
### CNN-LSTM Based Push-Up Form Classification

PushForm-AI is a deep learning project that analyzes push-up exercise videos and classifies them as **Correct** or **Wrong** form using a hybrid **Pretrained CNN + LSTM** architecture.

This project demonstrates practical implementation of **Transfer Learning**, **Fine-Tuning**, and **Temporal Sequence Modeling** for real-world human activity analysis.

---

## 🚀 Project Overview

Accurate exercise form detection is essential for injury prevention and performance improvement.

In this project:

- A **pretrained ResNet50 (ImageNet weights)** is used as a frame-level feature extractor.
- Uniform frame sampling is applied to each video sequence.
- Extracted features are fed into an **LSTM network** to model temporal motion.
- The model classifies push-up sequences into:
  - ✅ Correct Form
  - ❌ Wrong Form

---

## 🧠 Model Architecture

1. Video Input  
2. Frame Sampling (T = 16 frames)  
3. Pretrained ResNet50 (Feature Extraction)  
4. LSTM (Temporal Modeling)  
5. Fully Connected Classification Head  

Two-phase training strategy:
- Phase 1: Freeze CNN backbone
- Phase 2: Fine-tune final CNN layers with low learning rate

---

## 📊 Results

- Accuracy: ~81%
- Strong precision on wrong form detection
- Demonstrates effective temporal modeling

Confusion Matrix Example:

[[8 0]
[3 5]]


---

## 🛠 Tech Stack

- Python
- PyTorch
- TorchVision
- OpenCV
- Scikit-learn
- Google Colab

---

## 📂 Dataset

Kaggle Dataset:
Push-Up Video Sequences (Correct vs Wrong)

Split Strategy:
- 70% Training
- 15% Validation
- 15% Testing

---

## 🔥 Key Concepts Demonstrated

- Transfer Learning
- CNN Feature Extraction
- LSTM Sequence Modeling
- Fine-Tuning Strategy
- Evaluation Metrics
- Confusion Matrix Analysis

---

## 📌 Future Improvements

- Multi-exercise classification
- Pose estimation integration
- Real-time deployment
- Mobile optimization

---

## 👨‍💻 Author

Mahmoud Ayman  
Artificial Intelligence Student  
Deep Learning & Computer Vision Enthusiast
