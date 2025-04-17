# 🧠 Mouse Sleep Stage Classification

This project is part of the **2024-1 Introduction to Artificial Intelligence** course.  
We built an AI model to classify **mouse sleep stages** (REM, Wake, NREM) using spectrogram data extracted from brain signals.

## 🧪 Models Implemented

We tested and compared the following models:

- ✅ **Random Forest** *(Best Accuracy: ~92.2%)*
- 🧠 **Support Vector Machine (SVM)**
- 🔍 **K-Nearest Neighbors (KNN)**
- 🌐 **Convolutional Neural Network (CNN)**
- 🔢 **Multilayer Perceptron (MLP)**
- 🔁 **Sequential Dense Model**
- 🌲 **Decision Tree**

## 📊 Dataset

- **Training data**: 22,992 samples
- **Testing data**: 5,748 samples
- **Input shape**: (13 time points, 176 frequency points)
- **Labels**: 0 - REM, 1 - Wake, 2 - NREM
## 📌 Conclusion

Random Forest achieved the highest accuracy (~92.2%).  
However, model selection should also consider complexity, training time, and hardware availability.
