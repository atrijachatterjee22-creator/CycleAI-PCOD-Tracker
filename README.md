# 🩺 CycleAI — Smart Period Tracking & PCOD Risk Prediction System

> **Elite Her Hackathon 2025** submission by **Atrija Chatterjee & Aishwariya Dhage **

---

## 🔴 The Problem

- **1 in 5** women worldwide suffer from PCOD (Polycystic Ovary Disease)
- **70% remain undiagnosed** — often for years
- Existing apps like Flo and Clue **fail women with irregular cycles**
- No affordable, accessible tool combines cycle tracking + PCOD early detection

---

## 💡 Our Solution — CycleAI

A personalized health insights platform that uses **Machine Learning** to:
- Track cycle data even when cycles are **highly irregular**
- **Predict the next cycle** using LSTM + ARIMA models
- Generate an automatic **PCOD Risk Score**
- Provide **personalized health insights** — not generic tips
- Offer a **24/7 AI health chatbot** for guidance

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 📅 Cycle Tracking | Log start date, symptoms, mood, flow intensity |
| 🤖 ML Irregular Analysis | Model learns your unique pattern, flags anomalies |
| 🔮 Smart Predictions | Predicts next cycle even with skipped/irregular cycles |
| ⚠️ PCOD Risk Score | Detects indicators: long gaps, acne, skipped cycles |
| 📊 Visual Insights | Trend graphs, symptom frequency charts |
| 💬 AI Health Chatbot | 24/7 guidance on PCOD, symptoms, nutrition |
| 📄 Doctor Report Export | One-tap PDF export of full health history |
| 🔒 Privacy First | Encrypted data, offline mode, no data selling |

---

## 🆚 How Are We Different?

| Feature | Flo / Clue | PCOD Clinic Apps | **CycleAI** |
|---------|-----------|-----------------|------------|
| Irregular cycle support | ❌ Assumes regular | ❌ Not tracked | ✅ ML-trained |
| PCOD risk score | ❌ None | ⚠️ Manual only | ✅ Automatic |
| Predict skipped cycles | ❌ No | ❌ No | ✅ Yes |
| AI Chatbot | ❌ None | ❌ None | ✅ 24/7 |
| Offline + free | ❌ Cloud only | ⚠️ Paid | ✅ Yes |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React Native / Flutter |
| Backend | Python (FastAPI) |
| ML Engine | Scikit-learn, LSTM (TensorFlow), ARIMA |
| Database | MongoDB (encrypted) |
| AI Chatbot | Anthropic Claude API |
| Deployment | Netlify (prototype), AWS (production) |

---

## 🏗️ Architecture

```
User Input → Validation → ML Engine → Risk Score → Insight Generation → Dashboard
                              ↓
                    LSTM (cycle prediction)
                    PCOD Risk Classifier
                    Symptom Pattern Analyzer
```

---

## 🚀 Live Demo

🔗 **[Click here to try the interactive prototype](YOUR_NETLIFY_LINK_HERE)**

---

## 📁 Project Structure

```
CycleAI/
├── index.html          ← Interactive prototype (all 6 screens)
├── README.md           ← This file
├── /src
│   ├── /frontend       ← React Native app screens
│   ├── /backend        ← Python FastAPI server
│   ├── /ml             ← ML models (LSTM, ARIMA, PCOD classifier)
│   └── /data           ← Sample data for training
```

---

## 👩‍💻 Team

| Name | Role |
|------|------|
| [Your Name] | Frontend & UI/UX Design |
| Aishwariya | ML & Backend Development |

> First year students · Passionate about women's health technology

---

## 📊 Expected Impact

- **70% earlier** PCOD detection vs current average
- **85% accuracy** target for irregular cycle prediction
- **200M+** potential users in India (women aged 13–45)
- Bridges the healthcare gap for **rural women** with limited gynaecologist access

---

## 📄 License

MIT License — Free to use and build upon.

---

*"Because every woman deserves to understand her own body." 💜*
