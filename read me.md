# DCNN 22 Model for Facial Expression Recognition in Autistic Individuals

## Description
This project is about facial expression recognition using a Deep Convolutional Neural Network (DCNN 22). The model is trained and evaluated on the **CK+** and **FER2013** datasets, classifying emotions into seven categories:  

- Angry  
- Disgust  
- Fear  
- Happy  
- Sad  
- Surprise  
- Neutral  

The project also includes **image preprocessing**, **face detection**, and **facial landmark detection** for improved accuracy.

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
- 
## 💻 Code Files

- `dcnn_ckplus.py` → Training and evaluation on CK+ dataset  
- `dcnn_fer2013.py` → Training and evaluation on FER2013 dataset  
- `preprocessing.py` → Image preprocessing, face detection, and landmark extraction   
---

## ⚙️ Requirements

Install dependencies using:

```bash
pip install -r requirements.txt

## How to Run
1. Download datasets from above links  
2. Set dataset path in code  
3. Run python files  

## Methodology
- Image preprocessing (resize, normalization)  
- Face detection using dlib  
- Facial landmark detection  
- Deep CNN model for classification  

## Evaluation
- Accuracy  
- Precision  
- Recall  
- F1-score

## Reproducibility
Install libraries (pip install -r requirements.txt)
Download datasets
Set dataset paths
Run scripts

## License
This project is for academic and research purposes only. Dataset licenses belong to the original providers.

- ## Author
Konain Zehra

