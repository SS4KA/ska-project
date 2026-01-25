# SkaProject - Информационный портал по игре Rust
Информационный портал для игры Rust с калькуляторами ресурсов, справочником предметов, маркетом и интеграцией Steam API.
##  Технологический стек
### Frontend
- React Vite
- React Router DOM
- Zustand 
- TailwindCSS
- Framer Motion
- React Hook Form 

### Backend
- Django 
- Django REST Framework
- PostgreSQL
- JWT Authentication
- Steam API Integration

## Установка и запуск

### Frontend
```bash
cd frontend
npm install
npm run dev
```
### Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```