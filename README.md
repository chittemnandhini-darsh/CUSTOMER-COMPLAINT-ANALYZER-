# CUSTOMER-COMPLAINT-ANALYZER-

## 📌 Project Overview

Customer Complaint Analyzer is an AI-powered application that analyzes customer complaints using **Natural Language Processing (NLP)**. The system identifies the complaint category, sentiment, priority level, important keywords, and provides a recommended action for customer support teams.

The application is developed using **Python, Transformers, PyTorch, and Gradio** and can be easily run in **Google Colab**.



## 🎯 Objectives

* Analyze customer complaints automatically.
* Identify the type of complaint.
* Detect customer sentiment.
* Determine complaint priority.
* Extract important keywords.
* Recommend suitable customer support actions.
* Reduce manual complaint analysis.

---

## ✨ Features

* 📝 Customer complaint input
* 🤖 AI-based sentiment analysis
* 📂 Automatic complaint categorization
* 🚨 Priority detection
* 🔑 Keyword identification
* 💡 Recommended action
* 🌐 Interactive web application
* ☁️ Runs easily in Google Colab
* 🔗 Shareable Gradio application link

---

## 🏗️ System Workflow

```text
Customer Complaint
        ↓
Text Input
        ↓
NLP Processing
        ↓
┌───────────────┐
│ Complaint     │
│ Classification│
└───────┬───────┘
        ↓
Sentiment Analysis
        ↓
Priority Detection
        ↓
Keyword Extraction
        ↓
Recommended Action
        ↓
Analysis Result
```

---

## 📂 Complaint Categories

The application can identify categories such as:

* Delivery
* Payment
* Product
* Technical
* Customer Service
* General Complaint

---

## 🚨 Priority Levels

| Priority | Description                            |
| -------- | -------------------------------------- |
| High     | Serious or urgent complaints           |
| Medium   | Complaints requiring support attention |
| Low      | Normal customer issues                 |

---

## 🧠 Technologies Used

| Technology   | Purpose                    |
| ------------ | -------------------------- |
| Python       | Application development    |
| NLP          | Text analysis              |
| Transformers | AI/NLP model               |
| DistilBERT   | Sentiment analysis         |
| PyTorch      | Machine learning framework |
| Gradio       | Web application interface  |
| Google Colab | Development environment    |

---

## 📋 Example

### Input

text
My order arrived very late and the product was damaged.


<img width="922" height="296" alt="Screenshot 2026-09-22 202515" src="https://github.com/user-attachments/assets/362f6542-51ec-4904-981d-103e9e952b79" />



<img width="914" height="384" alt="Screenshot 2026-09-22 202551" src="https://github.com/user-attachments/assets/626378bc-2f7d-4cb4-9659-ea1e7a30483e" />




### Output

```text
Category: Delivery

Sentiment: Negative

Priority: Medium

Keywords:
delivery, late, damaged, product, order

Recommended Action:
Assign the complaint to the appropriate
support department.











