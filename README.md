# tomato-leaf-disease-detection
AI-powered tomato leaf disease detection system using EfficientNetB3 and Streamlit, deployed on Hugging Face Spaces.


# 🍅 Tomato Leaf Disease Detection

AI-powered tomato leaf disease detection system built with EfficientNetB3 and deployed on Hugging Face Spaces.

## 🚀 Live Demo

👉 https://huggingface.co/spaces/Reyal/tomat

---

## 📌 Project Overview

This project detects diseases in tomato plant leaves using a deep learning computer vision model.

Users can upload an image of a tomato leaf through a simple web interface, and the model predicts the disease category in real time.

The system is designed for:

- Smart agriculture
- Early disease detection
- AI-assisted farming solutions
- Plant health monitoring

---

## 🧠 Model

Vision model used:

- EfficientNetB3

The model was trained for tomato leaf disease classification and optimized for image-based inference.

---

## ⚙️ Tech Stack

- Python
- PyTorch
- Streamlit
- OpenCV
- Pillow
- Docker
- Hugging Face Spaces

---

## ☁️ Cloud Architecture

```text
User Upload
      ↓
Streamlit UI
      ↓
EfficientNetB3 Inference
      ↓
Disease Prediction
      ↓
Result Display
```

The application is deployed in the cloud using Docker-based containerization on Hugging Face Spaces.

---

## 📂 Project Structure

```text
├── app.py
├── model.pth
├── requirements.txt
├── Dockerfile
├── utils/
└── README.md
```

---

## 🐳 Dockerized Deployment

The application is containerized using Docker for reproducible deployment environments.

Example workflow:

1. Install dependencies
2. Load trained model
3. Launch Streamlit server
4. Run inference on uploaded images

---

## ▶️ Run Locally

Clone the repository:

```bash
git clone <your-repo-link>
cd <repo-name>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## 🌱 Use Cases

- Precision agriculture
- Crop monitoring
- Smart farming systems
- AI-based disease diagnostics
- Educational AI projects

---

## 📸 Demo

Live application:

👉 https://huggingface.co/spaces/Reyal/tomat

---

## 📜 License

This project is open-source and available for educational and research purposes.
