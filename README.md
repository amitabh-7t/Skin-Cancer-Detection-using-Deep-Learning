# 🩺 Skin Cancer Detection using Deep Learning

An AI-powered skin lesion classification system leveraging advanced Convolutional Neural Networks to support early screening of skin cancer. Multiple models have been compared to identify the best architecture for accurate diagnosis.

---

## 🎯 Objective

* Classify skin lesions using dermatoscopic images
* Compare performance of multiple transfer-learning architectures
* Support medical experts in early cancer risk detection

---

## 🧠 Deep Learning Models Used

| Model          | Status | Remarks                              |
| -------------- | :----: | ------------------------------------ |
| VGG-16         |    ✔   | Transfer learning baseline           |
| VGG-19         |    ✔   | Improved feature extraction          |
| ResNet50       |    ✔   | Strong performance on medical images |
| DenseNet169    |    ✔   | Captures deep hierarchical features  |
| EfficientNetB0 |    ✔   | Efficient & high accuracy            |
| InceptionV3    |    ✔   | Good at multi-scale feature learning |
| ESRGAN         |    ✔   | Used for resolution enhancement      |

📌 All training notebooks included inside the repository.

---

## 📂 Project Structure

```
📁 Skin-cancer
├─ content/                  # Image content / visual assets (optional)
├─ VGG-16.ipynb
├─ VGG-19.ipynb
├─ ResNet50.ipynb
├─ DenseNet169.ipynb
├─ InceptionV3.ipynb
├─ EfficientNetB0.ipynb
├─ ESRGAN.ipynb
└─ README.md
```

---

## 🧪 Dataset Used

Dermatoscopic skin lesion dataset:

* HAM10000 / ISIC (commonly used in research)

> (You can add dataset link here if public)

---

## 📊 Planned Evaluation Metrics

* Accuracy
* Precision, Recall, F1-Score
* ROC-AUC Score
* Confusion Matrix
* Grad-CAM Visual Explanations 🔥

These results will help determine the best model for deployment.

---

## 🚀 How to Run

```bash
# Install dependencies (suggested)
pip install tensorflow keras numpy pandas matplotlib scikit-learn opencv-python
pip install jupyter
jupyter notebook
```

Execute any notebook like:

```
VGG-16.ipynb
```

---

## 🔮 Future Enhancements

* Deploy as a web app (Streamlit or Gradio UI)
* Add Explainability module (Grad-CAM heatmaps)
* Clinical-level evaluation with dermatologists
* Export to ONNX / TensorRT for real-time inference

---

## ⚠ Disclaimer

This project is for **research & educational** purposes only.
It is **not** a replacement for professional medical diagnosis.

---

## 👨‍💻 Developer

**Amitabh Thakur**
AI/ML Engineer | CSE (AI & ML) @ Dayananda Sagar University
Founder — Humans Care Foundation
Bangalore, India

---

🌟 Contributions, forks & research collaboration are welcome!
