# 🌾 Laboratory Work 2: Plant Species Image Classification

An AI-powered image classification system that identifies different cereal crop species using deep learning.

---

# 📌 A. Project Overview

## 🌱 Project Description

This project focuses on building an **image classification model** capable of identifying different **cereal crop species** from images.

The model was trained using labeled images of the following crops:

- Finger Millet  
- Corn (Maize)  
- Rye  
- Pearl Millet  
- Rice  
- Barley  
- Oats  
- Sorghum  
- Buckwheat  
- Foxtail Millet  

By analyzing visual features such as shape, texture, and grain structure, the system can automatically recognize the crop type from an input image.

---

## 🎯 Purpose of the Model

This system aims to assist:

- 🌾 Farmers  
- 🧪 Agricultural Researchers  
- 🌿 Agronomists  

It supports:

- Crop monitoring  
- Farm management  
- Agricultural data collection  

Automating crop recognition reduces manual effort, minimizes human error, and improves efficiency in agricultural practices.

---

# 🌾 B. Cereal Crop Dataset

| Image | Crop Name |
|:-----:|:---------:|
| <img src="https://github.com/user-attachments/assets/40980c22-87f1-471a-bcfa-e831fac7b73e" width="200" /> | Finger Millet |
| <img src="https://github.com/user-attachments/assets/e8af36f1-e96e-44cf-9267-1cc91cc4d84d" width="200" /> | Corn (Maize) |
| <img src="https://github.com/user-attachments/assets/29be8a61-9824-420d-bd6e-f3999406b290" width="200" /> | Rye |
| <img src="https://github.com/user-attachments/assets/38fd7a02-1e03-4015-b7d4-c4e53d1b92dc" width="200" /> | Pearl Millet |
| <img src="https://github.com/user-attachments/assets/34a6728a-535f-4f3b-b21d-e15989d6be60" width="200" /> | Rice |
| <img src="https://github.com/user-attachments/assets/cbbb761d-111b-4868-920d-17a7df7353ef" width="200" /> | Barley |
| <img src="https://github.com/user-attachments/assets/2c03d044-3917-47a2-ae74-5ccc9b537004" width="200" /> | Oats |
| <img src="https://github.com/user-attachments/assets/4ad8870e-ca91-44de-a48d-01918d71bf4b" width="200" /> | Sorghum |
| <img src="https://github.com/user-attachments/assets/d7cc803f-43a1-4405-939f-6cadd3a47e2e" width="200" /> | Buckwheat |
| <img src="https://github.com/user-attachments/assets/a51a5023-bee9-4ef9-b947-ed5a5e852800" width="200" /> | Foxtail Millet |

---

# ⚙️ C. Model Training Details

<p align="center">
  <img src="https://github.com/user-attachments/assets/6bf9aec2-c6cc-4292-996e-26c97c64c287" width="450"/>
</p>

## 🔧 Training Configuration

| Parameter | Value | Purpose |
|------------|--------|----------|
| Epochs | 50 | Allowed the model to fully learn patterns while avoiding overfitting |
| Batch Size | 16 | Balanced training stability and computational efficiency |
| Learning Rate | 0.001 | Ensured smooth and gradual optimization |

### Why I Chose These Values

- **50 Epochs** gave the model enough time to converge and stabilize.
- **Batch Size of 16** provided consistent gradient updates without memory issues.
- **Learning Rate of 0.001** prevented overshooting and allowed controlled reduction in loss.

---

# 📈 D. Model Evaluation

To evaluate my model’s performance, I monitored both **accuracy** and **loss** curves during training.

These graphs helped me determine:
- How well the model learned from training data
- Whether it generalizes well to unseen data
- If overfitting occurred

---

## 1️⃣ Training Accuracy

<p align="center">
  <img src="https://github.com/user-attachments/assets/440279ca-a122-430f-955c-bd6cfa498e23" width="500"/>
</p>

The training accuracy rapidly increased and reached nearly **100%**, indicating that the model successfully captured patterns from the training dataset.

---

## 2️⃣ Validation Accuracy

<p align="center">
  <img src="https://github.com/user-attachments/assets/3b98c72f-126d-44c1-8d77-e856ce87f6ab" width="500"/>
</p>

The validation accuracy reached approximately **98–99%**, which is very close to the training accuracy.

This confirms:
- Strong generalization ability  
- Minimal overfitting  
- Stable model performance  

---

## 3️⃣ Training Loss

<p align="center">
  <img src="https://github.com/user-attachments/assets/87a5af59-1445-43c5-99dd-3194c086b015" width="500"/>
</p>

The training loss started high and quickly decreased toward zero, showing that prediction errors were minimized as training progressed.

---

## 4️⃣ Validation Loss

<p align="center">
  <img src="https://github.com/user-attachments/assets/55feda65-fedd-4075-b3b9-5fdbf3188af2" width="500"/>
</p>

The validation loss remained low and stable, confirming that the model performs well on unseen data.

---

# ✅ Overall Performance Summary

- 🎯 Training Accuracy: ~100%  
- 🎯 Validation Accuracy: ~98–99%  
- 📉 Training Loss: Near 0  
- 📉 Validation Loss: Low and stable  
- 🔍 Overfitting: Minimal  
- 🚀 Generalization: Strong  

## 📌 Final Conclusion

Based on the evaluation results, the model learned effectively and performs reliably in classifying cereal crop species.

---

# 🧠 Reflection

### 1. How did the number of images per class affect accuracy?

Classes with more images achieved higher accuracy because the model had more examples to learn from. Classes with fewer images were more prone to misclassification.

---

### 2. Which species were most commonly misclassified?

Visually similar crops such as finger millet, rice, and sorghum were sometimes misclassified due to similar textures and grain structures.

---

### 3. How did hyperparameters affect results?

- Increasing epochs improved convergence but risked overfitting.
- Larger batch sizes trained faster but sometimes reduced precision.
- Learning rate adjustments affected stability and convergence speed.

---

### 4. Challenges During Dataset Collection

- Limited high-quality images  
- Inconsistent lighting and angles  
- Similar-looking crops  
- Labeling consistency issues  

---

### 5. Future Improvements

To further improve the model, I would:

- Increase dataset size for underrepresented classes  
- Apply data augmentation techniques  
- Experiment with deeper neural network architectures  
- Fine-tune hyperparameters further  

---

# 🔗 Model Link

Teachable Machine Model:  
https://teachablemachine.withgoogle.com/models/[YOUR_MODEL_LINK]

---
