---
layout: archive
title: "Projects"
permalink: /Projects/
author_profile: true
---

{% include base_path %}

---

### 🎯 Customer Segmentation & Retention Analysis
**Technologies:** Python, EDA, Scikit-learn, XGBoost, ANN, AWS, Docker, GitHub Actions, CI/CD

Developed an end-to-end Customer Segmentation & Retention system using **RFM (Recency, Frequency, Monetary)** and **Customer Lifetime Value (CLV)** modeling to identify high-value, loyal, and at-risk customers.

**Key Highlights:**
- Performed in-depth **exploratory data analysis (EDA)** on a dataset of 50k records to understand customer behavior patterns, data quality issues, and feature distributions prior to modeling.
- Built modular, configuration-driven components for data ingestion, validation, transformation, and model training using **XGBoost, Random Forest, and Artificial Neural Networks (ANN)**, achieving up to **87% accuracy** and **AUC of 0.92**.
- Automated ingestion of semi-structured customer data from **MongoDB Atlas**, converting it into clean, analysis-ready datasets with logging and exception handling, reducing manual data prep time by **40%**.
- Managed model evaluation, versioning, and storage on **AWS S3**, and deployed the containerized application using **Docker** with **CI/CD via GitHub Actions** to AWS ECR and EC2.

👉 [Click here to explore more...](https://github.com/kaveti27022001/Customer_churn_prediction)

---

### 🤖 Legal AI Chatbot
**Technologies:** RAG, Ollama, OpenAI APIs, LLM Optimization, ChromaDB, Streamlit, AWS, CI/CD

Built a Legal Chatbot to support individuals with disabilities, delivering legal guidance across **health, education, and employment** domains.

**Key Highlights:**
- Created a **ChromaDB vector store** from 500+ files via semantic chunking and retrieved data using on-device **Llama 3.2**.
- Achieved a **precision of 0.86** and reduced hallucinations by **60%** via Fine-Tuning and Prompt Engineering.
- Integrated **Streamlit UI**, implemented **CI/CD**, and scaled the system for **100 queries/sec** by deploying it on **AWS**.

👉 [Click here to explore more...](https://github.com/kaveti27022001/Legal_aid_Chatbot)

---

### 🏆 Fraud Detection System — *HackUNT Winner*
**Technologies:** Python, Pandas, Scikit-learn, Logistic Regression, Model Optimization, Streamlit, Docker

Built an award-winning fraud detection system that **won HackUNT** hackathon, analyzing over **6 million transaction records** to identify fraudulent activities in real-time.

**Key Highlights:**
- Implemented a fraud detection system by performing in-depth **EDA** on a dataset of over **6 million transaction records**.
- Applied statistical techniques to engineer features and addressed **class imbalance** using weighted models.
- Achieved a **true-positive-rate of 0.95** by training a logistic regression model using a **Scikit-learn pipeline**.
- Dockerized and deployed a **Streamlit app** for real-time fraud prediction, detecting **~500 fraudulent transactions**.

👉 [Click here to explore more...](https://github.com/kaveti27022001/Fraud-Catcher.ML) | 🏅 [View on Devpost](https://devpost.com/software/fraudcatcher-ml)

---

<!-- You can also display portfolio items automatically -->
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
