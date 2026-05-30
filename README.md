<h1 align="center">🦵 OSTEO VISION</h1>

<h3 align="center">
AI-Powered Knee Osteoarthritis Detection using Deep Learning
</h3>

<p align="center">
TensorFlow • ResNet152V2 • Streamlit • Grad-CAM • AWS S3
</p>

---

## 📖 Overview

OSTEO VISION is a deep learning-based medical imaging application that automatically detects and classifies the severity of Knee Osteoarthritis (OA) from X-ray images.

The system uses a fine-tuned **ResNet152V2** model to predict the severity of Osteoarthritis according to the **Kellgren-Lawrence (KL) grading system**. To improve transparency and trust, the application also provides **Grad-CAM visualizations** that highlight the regions of the X-ray influencing the model's prediction.

---

## 🎯 Key Features

✅ Automated Knee Osteoarthritis Classification

✅ Classification into KL Grades 0–4

✅ Explainable AI using Grad-CAM

✅ Prediction Confidence Visualization

✅ Interactive Streamlit Web Interface

✅ AWS S3-based Model Storage

---

## 🏥 KL Grading System

| Grade      | Description       |
| ---------- | ----------------- |
| KL Grade 0 | No Osteoarthritis |
| KL Grade 1 | Doubtful OA       |
| KL Grade 2 | Mild OA           |
| KL Grade 3 | Moderate OA       |
| KL Grade 4 | Severe OA         |

---

## 🧠 Model Architecture

The final model is based on:

* ResNet152V2
* Transfer Learning
* Fine-Tuning
* TensorFlow/Keras

Models evaluated during experimentation:

* Logistic Regression
* Random Forest
* ResNet50
* ResNet152V2

ResNet152V2 achieved the best overall performance and was selected as the final production model.

---

## 🔬 Explainable AI (Grad-CAM)

Medical AI systems require transparency and interpretability.

Grad-CAM (Gradient-weighted Class Activation Mapping) generates heatmaps that highlight the regions of the knee X-ray most responsible for the model's prediction.

This helps:

* Improve trust in AI predictions
* Support clinical decision-making
* Provide visual interpretability

---


## 🛠️ Tech Stack

### Deep Learning

* TensorFlow
* Keras
* ResNet152V2

### Explainable AI

* Grad-CAM

### Application

* Streamlit

### Data Processing

* NumPy
* Matplotlib
* Pillow

### Cloud Storage

* AWS S3

### Version Control

* Git
* GitHub

---

## 📸 Application Screenshots

### Home Page

![Home Page]<img width="1911" height="664" alt="image" src="https://github.com/user-attachments/assets/b55431df-b3f7-4bc7-b4e1-2dbcbc63d532" />


### Prediction Result

![Prediction Result]<img width="1112" height="386" alt="image" src="https://github.com/user-attachments/assets/c1e7760a-d4a8-4264-8030-85e869434af3" />


### Grad-CAM Visualization

![Grad-CAM]<img width="1869" height="773" alt="image" src="https://github.com/user-attachments/assets/2b4c9b0f-6419-43a4-9ee0-bb4e22ab6f73" />


### Confidence Graph

![Confidence Graph]<img width="1887" height="736" alt="image" src="https://github.com/user-attachments/assets/79b42778-3fae-47c7-93c5-2c03671e4926" />


---

## 🚀 Running Locally

### Clone Repository

```bash
git clone https://github.com/mithun-26/Knee-OsteoArthritis-Detection.git

cd Knee-OsteoArthritis-Detection
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app/app.py
```

---


## 🔮 Future Improvements

* Clinical validation with larger datasets
* Mobile-friendly deployment
* Multi-disease musculoskeletal diagnosis
* Integration with hospital systems
* Advanced explainable AI techniques

---

## 👨‍💻 Author

### Mithun K A

Artificial Intelligence & Machine Learning

JSS Academy of Technical Education, Bengaluru

GitHub: https://github.com/mithun-26

---

## ⚠️ Disclaimer

This project is intended for educational and research purposes only and should not be used as a substitute for professional medical diagnosis.
