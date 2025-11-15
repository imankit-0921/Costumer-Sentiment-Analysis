# 🧠 Customer Sentiment Analysis – NLP & Machine Learning

Customer sentiment analysis (opinion mining) is an NLP technique used to determine whether textual feedback expresses **positive**, **negative**, or **neutral** emotion.  
This project analyzes large-scale customer complaint transcripts (voice, chat, email) to understand how customers feel about different companies.

It includes **NLP preprocessing, ML models, EDA, visualizations, and dashboards**.

---

## 📌 Project Overview

- Applied **Natural Language Processing (NLP)** techniques to clean and prepare customer transcripts.
- Performed **Exploratory Data Analysis (EDA)** to uncover sentiment patterns across products, companies, and issues.
- Built and evaluated multiple ML models:
  - **Naive Bayes**
  - **Decision Tree**
  - **K-Nearest Neighbors (KNN)**
- Achieved **~79% accuracy** with KNN after scaling and sampling.
- Created **visualizations and an interactive Tableau dashboard**.
- Extracted key insights about customer pain points, dispute reasons, and company-wise sentiment distribution.

---

## 📂 Dataset Description

The dataset contains customer complaints submitted across various channels.  
Key attributes include:

- `date_received`
- `product`
- `sub_product`
- `issue`
- `company`
- `state`, `zipcode`
- `consumer_complaint_narrative`
- `company_response_to_consumer`
- `submitted_via`
- `consumer_disputed?`
- `complaint_id`

The dataset contains **over 500K+ rows**, making it ideal for real-world NLP analysis.

---

## 🎯 Problem Statement

To analyze customer transcripts and:

1. Detect sentiment expressed toward different companies.
2. Identify dominant issues causing negative sentiment.
3. Build a model that automatically predicts customer sentiment.
4. Visualize insights to help companies improve customer satisfaction.

---

## 🎯 Project Objectives

- Use NLP techniques to label customer sentiment.
- Classify sentiment into **Positive**, **Negative**, or **Neutral**.
- Build ML models for automated sentiment prediction.
- Perform EDA to extract trends, patterns, and correlations.
- Create interactive visualizations and dashboards for insights.

---

## 🔧 Methodology

### **1. Data Collection**
Collected transcripts from:
- Voice calls  
- Emails  
- Chat messages  

### **2. Data Cleaning**
- Handled missing values  
- Cleaned text fields  
- Removed punctuation, special characters, stopwords  
- Performed lemmatization and tokenization  

### **3. NLP Preprocessing**
Converted text to features using:
- **Bag-of-Words (BoW)**
- **TF-IDF Vectorization**

Encoded categorical variables with Label Encoding.

### **4. Sentiment Classification Models**
Built and tested:
- **Multinomial Naive Bayes**
- **Decision Tree Classifier**
- **K-Nearest Neighbors (KNN)**

➡️ **Best accuracy: ~79% (KNN)** with feature scaling.

### **5. Exploratory Data Analysis (EDA)**
Identified:
- Most frequent complaint issues  
- Company-wise sentiment distribution  
- Trends over time  
- States with most disputes  
- Repeating negative issue categories  

### **6. Visualizations & Dashboard**
Created using **Matplotlib**, **Seaborn**, and **Tableau**:
- Sentiment distribution  
- Issue heatmaps  
- Company-wise comparisons  
- Complaint trends  
- Dispute patterns  

### **7. Insight Extraction**
- Highlighted recurring pain points across companies  
- Found issues triggering maximum disputes  
- Mapped companies with highest negative sentiment  
- Identified patterns based on geography, product, and time  

### **8. Recommendations**
Based on findings:
- Improve response speed for recurring negative categories  
- Invest in automation for common complaint resolution  
- Increase transparency in billing, credit reporting, and loan servicing  
- Strengthen multi-channel support systems  

---

## 📊 Sample Visualizations

### Sentiment Distribution  
![Sentiment Chart]([https://github.com/imankit-0921/Costumer-Sentiment-Analysis/blob/main/cloud.png))

### Negative Issue Categories  
![Issue Chart](https://github.com/imankit-0921/Costumer-Sentiment-Analysis/blob/main/output.png)

### Company-Wise Sentiment Comparison  
![Company Chart](https://github.com/imankit-0921/Costumer-Sentiment-Analysis/blob/main/image.png)

---

## 🛠️ Tools & Technologies

| Category | Tools Used |
|---------|------------|
| **Languages** | Python |
| **Libraries** | Pandas, NumPy, Scikit-Learn, NLTK, Matplotlib, Seaborn |
| **Dashboards** | Tableau |
| **Techniques** | NLP, TF-IDF, Text Preprocessing, Classification ML Models |

---

## 🚀 Future Enhancements

- Build a deep learning model using **LSTM**, **GRU**, or **BERT**.
- Deploy a **real-time sentiment analysis web app** using Streamlit.
- Perform topic modeling (LDA) to uncover hidden complaint themes.
- Add Named Entity Recognition (NER) to extract company/product mentions.
- Build a multiclass emotion classifier (anger, joy, frustration, etc.).

---

## 👤 Author

**Ankit Kumar Upadhyay**  
Data Science • NLP • Machine Learning  

- GitHub: https://github.com/imankit-0921  
- LinkedIn: https://www.linkedin.com/in/ankit-upadhyay-9734a424b  

---

## 📬 Support  
If you have suggestions, issues, or improvements, feel free to open an **Issue** in this repository.

---
