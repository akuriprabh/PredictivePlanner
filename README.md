# PredictivePlanner – AI-Powered Project Estimation Tool

GitHub: https://github.com/akuriprabh/PredictivePlanner  
Live Demo: Coming soon on Render (free tier)

[![PredictivePlanner](https://img.shields.io/badge/status-actively%20developing-brightgreen)]()
[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org)
[![Django](https://img.shields.io/badge/Django-5.0-green)](https://www.djangoproject.com)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o-black)](https://openai.com)

## What It Does
Just paste a plain-English project description → get a complete, client-ready estimate in seconds:

- Task breakdown with effort hours  
- Timeline & milestones  
- Budget calculation  
- Risk identification  
- Resource recommendations  
- One-click branded PDF report (download & send)

All powered by OpenAI GPT-4o + advanced prompt engineering, I learned directly from OpenAI’s official course.

## Key Features
- User registration & secure authentication (Django Allauth)  
- Save unlimited projects with full history  
- Instant AI-generated structured estimates  
- Beautiful real-time dashboard  
- Professional PDF report generation (ready for clients)  
- Fully responsive with Tailwind CSS  
- Clean, production-ready code

## Tech Stack
- Backend: Python + Django 5  
- AI: OpenAI GPT-4o API + advanced prompt engineering  
- Frontend: Tailwind CSS, HTML, JavaScript  
- Database: SQLite (easy switch to PostgreSQL)  
- Authentication: Django Allauth  
- Ready for Docker & cloud deployment

## Why I Built This
After 4+ years automating systems at Discover Financial Services and HCL (100+ production scripts, Azure automation, CI/CD), I kept seeing the same pain: project estimates took hours/days and were inconsistent.  
PredictivePlanner fixes that using the same GPT models behind ChatGPT, but with carefully engineered prompts to produce reliable, professional output every time.

## Screenshots 
<img width="1902" height="1113" alt="image" src="https://github.com/user-attachments/assets/3512d704-2f4c-457d-88a9-b1df6bb748ab" />
<img width="1872" height="1107" alt="image" src="https://github.com/user-attachments/assets/9cf76682-d452-4744-9df9-b0ca59d801e3" /> 
<img width="1893" height="1107" alt="image" src="https://github.com/user-attachments/assets/28ccf301-b743-4b49-b988-83d1d3b5c38d" /> 


## How to Run Locally
```bash
git clone https://github.com/akuriprabh/PredictivePlanner.git
cd PredictivePlanner
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
