# Student Career Platform

Full-stack starter for a Student Career Guidance + LMS platform.

## Stack
- Frontend: React + Vite
- Backend: Django + Django REST Framework
- Database: MySQL
- Cache: Redis

## Run
### Backend
```bash
cd backend
python -m venv venv
# Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

Copy `.env.example` to `.env` and configure credentials before production use.
