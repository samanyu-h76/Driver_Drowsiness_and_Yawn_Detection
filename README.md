# 🚗 Driver Drowsiness & Yawn Detection using Deep Learning

This project detects **driver drowsiness and yawning behavior** using a convolutional neural network (CNN) trained on facial image data.  
It helps promote **road safety** by alerting when a driver appears sleepy or yawning.

---

## 📚 Overview

The application uses a deep learning model (MobileNetV2) trained on a dataset with four facial classes:

- **Open** → Eyes open  
- **Closed** → Eyes closed  
- **yawn** → Mouth open / yawning  
- **no_yawn** → Mouth closed / not yawning  

By classifying these states, the app determines whether the driver is **Alert 😎** or **Drowsy 😴**.

---

## 🧠 Model Details

- **Architecture:** MobileNetV2 (Transfer Learning)
- **Framework:** TensorFlow / Keras
- **Image Size:** 224 × 224
- **Classes:** 4 (Open, Closed, yawn, no_yawn)
- **Training Epochs:** 10–15
- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Evaluation Metrics:** Accuracy, Precision, Recall, Confusion Matrix

---

## 🧩 Dataset

The dataset consists of images of eyes and mouths categorized into:

| Folder | Meaning | Category |
|--------|----------|-----------|
| `Open` | Eyes open | Alert |
| `Closed` | Eyes closed | Drowsy |
| `yawn` | Mouth open | Drowsy |
| `no_yawn` | Mouth closed | Alert |

Data is split into **train** and **test** folders for model training and validation.

---

## 🧾 Requirements

Install dependencies before running:
pip install -r requirements.txt

---

Streamlit Cloud Link: https://iada-201-1000319--samanyu-cwcmtqh2kcfbrjsjqs24zz.streamlit.app/
