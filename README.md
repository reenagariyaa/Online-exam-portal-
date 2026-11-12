
# Online Examination Portal

A web application for conducting timed multiple-choice exams.
Web-based exam platform with timed quizzes, auto-scoring, and an admin panel (Django, MySQL)
Students can attempt tests and see results instantly, while admins
manage tests and questions.

## Features
- Student registration and login
- Timed tests with auto-submit when time ends
- Automatic scoring and instant results
- Result history for each student
- Admin panel to create tests, add questions, and view scores
- Input validation and session-based authentication

## Tech Used
Python, Django, MySQL, HTML, CSS, JavaScript

## How to Run
1. Clone the repo: git clone <your-repo-link>
2. Go to the folder: cd online-exam-portal
3. Install requirements: pip install -r requirements.txt
4. Set up the database in settings.py
5. Run migrations: python manage.py migrate
6. Create admin: python manage.py createsuperuser
7. Start server: python manage.py runserver



## What I Learned
How to structure a Django project, design relational database
tables, handle user authentication, and build a timer-based
workflow.
