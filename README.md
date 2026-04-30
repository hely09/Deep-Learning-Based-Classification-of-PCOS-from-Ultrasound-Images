# 🩺 PCOS Detection using Ultrasound Images (Deep Learning Project)

## 📌 Overview

This project focuses on detecting **Polycystic Ovary Syndrome (PCOS)** using ultrasound images with the help of **Deep Learning techniques**. The model is trained to classify images into two categories:

* **PCOS**
* **Normal**

The goal is to assist in early diagnosis using automated image classification.

---

## 📂 Project Structure

```
PCOS_Ultrasound_Images_Dataset/
│
├── Dataset/
│   ├── Train/
│   │   ├── PCOS/
│   │   └── NORMAL/
│   │
│   ├── Test/
│       ├── PCOS/
│       └── NORMAL/
│
├── PCOS_Ultrasound_Images_Code_File.ipynb
└── README.md
```

---

## 📊 Dataset Details

* Dataset contains ultrasound images categorized into:

  * **PCOS**
  * **NORMAL**
* Split into:

  * **Training set**
  * **Testing set**
* Folder-based classification (compatible with Keras/PyTorch loaders)

---

## 🚀 Technologies Used

* Python 🐍
* Jupyter Notebook 📓
* TensorFlow / Keras (or PyTorch, depending on your code)
* OpenCV
* NumPy
* Matplotlib

---

## ⚙️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/pcos-detection.git
cd pcos-detection
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

*(If requirements.txt is not available, install manually: TensorFlow, numpy, matplotlib, opencv-python)*

---

### 3️⃣ Run the Notebook

Open the notebook:

```bash
jupyter notebook
```

Then run:

```
PCOS_Ultrasound_Images_Code_File.ipynb
```

---

## 🧠 Model Workflow

1. Data Loading
2. Image Preprocessing (Resize, Normalize)
3. Data Augmentation (if applied)
4. Model Building (CNN / Transfer Learning)
5. Training & Validation
6. Testing
7. Performance Evaluation

---

## 📈 Expected Output

* Classification of ultrasound images:

  * PCOS
  * Normal
* Metrics:

  * Accuracy
  * Loss
  * Confusion Matrix (optional)

---

## 🔍 Future Improvements

* Use larger dataset
* Apply Transfer Learning (ResNet, VGG, EfficientNet)
* Deploy as Web App (Streamlit/Flask)
* Add Explainable AI (Grad-CAM)

---

## ⚠️ Disclaimer

This project is for **educational and research purposes only**. It should not be used for medical diagnosis without professional validation.

---

## 👨‍💻 Author

**Hely Vachhani**
GitHub: https://github.com/hely09

