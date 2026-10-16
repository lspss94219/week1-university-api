# University API

A FastAPI service that serves in-memory university student data. It exposes a root endpoint describing the API, a list of all students, and lookup of a single student by ID (returns `404` if the ID is unknown).

## Requirements

- Packages listed in `requirements.txt` (FastAPI and Uvicorn)

## Installation

```bash
python -m venv .venv
source .venv/bin/activate  # on Windows: .venv\Scripts\activate
python -m pip install -r requirements.txt
```

## Running the API

```bash
uvicorn main:app --reload
```

## API Endpoints

- `GET /` - Root endpoint with API info
- `GET /students` - Retrieve all students
- `GET /students/{student_id}` - Retrieve a student by ID (e.g. `/students/s1`)
