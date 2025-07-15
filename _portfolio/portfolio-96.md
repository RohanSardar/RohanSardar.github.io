---
title: "SpeechFlowguard"
excerpt: "Developed a FastAPI web API for real-time toxic language detection in user comments. Implements multi-label classification (toxic, severe_toxic, obscene, threat, insult, identity_hate) using TF-IDF and Logistic Regression. Features a modular, Dockerized architecture for easy deployment."
collection: portfolio
---

🔗 **GitHub Link:** [SpeechFlowguard](https://github.com/RohanSardar/SpeechFlowGuard)

## Tech Stack  
- Python  
- FastAPI  
- Scikit-Learn  
- TF-IDF Vectorizer  
- Logistic Regression  
- Natural Language Processing (NLP)  
- Docker  

## Features

### Real-Time Toxicity Detection
- Analyzes user comments in real-time to detect toxic content.
- Handles **multi-label classification** for categories:
  - `toxic`  
  - `severe_toxic`  
  - `obscene`  
  - `threat`  
  - `insult`  
  - `identity_hate`

### Machine Learning Pipeline
- Uses **TF-IDF** for feature extraction.
- Trained **Logistic Regression** models for each label.
- Lightweight and interpretable models for fast inference.

### Web API Interface
- Built using **FastAPI** for high-performance async handling.
- REST endpoints allow sending a comment and receiving predictions instantly.

### Dockerized Deployment
- Fully containerized using **Docker**.
- Easily deployable as a microservice on cloud or edge environments.

## Workflow

1. **Model Training**
   - Train multi-label classifiers using `scikit-learn` and TF-IDF on annotated datasets.

2. **API Development**
   - Create endpoints in FastAPI for:
     - `/predict`: Accepts user comment and returns predicted labels.

3. **Containerization**
   - Use Docker to package the model and API into a modular image.

4. **Deployment**
   - Deployable on any cloud or local server with Docker support.

## Highlights

- 🚀 Real-time inference with low latency.
- 🧠 Simple, fast, and interpretable ML architecture.
- 🧱 Modular codebase for easy retraining or replacement of components.
- ☁️ Cloud-ready via Docker.
