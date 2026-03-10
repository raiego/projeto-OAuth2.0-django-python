🔐 Django OAuth2 Authentication (GitHub Login)

A Django web application that implements OAuth2.0 authentication with GitHub, created to demonstrate how to integrate secure social login using environment variables and modern authentication practices.

This project is useful for developers who want to learn how to implement OAuth-based authentication in Django applications.

🚀 Features

🔑 Authentication using GitHub OAuth2

👤 Automatic user login and account creation via GitHub

🔒 Secure credential storage using environment variables (.env)

🧩 Modular Django structure with separated apps

🛠️ Ready-to-run development setup

🛠️ Technologies Used

Python

Django

OAuth2.0 (GitHub Authentication)

django-allauth (or similar library)

Environment Variables (.env)

HTML / Django Templates

📦 Project Structure

The project follows a modular Django structure with separated apps and configuration:

project/
 ├── setup/
 ├── tech/
 ├── templates/
 ├── manage.py
 └── requirements.txt
⚙️ Running the Project Locally
1️⃣ Clone the repository
git clone https://github.com/raiego/projeto-OAuth2.0-django-python.git
cd projeto-OAuth2.0-django-python
2️⃣ Create and activate a virtual environment

Windows

python -m venv .venv
.venv\Scripts\activate

Linux / macOS

python -m venv .venv
source .venv/bin/activate
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Create a .env file

Add your credentials (do not commit this file):

SECRET_KEY=your_secret_key
GITHUB_CLIENT_ID=your_client_id
GITHUB_SECRET=your_client_secret
5️⃣ Run the development server
python manage.py runserver

The application will be available at:

http://localhost:8000
📚 What This Project Demonstrates

This project demonstrates:

OAuth2 authentication flow

Social login integration

Secure environment variable management

Django project organization

💡 Educational project created for learning authentication and backend development with Django.
