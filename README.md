# 🌐 FullStackDeployLab: Django + React Practice Project

> My personal sandbox for mastering full-stack architecture, integration, and deployment workflows with Django REST Framework and React.

This project is a complete full-stack setup designed to help myself **practice**, **debug**, and **deploy** modern backend and frontend services separately. From JWT authentication to Render deployment, this lab is my way of building confidence using real-world development stacks.

---

## 🛠️ Tech Stack

### Backend

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Django](https://img.shields.io/badge/Django-4.x-green?logo=django)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?&logo=postgresql&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-18-blue?logo=react)

### Deployment

![Render](https://img.shields.io/badge/Backend-Render-brightgreen?logo=render)
![Supabase](https://img.shields.io/badge/Database-Supabase-3ecf8e?logo=supabase&logoColor=white)

---

## Project Purpose

This project isn’t about features — it’s about mastering:
-  API-frontend integration
-  CORS and JWT flow
-  PostgreSQL database hosting with Supabase
-  Separate deployment pipelines for Django + React
-  Secure environment variable management

---

## ⚙️ Local Setup

```bash
cd backend
python -m venv env
source env/bin/activate  # Windows: .\env\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
