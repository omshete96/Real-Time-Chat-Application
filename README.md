# Real-Time Chat Application

This project is a real-time chat application built using Django. It features user authentication, WebSocket-based communication for live chat, a collapsible user menu, and chat message storage in the database.

## Features
- User Sign Up and Login
- Collapsible menu displaying all registered users
- Real-time chat functionality using WebSocket
- Chat message history stored in a database
- User-friendly interface

## Requirements
- Python 3.8+
- Django 4.2+
- Redis Server
- Channels and channels-redis

## Installation

1. Clone the Repository:
   git clone https://github.com/<your-username>/chat-application.git
   cd chat-application
   
2.Create and Activate a Virtual Environment:
  python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate

3.Install Dependencies:
  pip install -r requirements.txt

4.Run Migrations:
  python manage.py makemigrations
  python manage.py migrate

5.Start Redis Server: Ensure Redis is installed and running on your system:
  redis-server

6.Run the Development Server:
  python manage.py runserver

7.Access the Application: Open your web browser and go to http://127.0.0.1:8000
