# Chatbot-for-Patient-Symptom-Triage-Recommendation

# 🩺 Symptom Triage Chatbot (NLP Capstone – Phase 1)

A rule-based and ML-enhanced chatbot that takes user symptom descriptions and provides triage recommendations:  
→ **Self-Care**, **Consult GP**, or **Emergency**

---

## 🚀 Overview

This project demonstrates a basic NLP pipeline to simulate clinical triage using:
- Named Entity-style symptom extraction
- TF-IDF feature generation
- Logistic Regression classifier
- Multi-turn chatbot loop

---

## 📁 Files Included

| File                          | Description                                      |
|-------------------------------|--------------------------------------------------|
| `phase1_symptom_triage_chatbot.ipynb` | Main Colab notebook (NER + classifier + chatbot) |
| `medical_dialog.csv`          | Simulated training data (5 rows)                |
| `README.md`                   | This file                                        |

---

## 📊 Dataset

We explored several public medical dialogue datasets:
- [MedDialog (GitHub)](https://github.com/UCSD-AI4H/MedDialog)
- [Medical Dialogue Dataset (Kaggle)](https://www.kaggle.com/datasets/xuehaihe/medical-dialogue-dataset)

Due to access issues, we used a custom simulated CSV based on MedDialog structure for Phase 1.

---

## 🛠️ Tech Stack

- Python, Colab
- `pandas`, `scikit-learn`, `spaCy`
- Logistic Regression with TF-IDF pipeline
- Simple input/output chatbot loop

---

## 🔁 Example Chatbot Interaction
User: I have a sore throat and mild fever.
Bot: Based on your symptoms, I recommend: SELF-CARE
Bot: Any other symptoms? (yes/no)
