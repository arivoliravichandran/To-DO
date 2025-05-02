# Flask Todo App

A simple and modern Todo application built with Flask and SQLite, with Docker support for easy deployment.

## Features

- Create, read, update, and delete todos
- Mark todos as complete/incomplete
- Modern UI with Tailwind CSS
- RESTful API endpoints
- SQLite database for persistence
- Docker support for containerized deployment

## Setup

### Option 1: Local Development

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

### Option 2: Docker Deployment

1. Build the Docker image:

```bash
docker build -t flask-todo-app .
```

2. Run the container:

```bash
docker run -p 5000:5000 flask-todo-app
```

3. Access the application at:

```
http://localhost:5000
```

## Project Structure

```
.
├── app.py              # Main application file
├── requirements.txt    # Python dependencies
├── templates/          # HTML templates
├── instance/          # Database and configuration files
├── dockerfile         # Docker configuration
└── README.md          # Project documentation
```

## API Endpoints

- `GET /api/todos` - Get all todos
- `POST /api/todos` - Create a new todo
- `PUT /api/todos/<id>` - Update a todo
- `DELETE /api/todos/<id>` - Delete a todo

## Technologies Used

- Flask - Web framework
- SQLAlchemy - Database ORM
- SQLite - Database
- Tailwind CSS - Styling
- JavaScript (Vanilla) - Frontend interactivity
- Docker - Containerization

## Contributing

Feel free to submit issues and enhancement requests!
