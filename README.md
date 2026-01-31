# WIDS_2026

This repository contains my week-wise learnings, notes, and code submissions as part of the WIDS 2026 program. The focus is on building strong foundations in Computer Vision and Natural Language Processing, progressing from fundamentals to practical implementations.

---

## Week 1 – Computer Vision Foundations

### Overview

Week 1 focuses on the fundamentals of Computer Vision and the tooling required to work with visual data. The goal is to understand how machines interpret images and how raw pixel data is transformed into meaningful representations for learning.

### Topics Covered

* Introduction to Computer Vision and real-world applications
* Python basics for machine learning workflows
* Environment setup using Google Colab and local GPU-enabled Conda environments
* PyTorch fundamentals for deep learning
* OpenCV for image processing
* Image preprocessing and transformation techniques
* Neural Networks and Convolutional Neural Networks (CNNs)
* Transfer Learning and feature extraction using pretrained models

### Key Learnings

* Understood how images are represented as numerical data and processed by models
* Learned the importance of preprocessing steps such as resizing, normalization, and augmentation
* Gained familiarity with OpenCV for classical image processing tasks
* Developed intuition for CNN architectures and how convolutions extract visual features
* Learned when and why to use transfer learning for small or limited datasets

### Submissions

* Code notebooks covering Python setup, image preprocessing, CNN basics, and transfer learning experiments

---

## Week 2 – Introduction to Natural Language Processing

### Overview

Week 2 introduces Natural Language Processing (NLP), focusing on how machines process, understand, and model human language. The emphasis is on text preprocessing pipelines and classical text representation techniques.

### Topics Covered

* Fundamentals of Natural Language Processing
* NLP terminology: corpus, documents, vocabulary, language models
* NLP tasks at corpus, document, sentence, and token levels
* Challenges in NLP such as ambiguity, large vocabulary size, and contextual meaning
* Text preprocessing pipeline
* Tokenization techniques (word, sentence, subword)
* Stopword removal, stemming, and lemmatization
* Text vectorization methods: Bag of Words and TF-IDF
* Encoding techniques: label encoding, one-hot encoding
* Word embeddings and Word2Vec intuition
* Regular expressions for text cleaning and pattern matching
* Natural Language Toolkit (NLTK) for NLP tasks

### Key Learnings

* Understood how raw text is transformed into structured numerical representations
* Learned the role of preprocessing in improving model performance and efficiency
* Gained clarity on classical NLP representations such as BoW and TF-IDF
* Developed intuition for word embeddings and semantic representations
* Learned to use regex and NLTK for practical text processing tasks

### Submissions

* Code notebooks implementing text preprocessing pipelines
* Experiments with BoW and TF-IDF representations
* NLP tasks using NLTK and regex-based cleaning

---

# Week 3 – Bridging Computer Vision + NLP for Image Captioning and Explainability

## Overview
Week 3 connects Computer Vision and Natural Language Processing through multimodal learning and image captioning. The focus is on encoder–decoder architectures, attention mechanisms, Vision Transformers, and Explainable AI techniques. The practical work emphasizes understanding CNN model behavior using visualization and Grad-CAM.

---

## Topics Covered

- Image captioning as a multimodal (vision + language) task
- Encoder–decoder architectures for caption generation
- CNN and Vision Transformer (ViT) as image encoders
- LSTM and Transformer-based caption decoders
- Attention mechanisms for word–region alignment
- Explainable AI (XAI) methods for vision models
- Grad-CAM and attention heatmap visualization

---

## Practical Implementation (Assignment)

- Loaded pretrained ResNet-18 and fine-tuned final layer
- Performed image classification on CIFAR-10
- Visualized convolutional filters (early and deep layers)
- Extracted and plotted intermediate feature maps
- Implemented Grad-CAM for prediction explainability
- Generated heatmaps for correct predictions
- Analyzed a misclassified example using Grad-CAM

---

## Key Learnings

- Understood how vision and language models are combined
- Learned encoder–decoder multimodal design
- Built intuition for Vision Transformers
- Applied attention for interpretability
- Used CNN visualization techniques
- Implemented Grad-CAM for model explanation
- Evaluated model behavior on success and failure cases

---

## Submissions

- Week 3 notebook with XAI experiments
- Filter and feature map visualizations
- Grad-CAM outputs (correct + failure cases)
- Short interpretability report

