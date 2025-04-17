# 🧠 Mice Sleep Stage Classification (Team 18)

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

## 📁 Folder Structure

```
.
├── data/                   # EEG .npy files
├── notebooks/              # Model training Jupyter notebooks
├── README.md               # Project documentation
├── requirements.txt        # Python dependencies
```

## ⚙️ Requirements

You can install the dependencies with:

```bash
pip install -r requirements.txt
```

Recommended to use Python 3.8+ and TensorFlow 2.x.

## 👨‍👩‍👧‍👦 Team Members

- 송민영 (22000374)
- 심성환 (22000397)
- 채정원 (22100725)
- 하지민 (22100766)

## 📌 Conclusion

Random Forest achieved the highest accuracy (~92.2%).  
However, model selection should also consider complexity, training time, and hardware availability.

## 📄 License

This project is for educational purposes only.