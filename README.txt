PLACEMENT MANAGEMENT SYSTEM
===========================

TECHNOLOGY
- Python + Flask
- SQLite database
- HTML, CSS, Bootstrap 5, Jinja2

WINDOWS SETUP
1. Extract this ZIP file.
2. Open PowerShell in the extracted placement_management_system folder.
3. Install dependencies:
   py -m pip install -r requirements.txt

   If the 'py' command does not work, use your Python 3.14 executable:
   & "$env:LOCALAPPDATA\Programs\Python\Python314\python.exe" -m pip install -r requirements.txt

4. Start the application:
   py app.py

   Or:
   & "$env:LOCALAPPDATA\Programs\Python\Python314\python.exe" app.py

5. Open this address in your browser:
   http://127.0.0.1:5000

DEFAULT ADMIN LOGIN
Email: admin@placement.com
Password: admin123

SAMPLE JOBS
The database is initialized automatically. Five sample company accounts and jobs
are inserted only when the database is first created.

IMPORTANT
- Register as a student to test applying for jobs.
- Student CGPA must meet the job's minimum CGPA.
- Register a company to test company approval and job posting.
- The default admin password is for local project demonstration only.
  Change it before using this project beyond a classroom demo.
- The Flask development server is for learning/testing, not production hosting.
- Do not delete placement.db if you want to keep your registrations and applications.
