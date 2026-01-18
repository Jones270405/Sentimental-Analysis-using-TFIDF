# Task 2: Sentiment Analysis using NLP  
**Machine Learning Internship – Elitech**

---

## Overview
This project is part of **Task 2** of the **Machine Learning Internship at Elitech**.  
The objective of this task is to perform **Sentiment Analysis** on customer reviews using **Natural Language Processing (NLP)** techniques and evaluate the performance of the model.

---

## Dataset
- **Name:** Customer Reviews Dataset  
- **Format:** CSV file  

### Description
The dataset contains customer-related information such as demographic details, ratings, and review text.  
Since explicit sentiment labels were not available, **sentiment was derived from customer ratings**, where higher ratings indicate positive sentiment and lower ratings indicate negative sentiment.

---

## Problem Statement
To build a **Sentiment Analysis model** that learns patterns from customer review text and classifies reviews as **Positive** or **Negative** using NLP techniques.

---

## Tools & Technologies Used
- **Python**
- **Jupyter Notebook**

### Libraries
- `pandas`
- `numpy`
- `scikit-learn`
- `re`

---

## Workflow
1. Loaded and explored the Customer Reviews dataset  
2. Performed text preprocessing and cleaning  
3. Derived sentiment labels from customer ratings  
4. Converted textual data into numerical features using **TF-IDF Vectorization**  
5. Split the dataset into training and testing sets  
6. Trained a **Logistic Regression** classifier  
7. Evaluated the model using accuracy and classification metrics  
8. Analyzed results and documented observations  

---

## Results
- The sentiment analysis model achieved **good accuracy** on the test dataset  
- **TF-IDF combined with Logistic Regression** proved effective for text classification  
- Dataset size and class imbalance had an impact on overall performance  

---

## 📌 Key Learnings
- Understanding text preprocessing techniques in NLP  
- Importance of feature extraction using **TF-IDF**  
- Applying **Logistic Regression** for sentiment classification  
- Handling real-world datasets without explicit sentiment labels  

---

## 🚀 Conclusion
This task strengthened my understanding of **Natural Language Processing** and improved my ability to preprocess, analyze, and classify textual data using machine learning models.

---
