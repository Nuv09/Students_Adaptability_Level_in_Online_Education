## 🧠 Students’ Adaptability Level Prediction in Online Education

**Our Motivation**:  
We decided to work on this problem because online education has become increasingly prevalent, especially after the COVID-19 pandemic. Understanding students' adaptability to this mode of learning is crucial for improving educational outcomes. This dataset provides valuable insights into factors influencing adaptability, allowing us to explore patterns and build predictive models that can help educators and institutions better support students. By analyzing the adaptability levels, we hope to contribute to the improvement of online education strategies.

This project aims to analyze and predict students' adaptability levels in online learning environments using data mining techniques. By leveraging a real-world dataset from Kaggle with 1,205 entries and 11 attributes, we applied both **supervised** (classification using Decision Trees) and **unsupervised** (clustering using K-Means) learning methods.

---


### 📊 Objectives
- Identify key factors influencing student adaptability (e.g., age, device type, internet access).
- Classify students into high or low adaptability levels using decision trees (with Gini Index and Information Gain).
- Discover natural groupings among students using clustering analysis.

---


### ⚙️ Techniques Used
- **Preprocessing:** Encoding, normalization, balancing, outlier detection
- **Classification:** Decision Tree (IG & Gini) with multiple train/test splits
- **Clustering:** K-Means, evaluated with Silhouette & Elbow methods
- **Evaluation Metrics:** Accuracy, Precision, Sensitivity, Specificity, Error rate
  
---

### 📌 Key Results
- Gini-based decision tree (80% train / 20% test) gave the best performance with **68% accuracy**.
- Clustering showed optimal results with **K=2**, indicating two distinct student adaptability profiles.
  
---


### 🧰 Tools & Libraries
- Python (Pandas, Sklearn, Matplotlib)
- Jupyter Notebook
- Kaggle dataset: [Students Adaptability Level in Online Education](https://www.kaggle.com/datasets/mdmahmudulhasansuzan/students-adaptability-level-in-online-education)

---

### Done by: 
Raghd Hassan
nouf 
Raghad 

