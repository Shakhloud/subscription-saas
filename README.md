# Subscription SaaS (mini)

Мини-проект: платформа подписок (Express.js backend, React+Redux frontend, PostgreSQL, Docker).

## Структура
- `backend/` — Express.js + TypeScript
- `frontend/` — React + Redux
- `.github/workflows/` — CI

## Быстрый старт
1. Скопировать `.env.example` в `backend/.env` и `frontend/.env` и заполнить.
2. Запустить Docker Compose:
   ```bash
   docker-compose up --build
