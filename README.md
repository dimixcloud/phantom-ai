# Phantom AI Backend

A custom AI backend service built with FastAPI and deployed on Render.com. It provides endpoints for generating and summarizing text.

## 🚀 API Endpoints

All protected endpoints require an `X-API-Key` header.

| Method | Endpoint                     | Description            |
|--------|------------------------------|------------------------|
| GET    | `/`                          | Welcome message        |
| GET    | `/health`                    | Health check           |
| POST   | `/api/v1/generate/text`      | Generate AI content    |
| POST   | `/api/v1/summarize/text`     | Summarize input text   |

### 🔐 Example Header
