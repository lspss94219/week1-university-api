University API

A simple FastAPI project that provides endpoints to view student information.

API Endpoints
`GET /` - API welcome page
`GET /students` - Get all students
`GET /students/{student_id}` - Get a student by ID (e.g., 's1', 's10')

Setup & Run

Activate virtual environment:
   source .venv/bin/activate  # On Windows: .venv\Scripts\Activate.ps1

Install dependencies
   python -m pip install -r requirements.txt

Run Server
   uvicorn main:app --reload
