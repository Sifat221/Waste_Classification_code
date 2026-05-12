# ♻️ Waste Classification System using Machine Learning

## 📌 Project Overview

This project presents an AI-based waste classification system using deep learning models.
It can classify and detect different types of waste such as Plastic, Metal, Glass, and Polythene.

The system also integrates YOLOv3 for real-time object detection, making it suitable for smart waste management applications.

---

## 🚀 Features

* Image-based waste classification
* Multi-model comparison (MobileNetV2, ResNet50, EfficientNet)
* Real-time object detection using YOLOv3
* Web-based interface using Flask
* High accuracy (~89%)

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* Flask
* YOLOv3
* NumPy, PIL

---

## 📂 Dataset

* 3000+ waste images
* Categories:

  * Plastic
  * Metal
  * Glass
  * Polythene

The dataset includes real-world images with different lighting conditions.

---

## 🤖 Models Used

* MobileNetV2
* ResNet50
* EfficientNetB1 (Best Performance)
* YOLOv3 (Object Detection)

---

## 📊 Model Performance

| Model          | Accuracy |
| -------------- | -------- |
| MobileNetV2    | ~88%     |
| ResNet50       | ~88%     |
| EfficientNetB1 | ~89.12%  |

EfficientNetB1 achieved the best performance due to its balanced scaling technique.

---

## 📁 Project Structure

```
Waste_Classification_code/
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── static/
│   ├── style.css
│   ├── script.js
│   ├── image.png
│   └── IMG_3876.JPG
│
├── model/
│   └── waste_model.keras
│
├── app.py
├── waste_classification_project.ipynb
└── README.md
```

---

## ▶️ How to Run

### 1. Clone Repository

```
git clone https://github.com/Sifat221/Waste_Classification_code.git
cd Waste_Classification_code
```

### 2. Create Virtual Environment

```
python -m venv waste_env
waste_env\Scripts\activate
```

### 3. Install Dependencies

```
pip install tensorflow flask pillow numpy opencv-python
```

### 4. Run Application

```
python app.py
```

### 5. Open in Browser

```
http://127.0.0.1:5000
```

---

## 📸 Screenshots

### 🖥️ Web Interface
![UI](./static/ui.png)

### 📊 Prediction Result
![Result](./static/result.png)

---

## 💡 Project Significance

This system reduces manual waste sorting, improves recycling efficiency, and contributes to environmental sustainability using AI-based automation.

---

## 🔮 Future Work

* Add more waste categories
* Improve real-time detection
* Deploy on mobile or edge devices
* Integrate IoT-based smart bins

---

## 👨‍💻 Authors

* Sifat Khan
* Md Arif Billah
*  Department of CSE
* Daffodil International University

---
