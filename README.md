Django Polls App — Tutorials 1 to 3

This project is my implementation of Django’s official tutorial (Parts 1–3).
It includes creating a Django app, adding models, views, templates, and using the admin panel.

Features
	•	Tutorial 1: Basic view and URL routing
	•	Tutorial 2: Models (Question, Choice), migrations, and admin setup
	•	Tutorial 3: Templates, dynamic views, and voting functionality

How to Run
git clone https://github.com/techy-creasy/djangotutorial.git
cd djangotutorial

python3 -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
Open in browser:
	•	Polls app → http://127.0.0.1:8000/polls/
	•	Admin → http://127.0.0.1:8000/admin/
  
Project Structure
manage.py
mysite/
polls/
requirements.txt
