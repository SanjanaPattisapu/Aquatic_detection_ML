# 🐟 Aquatic Animal Detection using YOLOv8

## 📌 Project Overview

This project focuses on detecting aquatic animals (such as fish) in images and videos using the powerful **YOLOv8 object detection model**. The model is trained on a custom dataset obtained from Roboflow and deployed using Google Colab.

---

## 🚀 Features

* Real-time aquatic animal detection 🎯
* Works on both images and videos 📷🎥
* High-speed and accurate predictions using YOLOv8
* Custom-trained model on aquatic dataset
* Easy to run in Google Colab

---

## 🛠️ Technologies Used

* Python 🐍
* YOLOv8 (Ultralytics)
* OpenCV
* NumPy
* Matplotlib
* Roboflow (for dataset)
* Google Colab

---

## 📂 Dataset

* Dataset collected and managed using **Roboflow**
* Contains images of aquatic animals with annotations
* Used for training custom YOLOv8 model

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/aquatic-detection-yolov8.git
cd aquatic-detection-yolov8
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the project

* Open the notebook in Google Colab
* Upload your dataset or connect Roboflow
* Train the model
* Run detection on images/videos

---

## ▶️ Usage

### 🔹 For Image Detection

```python
from ultralytics import YOLO

model = YOLO('best.pt')
results = model('image.jpg', show=True)
```

### 🔹 For Video Detection

```python
results = model(source='video.mp4', save=True)
```

---

## 📊 Output

* Detects aquatic animals with bounding boxes 🟩
* Displays confidence scores
* Saves output images/videos in:

```
runs/detect/predict/
```

---

## 📸 Sample Output

(Add screenshots or video here)

---

## 📁 Project Structure

```
Aquatic-Detection-YOLOv8/
│
├── model_training.ipynb
├── requirements.txt
├── README.md
├── output_sample.mp4
└── images/
```

---

## 💡 Future Improvements

* Improve accuracy with larger dataset
* Add more aquatic species 🐠🐬
* Deploy as a web application
* Real-time webcam detection

---

## 🙌 Acknowledgements

* Ultralytics YOLOv8
* Roboflow
* Google Colab

---

⭐ If you like this project, don’t forget to star the repository!
