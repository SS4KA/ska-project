# SkaProject - Информационный портал по игре Rust
Информационный портал для игры Rust с калькуляторами ресурсов, справочником предметов, маркетом и интеграцией Steam API.
WRUST - Универсальная энциклопедия
Описание проекта
Ключевые особенности:

    Калькулятор ресурсов (серы и других материалов)
    Поисковая система по игровой информации
    Современный интерфейс на базе React
    Планируемая интеграция с нейросетями и Telegram-ботами

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
Аналитическая часть
ВВЕДЕНИЕ

Проект "SKA Prolect" разрабатывается для решения следующих проблем игрового сообщества RUST:

    Сложность расчета ресурсов для крафта
    Трудности в поиске актуальной игровой информации
    Отсутствие централизованной платформы для вспомогательных инструментов

Техническая архитектура

Хранение данных:

    Локальная база данных для статической информации
    Интеграция с внешними API для получения актуальных данных

Планируемые интеграции:

    Telegram-бот для быстрого доступа к калькуляторам
    AI-ассистент для ответов на игровые вопросы
    API для отслеживания цен на предметы торговой площадки[в стадии обсуждения]

Бизнес-модель

Монетизация:

    Контекстная реклама тематических проектов и услуг
    Партнерские программы с:
        Сервисами торговли игровыми предметами
        Платформами для пополнения игрового баланса
        Игровыми серверами и сообществами
    Премиум-функции для активных пользователей

Перспективы развития:

    Запуск собственного игрового сервера RUST
    Система аналитики игровых метрик
    Социальные функции для создания игровых групп

Целевая аудитория

    Новички RUST (16-25 лет): Упрощение освоения сложной игровой механики
    Опытные игроки (20-35 лет): Оптимизация игровых процессов и доступ к эксклюзивной информации

Конкурентные преимущества

    Постоянное обновление в соответствии с патчами игры
    Удобный и интуитивный интерфейс
    Планы по интеграции уникальных AI-функций []


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
Ссылки 
ТЗ https://docs.google.com/document/d/18CcJsZhsWrO4_xUPkF698HSKUpdWpwEX9KGyZiNrDbs/edit?usp=sharing
макет https://www.figma.com/design/MbHkBSM4GJxXhOGcAhcPOp/Ska?node-id=0-1&t=NXHu1MfTjCKf57GK-1
