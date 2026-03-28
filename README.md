# 🤖 AI Job Application Agent

An automated AI-powered system that finds relevant jobs, evaluates them, and generates personalized applications.

---

## 🚀 Features

* 🔍 Fetches jobs from APIs (Remotive)
* 🧠 AI-based job filtering (match score + decision)
* ✍️ Generates personalized cover letters
* 📊 Stores results in Google Sheets
* 📲 Sends real-time alerts via Telegram
* 🧠 Skill Gap Detection (suggests what to learn)

---

## ⚙️ Tech Stack

* n8n (workflow automation)
* OpenAI API
* Google Sheets API
* Telegram Bot API

---

## 🔁 Workflow

1. Fetch jobs from API
2. Loop through jobs
3. Clean data
4. AI evaluates job
5. IF:

   * ✅ Good → Cover Letter + Store + Notify
   * ❌ Bad → Skill Gap Detection

---

## 📸 Workflow image

<img width="1711" height="897" alt="image" src="https://github.com/user-attachments/assets/07f232e5-b1a3-4731-8b2e-7886da1a95da" />

---

## 💡 Future Improvements

* Auto-apply to jobs
* Multi-source job aggregation
* Smart ranking system

---

## 🧠 Learnings

* Built real-world AI pipelines
* Prompt engineering for decision-making
* API integrations and automation
