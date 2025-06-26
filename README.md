# MediIntel

## 🩺 Abstract

**MediIntel** is an AI-powered healthcare assistant designed to enhance accessibility and efficiency in medicine recognition, tracking, and medical information retrieval. It leverages image recognition, text-to-speech, chatbot integration, and intelligent data parsing to support patients, the elderly, and people with disabilities. The platform simplifies the medication process, promotes adherence, and reduces dependency on manual intervention.

---

## 💡 Motivation

Many individuals—especially the elderly and visually impaired—face challenges in identifying medicines, tracking prescriptions, and understanding medication usage. Manual errors, forgotten doses, and language barriers can have severe consequences. **MediIntel** bridges this gap by providing a smart, inclusive, and easy-to-use healthcare companion.

---

## ❗ Problem Statement

Managing multiple medications, reading prescriptions, or understanding medicine details can be overwhelming—particularly for people with impairments or during emergencies. Most apps require logins and lack accessibility. **MediIntel** addresses this gap with an intelligent assistant that offers medication info, reminders, and real-time interaction without forcing users to register.

---

## ✅ Proposed Solution

**MediIntel** provides:

- 📷 AI-based medicine identification via photo uploads  
- 🔊 Text-to-speech support for visually impaired users  
- 💬 Interactive chatbot with live medical info via web scraping  
- 📆 Medicine reminders based on meal timings  
- 📄 Prescription scanner to extract medicine details  
- 🔓 Optional login for saving reminders and tracking history  

---

## 🎯 Objectives

- Improve access for visually impaired and elderly users  
- Provide accurate, real-time information on medicines  
- Support users in multiple languages  
- Offer reminders for timely medicine intake  
- Allow login-free access while supporting user personalization  

---

## 🛠️ Features

- **Medicine Recognition** – Upload a medicine image to get details like name, usage, side effects, and dosage.  
- **Text-to-Speech** – Audio output for all medicine information.  
- **Multilingual Chatbot** – Fetches live data from medical sources for common questions.  
- **Reminder Tracker** – Schedule medicine alerts (before/after meals).  
- **Prescription Parser** – Extracts and analyzes medicine names from uploaded prescriptions.  
- **Guest Mode** – Skip signup and still use core features; login enables full functionality.  

---

## 🧱 Architecture Diagram

> *(Add your diagram here)*

---

## 🔧 Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Flask (Python)  
- **Database**: Firebase  
- **AI/ML**: TensorFlow, OpenCV, Streamlit, TTS APIs  

---

## 🖼️ Screenshots

> *(Add image paths or links here)*  
- Screenshot1.png  
- Screenshot2.png  
- Screenshot3.png  

---

## ⚠️ Challenges Faced

- Ensuring reliable AI recognition of various medicines  
- Implementing real-time multilingual chatbot scraping  
- Parsing text from prescriptions accurately  
- Designing reminders with user-friendly scheduling  
- Integrating accessibility features for the visually impaired  

---

## 🔭 Future Scope

- Add text-to-speech in multiple languages  
- Convert project into a mobile app  
- Use blockchain to securely store medical data  
- Upgrade chatbot for symptom-based suggestions  
- Integrate with smartwatches and wearables  

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/Pavithrars2004/MediIntel.git
cd MediIntel

# Set up environment
python3 -m venv venv
source venv/bin/activate

# Install Python dependencies
pip install -r requirements.txt

# (If using Node frontend)
# npm install
# npm start

# Run the Flask backend
python app.py
```

---
