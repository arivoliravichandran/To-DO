# Flask Todo App

A simple and modern Todo application built with Flask and SQLite.

## Features

- Create, read, update, and delete todos
- Mark todos as complete/incomplete
- Modern UI with Tailwind CSS
- RESTful API endpoints
- SQLite database for persistence

## Setup

1. Create a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the application:

```bash
python app.py
```

4. Open your browser and navigate to:

```
http://localhost:5000
```

## API Endpoints

- `GET /api/todos` - Get all todos
- `POST /api/todos` - Create a new todo
- `PUT /api/todos/<id>` - Update a todo
- `DELETE /api/todos/<id>` - Delete a todo

## Technologies Used

- Flask
- SQLAlchemy
- SQLite
- Tailwind CSS
- JavaScript (Vanilla)
