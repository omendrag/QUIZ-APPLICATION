📚 Quiz Application

The Quiz Application is a simple and interactive platform designed to make learning and testing knowledge fun. It allows users to participate in quizzes, track their performance, and get instant results. This project is ideal for students, educators, and anyone who loves quizzes!

✨ Key Features
👩‍🎓 For Learners

🎯 Clean & distraction-free UI – focus only on learning.

📝 Multiple-choice questions (MCQs) – single correct answer format.

⏳ Built-in timer – auto-submits when time runs out.

📊 Instant scoring – see results immediately after submission.

📜 Attempt history – track all past attempts with scores & timestamps.

🛠 For Admins

🔑 Secure admin login with Django authentication.

👥 User management – add, edit, delete, or bulk upload users (CSV).

📚 Quiz management – create, edit, delete, or bulk upload quizzes.

❓ Question & option management – define correct and wrong answers.

📈 Analytics dashboard – get insights on users, quizzes, and attempts.

🏗 Tech Stack

Backend: Django (Python)

Frontend: HTML, CSS, Bootstrap 5

Database: SQLite (default), supports PostgreSQL/MySQL

Authentication: Django’s built-in authentication

🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/omendrag/Quiz_app.git
cd Quiz_app

2️⃣ Set up virtual environment & install dependencies
# Create virtual environment
python -m venv venv  

# Activate environment
# Linux / macOS
source venv/bin/activate
# Windows (CMD)
venv\Scripts\activate
# Windows (PowerShell)
venv\Scripts\Activate.ps1

# Install dependencies
pip install -r requirements.txt

3️⃣ Run migrations
python manage.py makemigrations
python manage.py migrate

4️⃣ Create admin account
python manage.py createsuperuser

5️⃣ Start development server
python manage.py runserver

6️⃣ Access the platform

User site → http://127.0.0.1:8000/

Admin dashboard → http://127.0.0.1:8000/admin/dashboard/
