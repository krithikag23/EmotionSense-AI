# 🎭 Emotion Detection using DistilBERT

This project uses **DistilBERT**, a lightweight version of BERT, to classify human text into **six emotions**:

| Label | Emotion |
|------|---------|
| 0 | **Anger** |
| 1 | **Fear** |
| 2 | **Joy** |
| 3 | **Love** |
| 4 | **Sadness** |
| 5 | **Surprise** |

The model is trained on the **`dair-ai/emotion`** dataset from Hugging Face, which provides clean single-label emotional text samples.

---

## 📌 Features
- Uses **pretrained DistilBERT** transformer model
- Fine-tuned for **emotion classification**
- Evaluates accuracy and weighted F1 score
- Supports custom emotion predictions
- Saves model + tokenizer for reuse

---

## 🧠 Model Architecture
- **Base Model:** `distilbert-base-uncased`
- **Task:** Text Classification
- **Output:** 6 emotion classes

---

## 📂 Dataset
-Dataset: **dair-ai/emotion**
-**from datasets import load_dataset**
-**dataset = load_dataset("dair-ai/emotion")**

---
## 🎯 Example Output

-**Text: I am very happy and excited today!**
-**Predicted Emotion: joy**


