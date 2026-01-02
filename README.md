# -GDG-on-Campus---TechSprint
# 📢 Campus Voice: AI-Powered Student Feedback

![Status](https://img.shields.io/badge/Status-Live-green)
![Tech](https://img.shields.io/badge/Built%20With-Google%20Gemini%20%2B%20Firebase-blue)

**Campus Voice** is an anonymous, AI-driven feedback portal designed to bridge the gap between students and administration. By leveraging **Google Gemini AI**, it instantly analyzes student complaints, detects sentiment, and provides actionable insights via a real-time dashboard.

🔗 **Live Demo:** [https://studentfeedback-mbu.web.app](https://studentfeedback-mbu.web.app)

---

## 🚀 The Problem
* **Lack of Privacy:** Students fear retaliation when reporting issues via traditional channels.
* **Data Overload:** Administrators are overwhelmed by unstructured text complaints and cannot identify critical trends quickly.
* **Delayed Action:** Manual reading of feedback slows down resolution times for urgent issues like infrastructure or hygiene.

## 💡 The Solution
We built a **Zero-Touch Feedback Loop**:
1.  **Anonymous Submission:** Students log in anonymously using Firebase Auth.
2.  **AI Analysis:** **Google Gemini 1.5 Flash** reads every message to determine sentiment (Positive/Negative) and generates a 4-word summary.
3.  **Real-Time Visualization:** Administrators see a live dashboard powered by **Google Charts**, highlighting "Hot Topics" (e.g., Canteen issues) instantly.

---

## ✨ Key Features
* **🔒 Secure Anonymity:** Uses `firebase.auth().signInAnonymously()` to protect student identity.
* **🤖 AI Sentiment Engine:** Automatically tags feedback as *Positive*, *Negative*, or *Neutral*.
* **📝 Smart Summarization:** Compresses long rants into concise, actionable summaries (e.g., "Cold Food in Canteen").
* **📊 Admin Dashboard:** Visualizes campus mood with dynamic Pie Charts.
* **☁️ Cloud Native:** Fully hosted on Firebase (Firestore + Hosting) for global access.

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, JavaScript (ES6)
* **Backend:** Google Firebase (Serverless)
* **AI Model:** Google Gemini API (`gemini-1.5-flash`)
* **Database:** Cloud Firestore (NoSQL)
* **Visualization:** Google Charts

---

## 📸 Screenshots

### 1. Student View (AI Analysis)
*(Upload your screenshot here)*

### 2. Admin Dashboard (Analytics)
*(Upload your screenshot here)*

---

## ⚙️ How to Run Locally

1. **Clone the Repo**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Campus-Voice-AI.git](https://github.com/YOUR_USERNAME/Campus-Voice-AI.git)
