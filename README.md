# ☀️ Solar Savings Calculator

A **Full-Stack Web Application** that analyzes KSEB electricity bills and recommends solar installations with estimated cost savings.

---

## 🚀 Tech Stack

- **Backend:** Django Ninja (Python FastAPI framework)
- **Frontend:** Nuxt.js (Vue 3)
- **AI:** Gemini AI (Google Generative Model)
- **Hosting:** Vercel (Frontend), any backend hosting (Railway, Fly.io, DigitalOcean)

---

## ✨ Features

✅ Upload or paste KSEB bill text  
✅ AI-powered parsing and recommendation  
✅ Clear cost comparison and estimated savings  
✅ Modern responsive frontend  

---

## 🛠️ Local Development Setup

Follow these steps to run the project locally.

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Mulearn-CETKR/SolarUse
cd SolarUse

---

### 2️⃣ Backend Setup

```bash
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

---

### Create .env
```bash
GEMINI_API_KEY=your_key

---
### Migrate DB
```bash
python manage.py migrate

---

### Run Server
```bash
python manage.py runserver


## Project Structure
SolarUse/
├── backend/
│   ├── manage.py
│   ├── backend/             # Django project config
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── ...
│   └── api/                 # Django Ninja API
│       ├── models.py
│       ├── schemas.py
│       ├── views.py
│       └── utils.py
├── frontend/
│   ├── nuxt.config.ts
│   ├── package.json
│   └── pages/
│       └── index.vue
├── .env
├── README.md
└── requirements.txt
---