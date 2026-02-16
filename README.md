  ## 🌐 Multilingual Language Identification System
  Transformer-Based Text Language Classification (MiniLM + Random Forest)
<p align="center"> <img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python" /> <img src="https://img.shields.io/badge/Flask-Web%20App-white?style=for-the-badge&logo=flask" /> <img src="https://img.shields.io/badge/Transformers-MiniLM-blue?style=for-the-badge&logo=huggingface" /> <img src="https://img.shields.io/badge/Model-Random%20Forest-white?style=for-the-badge" /> </p>

________________________________________
## 🎯 Project Overview:
  This project implements a Transformer-Based Multilingual Language Identification System capable of accurately classifying short and informal       text inputs across multiple languages.


### Unlike traditional statistical approaches, this system leverages:


  1.	MiniLM transformer embeddings for deep semantic representation

  2.	Random Forest Classifier (RFC) for robust high-dimensional classification

  3.	A Flask-based web interface for real-time language prediction

________________________________________

## The solution is optimized for:


  1.	Short text inputs

  2.	Informal language

  3.	Code-mixed content

  4.	Social media text
________________________________________

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

________________________________________


## 🧠 Project Architecture:

<img width="939" height="309" alt="image" src="https://github.com/user-attachments/assets/e1eff838-809e-4f74-8295-4c825f765cac" />



## Architecture Highlights

  1.	NLP preprocessing (tokenization, stopword removal, lemmatization)

  2.	MiniLM transformer for compact semantic embeddings

  3.  Ensemble-based Random Forest classifier

  4.	Real-time prediction via Flask web deployment

________________________________________

## 🧩 System Modules

<img width="1173" height="1280" alt="image" src="https://github.com/user-attachments/assets/d64d2ac6-7694-4e5f-b18a-e17b6d51529d" />


________________________________________


## 🎨 Prototype – Web Interface


<img width="1895" height="854" alt="Screenshot 2026-02-12 133704" src="https://github.com/user-attachments/assets/db7fdc15-017e-48f8-a84f-04156c312180" />



## 🛠 Tech Stack


### Backend:


  1.	Python 3.12

  2.	Flask 3.1.2

  3.	Transformers 4.47.0

  4.	Torch 2.8.0

  5.	Scikit-learn 1.6.1

  6.	NLTK


### Frontend:


  1.	HTML5

  2.	CSS3

  3. JavaScript


### ML Libraries:


  1.	Random Forest (Scikit-learn)

  2.	MiniLM (HuggingFace Transformers)


## 💻 Hardware & Software Requirements


### Software:


  1.	Python 3.12.0

  2.	Windows OS (Tested)


### Hardware:


  1.	Intel i5 Processor

  2.	8 GB RAM

  3.	512 GB Storage


## 🚀 Installation Guide

  1.  Clone the Repository

     git clone https://github.com/ismail-omer/ismail-omer/Transformer-Based-Multilingual-Language-Identification-from-Text-Inputs.git

     cd your-repo-name

  2.  Create Virtual Environment

     python -m venv venv


Activate:


Windows

    venv\Scripts\activate


Mac/Linux

    source venv/bin/activate


  3. Install Requirements

    pip install -r requirements.txt

(Ensure Python 3.12 is installed)

________________________________________


▶ Running the Application

    python app.py


Open browser:

    http://127.0.0.1:5000


________________________________________


## 🔬 Model Pipeline (Technical Flow)


  1.	User inputs text

  2.	Preprocessing using NLTK

  3.	MiniLM generates sentence embeddings

  4.	Embeddings passed to Random Forest classifier

  5.	Language predicted and returned to UI

________________________________________

## 📊 Baseline vs Proposed Model

| Model            | Type             | Performance     |
|------------------|------------------|-----------------|
| DTC              | Tree-based       | Moderate        |
| KNN              | Distance-based   | Moderate        |
| NBC              | Probabilistic    | Moderate        |
| RFC (Proposed)   | Ensemble         | High Accuracy   |



## RFC improves:


  1.	Bias reduction

  2.	Variance control

  3.	Generalization performance

________________________________________


## 🌍 Applications


  1.	Real-time translation services

  2.	Multilingual chatbots

  3.	Social media analytics

  4.	Cross-border communication tools

________________________________________


## 🔮 Future Improvements


  1.	Replace RFC with fine-tuned transformer classifier

  2. Add REST API endpoint
  
  3.	Docker containerization

  4.	Cloud deployment (AWS / GCP)

  5.	Support for additional low-resource languages

________________________________________


## 📌 Conclusion


This system demonstrates how transformer-based embeddings combined with ensemble learning significantly enhance multilingual text classification accuracy, particularly for short and informal content.

It bridges NLP research and real-world deployment through a scalable Flask web application.









