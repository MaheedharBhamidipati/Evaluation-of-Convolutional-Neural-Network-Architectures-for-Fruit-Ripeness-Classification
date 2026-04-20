# 🍎 Evaluation of Convolutional Neural Network Architectures for Fruit Ripeness Classification

## 📌 Overview
This project presents a **comparative evaluation of deep learning models** for automated fruit ripeness classification using image-based analysis. It replaces traditional manual inspection with a **scalable, accurate, and non-destructive AI-based solution**.

The system uses **Convolutional Neural Networks (CNNs)** to classify fruits based on visual features such as **color, texture, and shape**.

---

## 🚀 Problem Statement
Traditional fruit ripeness evaluation methods:
- Manual inspection 👀  
- Chemical analysis 🧪  

Limitations:
- Time-consuming  
- Error-prone  
- Not scalable  

👉 This project solves these issues using **computer vision + deep learning**.

---

## 🧠 Proposed Solution
We implement and compare:
- **EfficientNetB0**
- **ResNet50**

Both models use **transfer learning** to classify fruit ripeness stages.

---

## 🍌 Dataset
- Source: Kaggle  
- Fruits:
  - Tomato 🍅  
  - Papaya 🥭  
  - Banana 🍌  

- Classes:
  - Unripe  
  - Ripe  
  - Overripe / Rotten  
  - Damaged  

---

## ⚙️ Methodology

### 1️⃣ Data Preprocessing
- Image resizing  
- Normalization  
- Data augmentation:
  - Rotation  
  - Flipping  
  - Zooming  

### 2️⃣ Model Training
- Python (Google Colab)  
- Optimizer: Adam  
- Epochs: 10  
- Transfer Learning  

### 3️⃣ Feature Extraction
- Color  
- Texture  
- Shape  

### 4️⃣ Classification
- Fully Connected Layer  
- Softmax Activation  

---

## 🏗️ Model Architectures

### 🔹 EfficientNetB0
- Compound scaling (depth, width, resolution)  
- Depthwise separable convolutions  
- Squeeze-and-Excitation blocks  
- High accuracy with low computation  

### 🔹 ResNet50
- Residual learning with skip connections  
- Handles deep network training effectively  
- Strong feature extraction capability  

---

## 📊 Performance Evaluation

### Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  

### Results

| Model          | Tomato | Papaya | Banana |
|----------------|--------|--------|--------|
| EfficientNetB0 | **78.67%** | **72.1%** | **74.18%** |
| ResNet50       | 62.8%  | 69.85% | 65.31% |

👉 EfficientNetB0 outperforms ResNet50 in most cases.

---

## 📈 Key Insights
- EfficientNetB0 → Better accuracy & efficiency  
- ResNet50 → Strong performance in specific classes  
- CNNs outperform traditional ML methods (SVM, KNN, Naïve Bayes)  

---

## 🌱 Applications
- Smart agriculture 🌾  
- Automated fruit sorting 🏭  
- Supply chain quality control 📦  
- IoT-based monitoring systems  

---

## 🔮 Future Scope
- IoT integration for real-time monitoring  
- Larger and more diverse datasets  
- Hyperspectral imaging  
- Edge/FPGA deployment  

---

## 🛠️ Tech Stack
- Python  
- TensorFlow / Keras  
- Google Colab  
- OpenCV  

---

## 📎 Conclusion
This project demonstrates that **CNN-based models significantly improve fruit ripeness detection**, making them suitable for scalable and real-time agricultural applications.

---

## 📌 Author
**V N S S S R Maheedhar Bhamidipati**  
M.Tech VLSI Design  
Amrita School of Engineering, Bengaluru
