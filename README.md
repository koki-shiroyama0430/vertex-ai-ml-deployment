# Vertex AI ML Deployment: End-to-End MNIST Classification

This repository demonstrates a complete Machine Learning workflow—from mathematical foundations and model architecture design to training and cloud-ready deployment. The project focuses on classifying handwritten digits using the MNIST dataset and is optimized for deployment on **Google Cloud Vertex AI**.

## 🚀 Project Highlights
* **Full Pipeline:** Implements the entire ML lifecycle: Data preprocessing → Model Design → Training → Evaluation → Model Export.
* **Production Ready:** The model is exported in the native `.keras` format, ready to be registered in the **Vertex AI Model Registry**.
* **Scalable Architecture:** Designed to be served as a REST API endpoint for real-world application integration.

---

## 🏗 Repository Structure
````text
vertex-ai-ml-deployment/
├── notebooks/
│   ├── 01_theory_and_math.ipynb        # Mathematical implementation from scratch
│   ├── 02_model_architecture.ipynb     # Deep Learning network design & layers
│   └── 03_training_and_evaluation.ipynb # Training loop and performance metrics
├── models/
│   └── mnist_model.keras               # Trained and serialized model file
└── README.md                           # Project documentation
````

---

## 📈 Model Performance
The model achieves high accuracy by utilizing a deep neural network with optimized hyper-parameters.

* **Test Accuracy**: 97% - 98%

* **Loss Function**: Sparse Categorical Crossentropy

* **Optimizer**: Adam

* **Evaluation**: High generalization capability verified with unseen test data.

---

# 🛠 Tech Stack
* **Language**: Python 3

* **Framework**: TensorFlow / Keras

* **Cloud Platform**: Google Cloud Platform (GCP)

* **Services**: Vertex AI (Model Registry & Endpoints), Cloud Storage (GCS)

* **Dataset**: MNIST (Handwritten Digits)

---

# 🌐 Cloud Deployment (Roadmap)
This model is specifically prepared for the following GCP workflow:

1. Upload the .keras model to a Google Cloud Storage (GCS) bucket.

2. Import the model into Vertex AI Model Registry.

3. Deploy to a Vertex AI Endpoint to serve real-time predictions via API.

---


📝 Author
[koki-shiroyama0430]

GitHub: [https://github.com/koki-shiroyama0430]

LinkedIn: [www.linkedin.com/in/koki-shiroyama-067a87245]
