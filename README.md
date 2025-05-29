# 🚨 AI-Based Accident Detection & Emergency Response System

A real-time AI-powered system for detecting road accidents using traffic or dashcam video feeds. Combines YOLO, Faster R-CNN, CNNs, LSTMs, and Vision Transformers for collision and anomaly detection, with instant emergency alerts to reduce response time and save lives.

---

## 📌 Overview

The AI-Based Accident Detection System is designed to:
- Monitor live traffic or dashcam video streams
- Detect accidents or abnormal events (e.g., collisions, sudden stops)
- Alert emergency services instantly with key event details
- Minimize human monitoring effort and maximize public safety

---

## 🎯 Goals

- **Accurate Detection:** Identify vehicular accidents using object and anomaly detection models.
- **Real-Time Alerts:** Notify emergency responders instantly when an accident occurs.
- **Robustness:** Handle various weather, lighting, and traffic scenarios.
- **Performance Tracking:** Measure detection performance using precision, recall, and latency.

---

## 📦 Deliverables

- 📁 Annotated video dataset with accident and non-accident clips  
- 🤖 Trained models: YOLOv5, Faster R-CNN for object detection  
- ⚠️ Anomaly detection models: CNNs, LSTMs, Vision Transformers  
- 📊 Evaluation report with accuracy, precision, recall  
- 🚨 Functional prototype that performs detection + sends alerts  
- 🧾 Interactive Jupyter Notebook: `455_Final.ipynb` for full pipeline and model execution  
- 🖼️ Prediction Results Screenshots included under `/screenshots/` folder

---

## 📊 Dataset

This project uses the **Accident Detection Dataset** from Kaggle:

- **Author**: Rahul Selvakumar  
- **Link**: [Kaggle Notebook](https://www.kaggle.com/code/rahulselvakumar/accident-detection/notebook)

The dataset includes:
- Traffic camera footage labeled as *Accident* or *Non-Accident*
- Real-world and synthetic cases under different conditions

Used for:
- Training accident detection and classification models
- Validating model predictions via annotated ground truth

---

## 🧠 Tech Stack

| Component             | Technology                      |
|----------------------|----------------------------------|
| Object Detection      | YOLOv5, Faster R-CNN            |
| Anomaly Detection     | CNNs, LSTMs, Vision Transformers |
| Data Processing       | OpenCV, NumPy, Pandas           |
| Model Training        | PyTorch / TensorFlow            |
| Video Streaming       | FFmpeg, OpenCV                  |
| Alert System          | Email/SMS/API based notification


---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/AI-Based_Accident-Detection_Emergency_Response_System.git
cd AI-Based_Accident-Detection_Emergency_Response_System

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
````

---

## 🚀 How to Run

```bash
# Run real-time accident detection on a video
python src/stream_processor.py --video path/to/video.mp4

# To evaluate model performance
python src/evaluation.py

# Or open and run the full workflow in Jupyter
jupyter notebook 455_Final.ipynb
```

---

## 🧪 Model Performance

| Model              | Accuracy | Precision | Recall |
| ------------------ | -------- | --------- | ------ |
| YOLOv5             | 94.2%    | 92.8%     | 93.5%  |
| LSTM + CNN         | 90.7%    | 89.1%     | 91.3%  |
| Vision Transformer | 91.5%    | 90.2%     | 91.7%  |


---

## 📍 Future Improvements

* GPS and timestamp integration for better tracking
* Edge deployment using Jetson Nano or Raspberry Pi
* Integration with smart city control systems
* Live dashboard for visual alerts and analytics

---

## 👨‍💻 Author

**Lalith Aditya Chunduri**
[GitHub](https://github.com/lalithaditya) • [LinkedIn](https://linkedin.com/in/lalithaditya)

---
