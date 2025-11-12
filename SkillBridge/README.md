# SkillBridge Project

> **Connecting skills with opportunities — empowering inclusive employment through data and AI.**

---

## Overview

**SkillBridge Project** is a Django-based system that analyzes and connects individual skills to the labor market by identifying structural patterns that limit employment inclusion for people in vulnerable situations.  
The project leverages data analytics and machine learning to **understand why capable individuals are excluded** and **recommend better job matches** based on proven skills.

---

## Objectives

- **Analyze** socioeconomic and structural patterns that influence employability.  
- **Identify** barriers to inclusion despite existing skills.  
- **Connect** individuals with matching job opportunities using algorithmic recommendations.  
- **Visualize** the causes and outcomes of exclusion in an interactive dashboard.

---

## Tech Stack

-----------------------------------------------------------------------
| Category        | Technologies                                      |
|-----------------|---------------------------------------------------|
| **Backend**     | Python 3.14, Django 5.2.8, Django REST Framework  |
| **Database**    | SQLite (dev), PostgreSQL (prod)                   |
| **ML / Data**   | pandas, numpy, scikit-learn, spaCy, matplotlib    |
| **Environment** | python-dotenv                                     |
| **Tools**       | VS Code, Git, Docker (optional), Black, isort     |
-----------------------------------------------------------------------

---

## Project Structure


SkillBridge/
    |-- manage.py
    |-- requirements.txt
    |-- README.md
    |-- .env
    │
    |-- config/
    |   |-- init.py
    |   |-- asgi.py
    |   |-- wsgi.py
    |   |-- urls.py
    |   |-- settings.py
    │
    |-- apps/
    |   |-- users/ # User profiles, skills, vulnerability attributes
    |   |-- jobs/ # Job listings, employers, and skill requirements
    |   |-- analytics/ # AI/ML models and data processing logic
    │
    |-- data/ # Datasets (CSV, JSON)
    |-- scripts/ # Helper scripts for data loading and model training
    |-- static/ # Global static files (CSS, JS)
    |-- media/ # Uploaded user files (e.g., resumes)

---


