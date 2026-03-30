=======
# 🏥 Personalized Doctor AI Agent

An AI-powered medical consultation system that predicts the appropriate medical department based on symptoms and evaluates patient risk using machine learning models.

---

## 🚀 Overview

This project simulates a smart medical assistant that helps users:

- Identify the relevant medical department  
- Assess risk severity (0–100 score)  
- Provide real-time AI-based guidance  
- Assist in emergency decision-making  

---

## 🧠 Features

- Symptom-based department prediction  
- Risk scoring with severity classification  
- Real-time consultation interface using Streamlit  
- AI chatbot for personalized medical guidance  
- Emergency rule-based overrides for critical cases  

---

## 🏗️ Tech Stack

- **Programming Language:** Python  
- **Frontend/UI:** Streamlit  
- **Machine Learning:** Scikit-learn  
- **Data Handling:** Pandas  
- **AI Integration:** LangChain, OpenAI API  

---

## 🤖 Machine Learning Models Used

- Logistic Regression (LR)  
- Random Forest (RF)  
- Gradient Boosting (GB)  
- Support Vector Regressor (SVR)  
- K-Nearest Neighbors (KNN)  

---

## 📊 Risk Score System

- Generates a risk score from **0 to 100**  
- Categorizes patients into:
  - 🟢 Low Risk  
  - 🟡 Medium Risk  
  - 🔴 High Risk  

---

## 🖥️ Application Interface

Built using **Streamlit**, providing:

- Structured symptom input  
- Instant predictions  
- Dynamic AI responses  
- User-friendly dashboard  

---

## ⚙️ How It Works

1. User inputs symptoms  
2. ML models process the input  
3. System predicts:
   - Medical department  
   - Risk score  
4. AI agent provides guidance and alerts  

---

## 📦 Installation

```bash
git clone https://github.com/your-username/personalized-doctor-ai-agent.git
cd personalized-doctor-ai-agent
pip install -r requirements.txt
streamlit run app.py

