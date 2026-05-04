# 🫁Pnuemonia Detection System

* **Project**: CAP 4630 | Intro to Artificial Intelligence
* **Instructor**: Professor Ahmed Imteaj
* **Institution**: Florida Atlantic University
* **Team Members**: Alexander Moller & Christina Pappachan
---

## Table of Contents
* [About the Project](#about-the-project)
* [Objective](#objective)
* [Dataset](#dataset)
* [Performance](#performance)
* [Challenges](#challenges)
* [References](#references)
* [Improvements](#improvements)

---

## About the Project
The Pneumonia Detection System is a Supervised Machine-learning project that uses Artificial Intelligence as a tool to utilizes medical imaging through X-ray imaging to identify if the patient classifies as pneumonia-positive or normal. The project is modeled through multiple Convolutional Neural Networks (CNN) to train, validate, and test the models in order to achieve the highest classification performance.

---

## Objective
The objective of this project is to develop a reliable binary classification model capable of distinguishing pneumonia-positive from normal chest X-rays with high accuracy. By training and comparing multiple CNN architectures, the project aims to identify the model with the highest metrics and performance based on evaluations such as accuracy, precision, F1-Score, recall, and AUC. The ultimate goal is to demonstrate the activity of AI-assisted diagnosis as a supportive tool for medical professionals in detecting and identifying pneumonia more efficiently.

---

## Dataset
* Original dataset: 8,530 frontal chest X-ray images.
* **Split:** 80% Train | 10% Validation | 10% Test

### Training (80%):
* **6824 images** of an even 50/50 split of pneumonia-positive and normal cases.
* **Classes**: Classes are classified through 1: 🔴("PNEUMONIA"), 2: 🟢("NORMAL").

### Validation (10%):
* **852 images** of an even 50/50 split of pneumonia-positive and normal cases.
* **Classes**: Classes are classified through 1: 🔴("PNEUMONIA"), 2: 🟢("NORMAL").
 
### Testing (10%):
* **852 images** of an even 50/50 split of pneumonia-positive and normal cases.
* **Classes**: Classes are classified through 1: 🔴("PNEUMONIA"), 2: 🟢("NORMAL").

---

## Performance
    
### Alexander's Model: Scratch CNN iterations
* **Model 1: Scratch CNN**:
    * **Average Accuracy**: 
    * **Average Precision (P)**: 
    * **Average Recall (R)**: 
    * **Average F1-Score**:]
      
* **Model 2: Scratch CNN + Data Augmentation**:
    * **Average Accuracy**: 
    * **Average Precision (P)**: 
    * **Average Recall (R)**: 
    * **Average F1-Score**:
      
* **Model 3: Scratch CNN + Data Augmentation & Batch Normlization**:
    * **Average Accuracy**: 
    * **Average Precision (P)**: 
    * **Average Recall (R)**: 
    * **Average F1-Score**:

### Christina's Model: CNN vs ResNet50

* **Model 1: Scratch CNN**:
    * **Average Accuracy**: 
    * **Average Precision (P)**: 
    * **Average Recall (R)**: 
    * **Average F1-Score**:
      
* **Model 2: ResNet50 CNN**:
    * **Average Accuracy**: 
    * **Average Precision (P)**: 
    * **Average Recall (R)**: 
    * **Average F1-Score**:
  
---

### Challenges

1. **Overfitting & Generalization**
   * *Challenge*: Early CNN experiments revealed significant overfitting, where the model performed well on training data but failed to generalize to unseen cases.
   * *Solution*: Data augmentation, dropout, batch normalization, and learning rate adjustments were systematically tested and applied to improve generalization performance.

2. **Dataset Split & Evaluation Fairness**
   * *Challenge*: The original dataset split was not structured in a way that allowed for a fair and reliable comparison between models with an original split that had less than 5% for validation and testing.
   * *Solution*: A consistent, balanced test set was created and established that was uniform across all models to ensure evaluation integrity.

3. **Limited Tuning Time & External Validation**
   * *Challenge*: The scope of the project limited the amount of time available for tuning and testing on outside datasets.
   * *Solution*: Additional tuning opportunities and validation against independent datasets are identified as next steps for future development and improvements.

---

## 🔍Improvements 
* **Broaden Detection Features**: Create additional classes to form a multi-class classification tool in the detection process to identify additional lung-related conditions through the images.

---

## References

1. Dataset: https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fyusufmurtaza01%2Fchest-xray-pneumonia-balanced-dataset%2Fdata
