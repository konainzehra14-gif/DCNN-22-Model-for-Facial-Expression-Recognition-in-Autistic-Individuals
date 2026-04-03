# DCNN 22 Model for Facial Expression Recognition in Autistic Individuals

This project implements facial expression recognition using a Deep Convolutional Neural Network (DCNN 22).
The model classifies facial expressions into seven categories:

1. Angry
2. Disgust
3. Fear
4. Happy
5. Sad
6. Surprise
7. Neutral

---

## 📊 Dataset Information

### 1. FER2013 Dataset
- Source: Kaggle  
- URL: [https://www.kaggle.com/datasets/msambare/fer2013](https://www.kaggle.com/datasets/msambare/fer2013)  
- Format: 48x48 grayscale images stored as pixel values in CSV  

### 2. CK+ Dataset (Extended Cohn-Kanade)
- Source: Official dataset  
- URL: [http://www.jeffcohn.net/Resources/](http://www.jeffcohn.net/Resources/)  
- Format: Image sequences labeled with facial expressions

## 💻 Code Files

- `dcnn_ckplus.py` → Training and evaluation on CK+ dataset  
- `dcnn_fer2013.py` → Training and evaluation on FER2013 dataset  
- `preprocessing.py` → Image preprocessing, face detection, and landmark extraction   
---

## ⚙️ Requirements

Install dependencies using:

pip install -r requirements.txt

---

## 📊 Dataset Information

Follow the steps below to reproduce the experiments.

#### Clone the Repository
- git clone https://github.com/konainzehra14-gif/DCNN-22-Model-for-Facial-Expression-Recognition-in-Autistic-Individuals
- cd DCNN-22-Model-for-Facial-Expression-Recognition-in-Autistic-Individuals
#### Install Required Libraries
- pip install -r requirements.txt
#### Prepare Dataset
Download the datasets:
- #### FER2013 Dataset: 
https://www.kaggle.com/datasets/msambare/fer2013
- #### CK+ Dataset: 
http://www.jeffcohn.net/resources/
Place the datasets in the directories of dataset
#### Run Preprocessing
python preprocessing.py
#### Train the Model
- python dcnn22_fer2013.py
- python dcnn22_ck+.py

---


## Methodology

The proposed system implements a Deep Convolutional Neural Network (DCNN-22) for Facial Expression Recognition (FER).
The workflow consists of the following stages:

#### Data Preprocessing:
Facial images from the FER2013 and CK+ datasets are preprocessed, including resizing, normalization, and dataset preparation.
#### Feature Extraction: 
DCNN-22 extracts hierarchical features from facial images.
#### Model Training: 
The DCNN model is trained on labeled facial expression images to learn discriminative features for classification.
#### Emotion Classification: 
The trained model predicts facial emotion classes (happiness, sadness, anger, surprise, fear, disgust, and neutral).


## Evaluation

The DCNN-22 model is evaluated using two benchmark facial expression datasets:
- FER2013 Dataset
- CK+ Dataset

Performance metrics include:
-  Accuracy
-  Precision
-  Recall
-  F1 Score
-  Confusion Matrix

Datasets are divided into training and testing sets to measure generalization performance. Experimental results demonstrate that the DCNN-22 model effectively learns facial emotion representations and achieves competitive performance on both datasets. 

---

## Reproducibility

To ensure reproducibility:

- The full source code is publicly available in this repository.
- Dataset sources are provided with download links.
- Preprocessing steps and training scripts are included.
- Model parameters and architecture are defined in the code.

Researchers can reproduce the experiments by following the instructions provided in the "How to run" section.

## License & Contribution Guidelines
#### License:
- This project is for academic and research purposes only. Dataset licenses belong to the original providers.
#### Contributions:
- Pull requests and suggestions for improvements are welcome for research purposes.

## Author
Konain Zehra
