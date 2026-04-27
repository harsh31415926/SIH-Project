  # 🎓 Student Dropout Risk Prediction System

An AI-powered early warning system designed to predict student dropout risk using a combination of psychological, academic, and environmental factors.

## 🚀 Overview
Traditional dropout prediction models rely heavily on academic performance such as marks and attendance. However, student dropout is often driven by deeper behavioural and psychological factors.

This project introduces a hybrid approach where:
- 🧠 Psychological factors are treated as primary signals
- 📊 Academic performance acts as supporting evidence
- 🌍 Environmental conditions provide contextual insights

The system predicts dropout risk at an early stage, enabling proactive intervention.

## 🧩 Key Features
- 🔍 **Psychology-first modeling** (stress, motivation, family support, bullying, etc.)
- 📈 **Trajectory-based features** (slope, momentum, % change, deviation)
- 📊 **Risk scoring system** with probabilistic output
- 🤖 **Machine Learning models** (XGBoost / ensemble approach)
- 🧠 **Explainable AI** using feature importance and insights
- 📋 **Survey-based data collection** for behavioural analysis
- 🌐 **Real-world factors integration** (distance, language barrier, financial stress)

## 🏗️ Model Architecture
- Psychological Model (Primary)
- Combined Model (Psychological + Academic + Environmental)
- Final Risk Score = Weighted Ensemble Output

## 📊 Evaluation Metrics
- ROC-AUC
- Precision & Recall
- Confusion Matrix
- Precision@Top-K (high-risk detection)

## 🎯 Use Case
- Schools, colleges, and coaching institutes
- Early identification of at-risk students
- Supporting educators with actionable insights

## 💡 Innovation
Unlike traditional systems, this project focuses on **early behavioural signals**, allowing institutions to identify and support students *before academic failure occurs*.

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- XGBoost / Scikit-learn
- Matplotlib / Seaborn
- (Optional) Streamlit / Dashboard UI

## 📌 Future Scope
- Integration with real-time student data systems
- Personalized intervention recommendations (RAG-based)
- Deployment as a scalable institutional dashboard

---

> Built for Smart India Hackathon (SIH) 🚀
