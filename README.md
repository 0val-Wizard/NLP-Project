# NLP-Project
Natural Language Processing (NLP) is Year 2 module in TP. It introduces students to the concepts &amp; application of nlp. It covers the standard NLP workflow through various aspects such as text scraping, text wrangling and pre-processing, etc. using available libraries. Also, exploring applications of NLP to chatbot development.

### NLP Projects:
#### 1) NLP Rag + Rasa Chatbot
#### 2) NLP Pipeline

## 1) NLP Rag + Rasa Chatbot

### - Conversation Workflow

  - Cancel Order
    
    <img width="613" height="185" alt="image" src="https://github.com/user-attachments/assets/d2b1704a-e4aa-44fe-badd-7bb8dea16684" />

  - Create Account
    
    <img width="551" height="173" alt="image" src="https://github.com/user-attachments/assets/36068b98-67d8-4b0f-abe6-f604f98add3e" />

  - Handle Complaint
    
    <img width="613" height="157" alt="image" src="https://github.com/user-attachments/assets/b476db0c-f610-487a-8633-a0ba9fd5ec5d" />
 
  - Change Order
    
    <img width="613" height="169" alt="image" src="https://github.com/user-attachments/assets/e12197ca-2a94-40bf-823c-e4ee2b4c5c84" />
 
  - Change Shipping Address
    
    <img width="471" height="176" alt="image" src="https://github.com/user-attachments/assets/c4c38ac1-2cb3-43db-a2f0-89992949fe50" />

  - Track Order
    
    <img width="612" height="151" alt="image" src="https://github.com/user-attachments/assets/87496301-c06a-44fe-9463-7697a7c4bd9e" />

  - Track Refund
    
    <img width="669" height="151" alt="image" src="https://github.com/user-attachments/assets/076e3b65-83d2-4013-a428-dfe92d47835a" />
 
  - Check Invoices
    
    <img width="612" height="208" alt="image" src="https://github.com/user-attachments/assets/492801ee-7d1a-484e-846d-9ffd6ed00377" />

  - Order Management
    
    <img width="612" height="128" alt="image" src="https://github.com/user-attachments/assets/0f8622ad-ea4c-42a6-9b77-c13403e84cfb" />
 
  - Refund Policy
    
    <img width="916" height="106" alt="image" src="https://github.com/user-attachments/assets/4a25c912-63d8-4a48-bbc0-2353a56da004" />
 
  - Complaint Handling
    
    <img width="688" height="156" alt="image" src="https://github.com/user-attachments/assets/e059703a-3905-4f7e-9b2f-22a60bdc4b66" />
 
  - Shipping Information
    
    <img width="904" height="105" alt="image" src="https://github.com/user-attachments/assets/484ed4b1-96e4-498d-8612-9cc6d9e65276" />

--------------------------------------
## 2) NLP Pipeline

### 1. Data Loading & Preprocessing
  - Two CSV files are loaded using Pandas.
  - They are merged on a common column (outer join) to create a combined dataset.
  - The merged dataset is saved as combined.csv.

### 2. Typical NLP Pipeline Components (based on notebook patterns)
  - Although only part of the notebook was fully extracted, a standard Part 1 NLP pipeline usually includes:
  - Text Cleaning – lowercasing, removing punctuation, stopword filtering.
  - Vectorization – CountVectorizer / TfidfVectorizer to convert text into numerical features.
  - Train/Test Split – split dataset into training and testing subsets.
  - Model Training – fit baseline models (e.g., Logistic Regression, Naive Bayes, SVM).
  - Evaluation – accuracy, precision, recall, F1-score.
  - Pipeline Packaging – Scikit-learn Pipeline objects for reproducibility.
 
