# Learning
Testing of code
# KPA API Assignment – FastAPI + PostgreSQL

## 👩‍💻 Setup Instructions

```bash
git clone <your-repo-url>
cd kpa_assignment
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Create `.env`:
```
DATABASE_URL=postgresql://postgres:password@localhost/kpa_db
```

## 🌐 API Endpoints

| Method | Endpoint     | Description           |
|--------|--------------|-----------------------|
| POST   | `/form`      | Submit new form data  |
| GET    | `/forms`     | Retrieve all forms    |

## 🛠 Tech Stack
- FastAPI
- PostgreSQL
- SQLAlchemy
- Pydantic
- Postman
- Swagger UI (http://127.0.0.1:8000/docs)

## ✅ Features Implemented
- Token-less, public submission API
- PostgreSQL integration
- Error handling & validations
- Swagger documentation auto-exposed

## ⚠️ Assumptions
- No authentication layer required
- Data fields are simple text for the form
