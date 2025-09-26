# MLE Sprint 3 - Churn Prediction API

FastAPI приложение для предсказания оттока клиентов с использованием CatBoost модели.

## Установка

```bash
pip install -r requirements.txt
```

## Запуск

```bash
uvicorn app.churn_app:app --reload --port 8081
```

## API

- `POST /api/churn/` - Предсказание оттока клиента
- `GET /docs` - Swagger документация