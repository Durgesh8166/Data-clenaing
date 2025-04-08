# 🧠 EEG Data Cleaning & Visualization Toolkit

A modular Python-based toolkit to automate data cleaning, standardization, and visualization of raw neuroscience datasets.  
Built for **Google Summer of Code 2025** under **INCF** (International Neuroinformatics Coordinating Facility).

---

## 🚀 Overview

Neuroscience researchers often work with unstructured, noisy data from various sources (EEG, patient records, event logs). This project simplifies and standardizes the preprocessing stage by:

- Cleaning and normalizing tabular data
- Extracting useful fields like phone/email using Regex
- Visualizing EEG signals and missing data patterns
- Outputting clean, research-ready datasets

---

## 📂 Dataset Used

**Complete EEG Dataset**  
📥 [Kaggle Link](https://www.kaggle.com/datasets/amananandrai/complete-eeg-dataset)  
Includes 35+ CSV files with patient metadata, EEG recordings, event labels, etc.

---

## ✨ Features

- ✅ Load multiple file formats (CSV, JSON)
- 🧹 Missing value handling
- 📞 Extract contact info (phone/email) with Regex
- 📈 Time-series plots using Matplotlib & Seaborn
- 🔍 Correlation matrices & FFT (optional)
- 📊 Interactive dashboard using Streamlit
- 📤 Export clean files (CSV / NumPy / JSON)

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Streamlit**
- **Regular Expressions**
- **Google Colab** for prototyping

---
