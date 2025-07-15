---
title: "CyberGuard"
excerpt: " It detects 11 Bengali vowels taking handwritten figures through live sketchpad as input and predicts accordingly."
collection: portfolio
---

🔗 **Deployed Link:** [CyberGuard](https://huggingface.co/spaces/RohanSardar/CyberGuard)

## Tech Stack  
- Python
- Gradio
- PyTorch
- Scikit-Learn
- Transformers
- Accelerate
- NLTK
- NumPy
- Pandas 

## Features

### Data Handling
- Cybercrime complaints are preprocessed using **Pandas**.
- Custom PyTorch Dataset class used for loading data.

### Model Architecture
- Fine-tuned **BERT (BertForSequenceClassification)** model for multi-class text classification.
- **BertTokenizerFast** used for tokenizing inputs efficiently.

### Inference Pipeline
- Hugging Face **`pipeline`** used for quick and clean inference setup.
- Runs seamlessly on CPU or GPU with **Torch** backend.

### Interface
- Deployed via **Gradio** for an interactive user experience.

## Workflow

1. **Data Preparation**  
   Load CSV data with **Pandas**, clean and encode labels.  
   Define custom dataset class using **torch.utils.data.Dataset**.

2. **Model Training**  
   Fine-tune `BertForSequenceClassification` with PyTorch.

3. **Inference**  
   Use Hugging Face **pipeline** for streamlined inference deployment.

4. **Deployment**  
   Gradio app allows users to input a complaint and see classification results instantly.
