---
title: Ai Medical Chatbot
emoji: 🚀
colorFrom: red
colorTo: red
sdk: docker
app_port: 7860
tags:
- streamlit
pinned: false
short_description: 'AI medical diagnostic chatbot will diagnosis the symptoms '
license: mit
---
# Overview 
This project was done during my Viswam.ai Internship as an AI Intern Developer , this project was done as a TEAM (AI MEDIVISION)  
Member 1: [manibyra] – Frontend & user Growth
Member 2: [gorileshailaja] – AI Integration & Documentation
Member 3: [pooja25] – Testing & Optimization
Member 4: [akhilbudige] – Streamlit Integration & Community Engagement
Member 5: [nayan_2069] – Backend & Optimization

# 🧠 AI Medical Diagnostic Chatbot

This is a Flask-based AI-powered Medical Diagnostic Chatbot that dynamically interacts with users, gathers symptom details, and suggests possible conditions based on a rule-based symptom matching system.
To experience click this link :
https://huggingface.co/spaces/Shailajagorile/AI-Medical-Diagnosis-Assistant

## 🚀 Features

- 🧾 Multi-turn symptom collection and questioning
- 🤖 Dynamic question generation
- ✅ Smart condition detection (Suspected / Possible)
- 📁 Session tracking and input logging
- 🗣️ Voice input support (planned)
- 🧑‍⚕️ Suggested condition with basic medicine/doctors (planned)
- 🎨 User-friendly frontend

## 🛠️ Technologies Used

- Python 3.12+
- Flask
- HTML/CSS/JavaScript
- JSON (for condition and question rules)
- Hugging Face Spaces (deployment)

## 📂 Project Structure

```plaintext
├── app.py                 # Main Flask application
├── templates/
│   └── index.html         # Chat frontend
├── static/
│   ├── css/
│   └── js/
├── data/
│   └── conditions.json    # Symptom-condition mapping
├── logs/
│   └── user_logs.csv      # Logs of each user interaction
├── requirements.txt
├── Dockerfile
├── .huggingface.yml
├── README.md
├── REPORT.md
├── CONTRIBUTING.md
├── CHANGELOG.md
└── LICENSE

Diagnosis Rules:
✅ If a condition gets 3 “yes” responses from the user → immediately confirm diagnosis and stop.
❗ If a condition gets 2 “yes” responses and no other conditions have that many → suspect that condition and show it.
⚠️ If no condition has 2 or more “yes” → show a fallback message like “No clear diagnosis found, consult a doctor.”

📦 Deployment
Deployed on Hugging Face Spaces using Docker and .huggingface.yml.

# Feedback
https://docs.google.com/spreadsheets/d/15oDv5QK3g_YceaVuPrrtPSVuJW07ZQVRPpzMj2PXnvk/edit?usp=sharing

📃 License
This project is licensed under the MIT License. See LICENSE for more information.
