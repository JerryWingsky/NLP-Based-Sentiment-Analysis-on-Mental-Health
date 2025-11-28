# NLP-Based Sentiment Analysis on Mental Health (DAML) ❤️‍🩹

📄 Licensed under CC BY-NC 4.0 — For educational & non-commercial use only.
🔗 [View Full License Terms](https://creativecommons.org/licenses/by-nc/4.0/)

## Overview ✨

A group project for **Data Analytics**, **Sentiment Analysis**, and combined with **Natural Language Processing**, focusing on applying **ML** & **AI** to solve a **Data Problem** of your choice. It classifies **Mental Health Statements** as either **Normal** or **Depressed**. It explores **Practical Solutions** to **Real-World Challenges** in:
- **Text Classification**.
- **Applies Decision Tree & Neural Network Models**.
- **Performs Data Cleaning & Transformation**.

## Project Overview 📌

- Text Data Cleaning, Preprocessing, and Tokenization.
- Application of Decision Tree & Neural Network Models.
- Model Evaluation Metrics (`Accuracy`, `Precision`, `Recall`, `F1-Score`, `Confusion Matrix`, and `ROC Curve & AUC`).
- Practical considerations -> AI in Mental Health Assessment.

## Results 📈
- Best Model Accuracy (Decision Tree): 0.9092 (Best).
- Best Model Accuracy (Neural Network): 0.9484 (Best).
- Accuracy, Precision, Recall, and F1-Score:

<p align="center">
<img src="https://github.com/user-attachments/assets/62f2acde-cdd7-497a-806c-40807988fc4f" alt="Image" width="500"/>
<br/>
<strong><em>Figure 1: Accuracy, Precision, Recall, and F1-Score Results</em></strong>
</p>

- Confusion Matrix Analysis:

|                      | **Predicted Benign**  | **Predicted Malignant** |
|----------------------|-----------------------|----------------------|
| **Actual Benign**    | 7016 (True Negative)  | 318 (False Positive) |
| **Actual Malignant** | 230 (False Negative)  | 3046 (True Positive) |

1. True Positives (3046):
Correctly Predicted **Depressed** Cases.

2. True Negatives (7016):
Correctly Predicted **Normal** Cases.

3. False Positives (318):
**Depressed** Cases Wrongly Classified as **Normal**.

4. False Negatives (230):
**Normal** Cases Wrongly Classified as **Depressed**.

## Results 🤔
- So, based from this **Analysis**, I choose **Neural Network** for the **Confusion Matrix**. The model shows **Strong Performance** in detecting **Normal** or **Depressed** compared to **Decision Tree**.

<p align="center">
<img src="https://github.com/user-attachments/assets/ba39569f-279e-491e-8078-a96b71a62757" alt="Image" width="500"/>
<br/>
<strong><em>Figure 2: Accuracy, Precision, Recall, and F1-Score (Decision Tree) Results</em></strong>
</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/94485210-7069-4cf6-bbdf-3a5abdb51ec0" alt="Image" width="500"/>
<br/>
<strong><em>Figure 3: Confusion Matrix (Decision Tree) Results</em></strong>
</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/4da76ed7-8352-4996-b452-1200601c4f85" alt="Image" width="500"/>
<br/>
<strong><em>Figure 4: Accuracy, Precision, Recall, and F1-Score (Neural Network) Results</em></strong>
</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/43fae94c-a1d5-4938-bb18-35b4f1944e6d" alt="Image" width="500"/>
<br/>
<strong><em>Figure 5: Confusion Matrix (Neural Network) Results</em></strong>
</p>

- Why we use **Neural Network** for the **Confusion Matrix**?
1. **Neural Network Correctly Classifies More**.
    - `Higher True Positive (TP) 3046 > 2806` & `True Negative (TN) 7016 > 6841`.
    - `Lower False Positive (FP) 318 < 493` & `False Negative (FN) 230 < 470`.

2. **Neural Network** has `Higher Precision (0.91 Vs 0.85)` & `Higher Recall (0.93 Vs 0.86)`.

## How to Use 🚀 
- Open the `.ipynb` **Notebook File** in the **Files**.

> 📁 **Note**: This is for **Educational Purposes Only** — no **Real Credentials**, **Access**, or **Confidential Data are Used**.

## Coding Information 🛠
Front-End:
- Google Colab.
- Matplotlib & Seaborn Visualizations.
- Image Display.

Back-End:
- Python (`If-Else`, `Functions`, `Loops`, etc).
- Data Handling & Preprocessing (`ImageDataGenerator`, `Pandas`, `NumPy`, `Sklearn.Preprocessing`, etc).

- `TensorFlow`/`Keras`:
  - `TensorFlow`: Open Source Library developed by Google. Used for Build, Train, and Deploy Neural Network (CNNs).
  - `Keras`: Open Source Library that provides a Python Interface for Neural Networks.

- Google Colab: Free Online Platform to Write & Run Code.

## Big thanks to my teammates: 🙌
1. Jerry Wingsky ([@jrywsky](https://linktr.ee/JerryWingsky))
2. Hu Jiawei (https://github.com/HuJiawei-David)
