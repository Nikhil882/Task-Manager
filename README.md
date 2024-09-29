# Flask Task Manager

## Project Overview
Flask Task Manager is a simple web application built using Python's Flask framework and SQLite as the database. It allows users to manage tasks by creating, updating, and deleting them. The application visually distinguishes between completed tasks and overdue tasks for better organization.

## Features
- Add new tasks with a title, description, and deadline.
- Mark tasks as complete.
- Delete tasks.
- Visually differentiate between completed tasks (with a strikethrough) and overdue tasks (with a red border).
- Responsive design using Bootstrap for a better user experience.

## Requirements
- Python 3.x
- Flask
- Flask-SQLAlchemy

## Installation Instructions
1. **Clone the Repository**
   ```bash
   git clone https://github.com/Nikhil882/Task-Manager.git
   cd flask-task-manager
   ```

2. **Create a Virtual Environment**
   It's a good practice to use a virtual environment to manage your project dependencies.
   ```bash
   python -m venv venv
   ```

3. **Activate the Virtual Environment**
   - **Windows:**
     ```bash
     venv\Scripts\activate
     ```
   - **macOS/Linux:**
     ```bash
     source venv/bin/activate
     ```

4. **Install Required Packages**
   Install Flask and Flask-SQLAlchemy using pip:
   ```bash
   pip install Flask Flask-SQLAlchemy
   ```

5. **Run the Application**
   - Navigate to the project directory and run the application:
   ```bash
   python app.py
   ```

6. **Access the Application**
   Open your web browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

## Directory Structure
```
flask-task-manager/
│
├── app.py                  # Main application file
├── templates/              # Folder containing HTML templates
│   └── index.html          # Template for displaying tasks
└── venv/                   # Virtual environment folder
```

## Contributing
Feel free to fork the repository and submit pull requests. For any issues or feature requests, please create an issue in the repository.
