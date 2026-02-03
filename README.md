Vertex AI ML Deployment: End-to-End MNIST Classification
This repository demonstrates a complete Machine Learning workflow—from mathematical foundations and model architecture design to training and cloud-ready deployment. The project focuses on classifying handwritten digits using the MNIST dataset and is optimized for deployment on Google Cloud Vertex AI.

🚀 Project Highlights
Full Pipeline: Implements the entire ML lifecycle: Data preprocessing → Model Design → Training → Evaluation → Model Export.

Production Ready: The model is exported in the native .keras format, ready to be registered in the Vertex AI Model Registry.

Scalable Architecture: Designed to be served as a REST API endpoint for real-world application integration.

🏗 Repository Structure
Plaintext
vertex-ai-ml-deployment/
├── notebooks/
│   ├── 01_theory_and_math.ipynb        # Mathematical implementation from scratch
│   ├── 02_model_architecture.ipynb     # Deep Learning network design & layers
│   └── 03_training_and_evaluation.ipynb # Training loop and performance metrics
├── models/
│   └── mnist_model.keras               # Trained and serialized model file
└── README.md                           # Project documentation
🛠 Tech Stack
Language: Python 3.x

Framework: TensorFlow / Keras

Cloud Platform: Google Cloud Platform (GCP)

Services: Vertex AI (Model Registry & Endpoints), Cloud Storage (GCS)

Dataset: MNIST (Handwritten Digits)

📈 Model Performance
The model achieves high accuracy by utilizing a deep neural network with optimized hyper-parameters.

Test Accuracy: 97%~98% (Expected)

Loss Function: Sparse Categorical Crossentropy

Optimizer: Adam

🌐 Cloud Deployment (Roadmap)
This model is specifically prepared for the following GCP workflow:

Upload the .keras model to a Google Cloud Storage bucket.

Import the model into Vertex AI Model Registry.

Deploy to a Vertex AI Endpoint to serve real-time predictions via API.

📝 Author
[Your Name]

GitHub: [Your GitHub Profile Link]

LinkedIn: [Your LinkedIn Profile Link]
