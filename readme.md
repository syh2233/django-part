Django tutorial (official) — Part 1

This repo follows: https://docs.djangoproject.com/en/5.2/intro/tutorial01/

Quick start (Windows PowerShell):

1) Create venv + install deps
   python -m venv .venv
   .\.venv\Scripts\python -m pip install -r requirements.txt

2) Run dev server
   cd djangotutorial
   ..\.venv\Scripts\python manage.py runserver

Then visit:
- http://127.0.0.1:8000/polls/
- http://127.0.0.1:8000/admin/