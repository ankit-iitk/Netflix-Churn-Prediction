# 🎬 Netflix Customer Churn Prediction using Deep Learning

This project predicts customer churn for a Netflix-like platform using an **Artificial Neural Network (ANN)** built with **TensorFlow/Keras**. It helps identify users who are likely to stop using the service, empowering businesses to take preventive action.

---

## 🚀 Project Overview

Customer churn is a critical metric for subscription-based businesses. Retaining existing customers is far more cost-effective than acquiring new ones. This project builds a predictive model to classify whether a customer is likely to churn based on features like:

- Favorite Genre  
- Age  
- Gender  
- Number of Profiles  
- Subscription Type  
- Device Used
- Watch Hours
- Monthly fee
- Last Login Days
- Region
- Payment method
- Average Watch time per day

---

## 🧠 Model Architecture

We use a **Deep Learning ANN** model with the following architecture:

- Input Layer: Based on the number of features  
- Hidden Layers:
  - Dense(64) + ReLU + Dropout(0.3)  
  - Dense(32) + ReLU + Dropout(0.3)  
  - Dense(16) + ReLU + Dropout(0.3)  
- Output Layer: Dense(1) with Sigmoid Activation  

**Loss Function**: Binary Crossentropy  
**Optimizer**: Adam  
**Metrics**: Accuracy  
**Batch Size**: 32  
**Epochs**: 20  

---

## 🛠️ Technologies Used

- Python  
- Pandas & NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib / Seaborn (for EDA)  
- Flask or Streamlit (optional, for deployment)

---

## 📊 Evaluation

- Confusion Matrix  
- Accuracy Score  
- Precision / Recall (optional)  
