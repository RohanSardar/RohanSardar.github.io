---
title: "Handwritten Bengali Vowel Recognition Web App"
excerpt: " It detects 11 Bengali vowels taking handwritten figures through live sketchpad as input and predicts accordingly."
collection: portfolio
---

🔗 **Deployed Link:** [Handwritten Bengali Vowel Recognition Web App](https://huggingface.co/spaces/RohanSardar/Bangla)

## Tech Stack  
- Python  
- TensorFlow  
- Gradio  
- NumPy  

## Features

### Input Method
- Interactive sketchpad captures handwritten input in real-time.

### Model
- CNN trained to classify 11 Bengali vowel characters.
- Trained with TensorFlow on image dataset of handwritten characters.

### Interface
- Live sketchpad input with prediction shown instantly.
- Clean UI built using Gradio.

## Workflow

1. **Data Collection**  
   Dataset of handwritten Bengali vowels prepared and augmented.

2. **Model Training**  
   CNN trained with categorical cross-entropy and accuracy metrics.

3. **Web App Deployment**  
   Gradio app created for real-time predictions from user-drawn input.

4. **User Interaction**  
   Users draw a vowel, and the app instantly returns the predicted character.
