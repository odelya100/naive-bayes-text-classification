# 📝 Naive Bayes Text Classification

## 📌 Project Overview
This project uses the **20 Newsgroups dataset** to classify text documents into two categories:  
- 🩺 **sci.med** (medical science)  
- 🚀 **sci.space** (space science)  

The goal is to demonstrate a complete **machine learning workflow** for text classification using **Naive Bayes** with **TF-IDF features**.

---

## 🔍 Steps Taken
1. **Load Dataset** – selected two categories from the 20 Newsgroups dataset.  
2. **Text Preprocessing** – converted text into numbers using **Bag of Words** and **TF-IDF**.  
3. **Model Training** – trained a **Multinomial Naive Bayes** classifier.  
4. **Evaluation** – measured **Accuracy, Precision, Recall, F1**, and built a **Confusion Matrix**.  

---

## 📊 Results
- Achieved ~**92–95% Accuracy** on unseen test data.  
- Both categories (medical and space) were classified with high precision and recall.  

---

## 🖼️ Visualizations
- Confusion Matrix (heatmap)  
- Example ROC curve (optional extension)

---

## 🚀 Why This Project is Important
This project demonstrates the ability to:  
- Preprocess and transform real-world text data  
- Apply **Naive Bayes** for classification  
- Evaluate models with meaningful metrics  
- Visualize and communicate results clearly  

---

## 📦 Tech Stack
- **Python** (scikit-learn, NumPy, pandas)  
- **Visualization**: Matplotlib, Seaborn  
- **Environment**: Jupyter Notebook / Google Colab  
