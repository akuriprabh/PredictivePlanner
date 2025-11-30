# PredictivePlanner – AI-Powered Project Estimation Tool

https://github.com/akuriprabh/PredictivePlanner

Live Demo → Coming this week (free Render free tier)  
Ask me for early access: prabhudeva.akuri7@gmail.com

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org)
[![Django](https://img.shields.io/badge/Django-5.0-green)](https://www.djangoproject.com)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o-black)](https://openai.com)

## What It Does
You type a normal project description in English → in 5 seconds you get a full professional estimate:

- Task breakdown with hours
- Timeline & milestones
- Budget estimate
- Risk analysis
- Resource plan
- Beautiful downloadable PDF report (ready to send to clients)

Powered 100% by OpenAI GPT-4o + advanced prompt engineering (official OpenAI course)

## Features
- User login/registration
- Save all your projects
- Instant AI estimation
- Real-time dashboard
- One-click branded PDF report
- Fully responsive (mobile + desktop)
- Clean production-ready code

## Tech Stack
- Python + Django 5
- OpenAI GPT-4o API
- Tailwind CSS
- SQLite (easy to change to PostgreSQL)
- Docker-ready

## Why I Built This
After 4+ years writing automation at Discover Financial Services and HCL Technologies, I saw the same problem again and again: project estimates take hours and are inaccurate.  
PredictivePlanner solves it instantly using the same AI that powers ChatGPT — but with professional-grade prompts.

## Screenshots 
<img width="1875" height="1111" alt="image" src="https://github.com/user-attachments/assets/91bb2c65-8a62-469b-941a-ba17a6d70adc" /> <img width="1872" height="1107" alt="image" src="https://github.com/user-attachments/assets/9cf76682-d452-4744-9df9-b0ca59d801e3" /> <img width="1893" height="1107" alt="image" src="https://github.com/user-attachments/assets/28ccf301-b743-4b49-b988-83d1d3b5c38d" /> 




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
