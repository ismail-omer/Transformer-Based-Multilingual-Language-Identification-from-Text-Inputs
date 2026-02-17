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

    🧩 System Modules
    │
    ├── 📂 Dataset
    │   └── Curated multilingual text samples
    │       ├── Multiple languages
    │       ├── Short text inputs
    │       └── Code-mixed data
    │
    ├── 🧹 NLP Preprocessing
    │   ├── Tokenization
    │   ├── Stop-word Removal
    │   └── Lemmatization
    │
    ├── 📊 Exploratory Data Analysis (EDA)
    │   ├── Language distribution analysis
    │   ├── Word frequency patterns
    │   └── Character usage statistics
    │
    ├── 🤖 Feature Extraction (MiniLM)
    │   ├── Transformer-based embeddings
    │   ├── Context-aware semantic vectors
    │   └── Compact high-dimensional representation
    │
    ├── 📉 Baseline Models
    │   ├── Decision Tree Classifier (DTC)
    │   ├── K-Nearest Neighbors (KNN)
    │   └── Naïve Bayes Classifier (NBC)
    │
    ├── 🌲 Proposed Model
    │   └── Random Forest Classifier (RFC)
    │       ├── Ensemble learning
    │       ├── Robust to high-dimensional data
    │       └── Improved generalization performance
    │
    └── 🌐 Flask Web Application
        ├── User text input interface
        ├── Real-time prediction output
        └── Blue & white responsive UI
    





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
(Ensure Python 3.12 is installed)
##  1.  Clone the Repository

     git clone https://github.com/ismail-omer/Transformer-Based-Multilingual-Language-Identification-from-Text-Inputs.git

     cd Transformer-Based-Multilingual-Language-Identification-from-Text-Inputs

 ## 2.  Create Virtual Environment

     python -m venv venv


- Activate:


- Windows

      .\venv\Scripts\activate


- Mac/Linux

      source venv/bin/activate



## 3.Install Requirements
### 1. Upgrade core tooling (critical)

       python -m pip install --upgrade pip setuptools wheel
- This avoids 80% of installation failures.
    
### 2. Install system-level dependency (Graphviz)
- graphviz will not work without this.
- Download (official):

      https://graphviz.org/download/

- Choose:

      Windows 64-bit Installer (.exe)

- During install:

- ✔ Check “Add Graphviz to PATH”

- After installation, restart PowerShell and re-activate venv.
- Verify:

      dot -V
- You should see a Graphviz version.

### 3. Install PyTorch FIRST (very important)

Do NOT rely on pip default for torch.

Official PyTorch selector (bookmark this):

    https://pytorch.org/get-started/locally/

### For most laptops (CPU-only, safe choice):

    pip install torch==2.8.0 torchvision==0.23.0 --index-url https://download.pytorch.org/whl/cpu

### 4. Install TensorFlow (standalone step)

    pip install tensorflow==2.17.0

### 5. Create requirements.txt (clean & controlled)

    notepad requirements.txt

Paste exactly this (already ordered to reduce conflicts):

    audioread==3.0.1
    beautifulsoup4==4.13.4
    bleach==6.2.0
    catboost==1.2.8
    cryptography==46.0.2
    Django==5.2.7
    django-cors-headers==4.9.0
    djangorestframework==3.16.1
    email-validator==2.3.0
    emoji==2.15.0
    Flask==3.1.2
    flask-cors==6.0.1
    Flask-Login==0.6.3
    Flask-SQLAlchemy==3.1.1
    Flask-WTF==1.2.2
    google-ai-generativelanguage==0.6.15
    google-api-core==2.29.0
    google-api-python-client==2.188.0
    google-auth==2.48.0
    google-auth-httplib2==0.3.0
    google-generativeai==0.8.6
    google-pasta==0.2.0
    googleapis-common-protos==1.72.0
    graphviz==0.21
    h5py==3.14.0
    imbalanced-learn==0.14.0
    imodels==2.0.0
    Jinja2==3.1.6
    joblib==1.4.2
    jupyter==1.1.1
    jupyterlab==4.4.5
    keras==3.11.3
    langcodes==3.5.0
    langdetect==1.0.9
    language_data==1.3.0
    librosa==0.11.0
    lightgbm==4.6.0
    lmdb==1.7.5
    matplotlib==3.10.3
    networkx==3.5
    ngboost==0.5.6
    nltk==3.9.1
    numba==0.61.2
    numpy==1.26.4
    pandas==2.3.1
    pillow==11.3.0
    plotly==6.3.0
    protobuf==5.29.5
    pycryptodome==3.23.0
    pymongo==4.16.0
    PyMySQL==1.1.2
    redis==6.4.0
    requests==2.32.4
    resampy==0.4.3
    safetensors==0.6.2
    scikit-image==0.26.0
    scikit-learn==1.6.1
    scipy==1.13.1
    seaborn==0.13.2
    soundfile==0.13.1
    SQLAlchemy==2.0.46
    tinydb==4.8.2
    tokenizers==0.21.4
    tqdm==4.67.1
    transformers==4.47.0
    ultralytics==8.3.184
    urllib3==2.5.0
    xgboost==3.0.4
    zipp==3.23.0

Ctrl + s & Close the notepad
### 7. Install everything (single command)

     pip install -r requirements.txt

### 6. verification
Copy-paste exactly this:

    python -c "import transformers, torch, tensorflow, sklearn, pandas; print('Transformers:',       transformers.__version__); print('Torch:', torch.__version__); print('TensorFlow:', tensorflow.__version__); print('Scikit-learn:', sklearn.__version__); print('Pandas:', pandas.__version__)"

Expected output (versions may vary slightly):

    Transformers: 4.47.0
    Torch: 2.8.0
    TensorFlow: 2.17.0
    Scikit-learn: 1.6.1
    Pandas: 2.3.1



## ▶ Running the Application

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









