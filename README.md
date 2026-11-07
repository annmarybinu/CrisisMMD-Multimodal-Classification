# CrisisMMD-Multimodal-Classification

# Multimodal Identification of Informative Social Media Posts for Disaster Response

## Project Overview

This project investigates whether combining text and image information improves the classification of informative disaster-related social media posts.

It uses pretrained DistilBERT and EfficientNet-B0 encoders to extract text and image features and compares four approaches:
- Text-only
- Image-only
- Early fusion
- Late fusion

## Dataset

**QCRI CrisisMMD v2.0**

Dataset: https://huggingface.co/datasets/QCRI/CrisisMMD
The dataset is downloaded through the notebook and is not included in this repository.

## Technologies Used

- Python
- PyTorch and Torchvision
- Hugging Face Transformers
- DistilBERT
- EfficientNet-B0
- Scikit-learn
- Pandas and NumPy
- Matplotlib

The notebook contains the package installation and environment setup.
