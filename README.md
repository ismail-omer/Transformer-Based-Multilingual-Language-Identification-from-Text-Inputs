  ## 🌐 Multilingual Language Identification System
  Transformer-Based Text Language Classification (MiniLM + Random Forest)
<p align="center"> <img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python" /> <img src="https://img.shields.io/badge/Flask-Web%20App-white?style=for-the-badge&logo=flask" /> <img src="https://img.shields.io/badge/Transformers-MiniLM-blue?style=for-the-badge&logo=huggingface" /> <img src="https://img.shields.io/badge/Model-Random%20Forest-white?style=for-the-badge" /> </p>


## 🎯 Project Overview:
  This project implements a Transformer-Based Multilingual Language Identification System capable of accurately classifying short and informal       text inputs across multiple languages.


### Unlike traditional statistical approaches, this system leverages:


- MiniLM transformer embeddings for deep semantic representation

- Random Forest Classifier (RFC) for robust high-dimensional classification

- A Flask-based web interface for real-time language prediction



## The solution is optimized for:


  1.	Short text inputs

  2.	Informal language

  3.	Code-mixed content

  4.	Social media text


## Table of Contents

- [Project Architecture](#project-architecture)
- [System Modules](#system-modules)
- [Prototype (UI Preview)](#prototype-ui-preview)
- [Tech Stack](#tech-stack)
- [Installation Guide](#installation-guide)
- [Running the Application](#running-the-application)
- [Model Pipeline](#model-pipeline-technical-flow)
- [Baseline vs Proposed Model](#baseline-vs-proposed-model)
- [Hardware & Software Requirements](#hardware--software-requirements)
- [Future Improvements](#future-improvements)
- [Conclusion](#conclusion)




## 🧠 Project Architecture:

<img width="939" height="309" alt="image" src="https://github.com/user-attachments/assets/e1eff838-809e-4f74-8295-4c825f765cac" />



## Architecture Highlights

- NLP preprocessing (tokenization, stopword removal, lemmatization)

- MiniLM transformer for compact semantic embeddings

- Ensemble-based Random Forest classifier

- Real-time prediction via Flask web deployment



## 🧩 System Modules

<img width="1173" height="1280" alt="image" src="https://github.com/user-attachments/assets/d64d2ac6-7694-4e5f-b18a-e17b6d51529d" />





## 🎨 Prototype – Web Interface


<img width="1895" height="854" alt="Screenshot 2026-02-12 133704" src="https://github.com/user-attachments/assets/db7fdc15-017e-48f8-a84f-04156c312180" />



## 🛠 Tech Stack


### Backend:


- Python 3.12

- Flask 3.1.2

- Transformers 4.47.0

- Torch 2.8.0

- Scikit-learn 1.6.1

- NLTK


### Frontend:


- HTML5

- CSS3

- JavaScript


### ML Libraries:


-	Random Forest (Scikit-learn)

-	MiniLM (HuggingFace Transformers)


## 💻 Hardware & Software Requirements


### Software:


  -	Python 3.12.0

  -	Windows OS (Tested)


### Hardware:


  -	Intel i5 Processor

  -	8 GB RAM

  -	512 GB Storage


## 🚀 Installation Guide

  1.  Clone the Repository

     git clone https://github.com/ismail-omer/ismail-omer/Transformer-Based-Multilingual-Language-Identification-from-Text-Inputs.git

     cd Transformer-Based-Multilingual-Language-Identification-from-Text-Inputs

  2.  Create Virtual Environment

     python -m venv venv


- Activate:


- Windows

      .\venv\Scripts\activate


- Mac/Linux

      source venv/bin/activate



3.Install Requirements

    pip install -r requirements.txt



(Ensure Python 3.12 is installed)



▶ Running the Application

    python app.py


Open browser:

    http://127.0.0.1:5000




## 🔬 Model Pipeline (Technical Flow)

1. **User Input Acquisition**  
   Raw text is received through the web interface.

2. **Text Preprocessing (NLTK)**  
   The input text undergoes normalization, tokenization, stop-word removal, and lemmatization to prepare it for embedding generation.

3. **Feature Extraction – MiniLM Embeddings**  
   The preprocessed text is passed through the MiniLM transformer model to generate dense, low-dimensional semantic embeddings.

4. **Classification – Random Forest**  
   The generated embedding vectors are fed into a trained Random Forest classifier for language prediction.

5. **Prediction Output**  
   The predicted language label is returned to the Flask application and displayed in the user interface.




## 📊 Baseline vs Proposed Model

| Model            | Type             | Performance     |
|------------------|------------------|-----------------|
| DTC              | Tree-based       | Moderate        |
| KNN              | Distance-based   | Moderate        |
| NBC              | Probabilistic    | Moderate        |
| RFC (Proposed)   | Ensemble         | High Accuracy   |



## RFC improves:


  -	Bias reduction

  -	Variance control

  -	Generalization performance




## 🌍 Applications


  1.	Real-time translation services

  2.	Multilingual chatbots

  3.	Social media analytics

  4.	Cross-border communication tools




## 🔮 Future Improvements


  -	Replace RFC with fine-tuned transformer classifier

  -  Add REST API endpoint
  
  -	Docker containerization

  -	Cloud deployment (AWS / GCP)

  -	Support for additional low-resource languages




## 📌 Conclusion


This system demonstrates how transformer-based embeddings combined with ensemble learning significantly enhance multilingual text classification accuracy, particularly for short and informal content.

It bridges NLP research and real-world deployment through a scalable Flask web application.









