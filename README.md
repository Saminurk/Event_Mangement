# Event_Mangement
A comprehensive event management system with Django + FastAPI backend and React.js frontend.

Some local setup are given below :
Prerequisites-
>Node.js 16.x or higher
>Python 3.8 or higher
>Git
  
Backend Setup
bash
Navigate to server directory
cd server/event_management

To Create virtual environment
python -m venv venv

To Activate virtual environment
For Windows:
venv\Scripts\activate
For macOS/Linux:
source venv/bin/activate

To Install dependencies
pip install -r ../requirements.txt

To Setup database
python manage.py makemigrations
python manage.py migrate

For Frontend Setup
bash
Navigate to client directory
cd ../../client/event_management

To Install dependencies
npm install


To Run the Application
FastAPI will run on: http://localhost:8001
Django + FastAPI (Full Setup)
bash
Terminal 1: Django Admin Server
cd server/event_management
python manage.py runserver

Terminal 2: FastAPI Server
cd server/event_management
python fastapi_app.py

Django Admin will run on: http://localhost:8000
FastAPI will run on: http://localhost:8001

Start Frontend (Terminal 3)
bash
cd client/event_management
npm run dev
Frontend will run on: http://localhost:3000

Access the Application
> Frontend: http://localhost:3000
> FastAPI API: http://localhost:8001
> Django Admin: http://localhost:8000 

1. *Port conflicts:* Make sure ports 3000, 8000, and 8001 are available
2. *Python virtual environment:* Always activate venv before running backend
3. *Dependencies:* Run npm install and pip install -r requirements.txt if you encounter import errors
