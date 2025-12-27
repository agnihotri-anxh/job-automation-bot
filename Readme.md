# 🤖 Automated Job Data Pipeline using n8n

This project is a fully automated **Job Data Management System** built using **n8n**.  
It fetches real job listings from public APIs, processes & cleans the data, stores it in a database, and publishes it to Notion — automatically and continuously.

---
<img width="1365" height="493" alt="Screenshot 2025-12-26 231152" src="https://github.com/user-attachments/assets/0ed0cdcb-ba98-4025-aee1-9df9ff67c346" />

## 🚀 What This Automation Does

### ✅ End-to-End Workflow
1️⃣ Fetches latest job listings from **Remotive API / public job APIs**  
2️⃣ Cleans & transforms data (title, company, category, location, salary, date, link, etc.)  
3️⃣ Stores structured records in **PostgreSQL (Neon DB)**  
4️⃣ Sends final cleaned jobs to **Notion Database**  
5️⃣ Runs automatically on schedule (no manual work needed)

---

## 🏗️ Tech Stack

| Component | Tool |
|---------|------|
Automation Engine | n8n
Job Source API | Remotive API
Database | PostgreSQL (NeonDB)
Knowledge Base / UI | Notion
Cloud Deployment | Render / n8n Cloud

---

## 🔥 Architecture

```
API → n8n → Data Cleaning → PostgreSQL → Notion Dashboard
```

This makes it:
✔ scalable  
✔ automated  
✔ resume-worthy  
✔ real-world applicable  

---

## 📌 Features

- Automated job scraping
- Real-time data pipeline
- Database persistence
- Centralized Notion Job Dashboard
- No coding required in pipeline
- Cloud hosted
- Production ready design

---

## 🖥️ Demo / Outputs

### 📄 Live Notion Dashboard
🔗 [<your-notion-public-link>](https://www.notion.so/2d593c5e83b4807e93b6d28dcb3dfb0f?v=2d593c5e83b480c6a584000cf3d04e19&source=copy_link)
---

## ⚙️ How It Works (Internals)

### n8n Workflow Steps
- HTTP Node → Fetch Jobs
- Function / Set Node → Clean + Structure
- PostgreSQL Node → Insert into DB
- Notion Node → Create page entry
- Cron Node → Schedule automation

---

## 🧪 Execution & Reliability
- Tested with multiple runs
- Handles empty responses
- Avoids duplicate breaking
- Follows API limits



## 🎯 Use Cases

- Job Aggregator Tool
- Career Recommendation System
- Automation Portfolio Project
- Data Engineering Practice
- No-Code Backend Demo


Give it a ⭐ on GitHub!

