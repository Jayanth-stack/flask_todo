
# Flask To-Do Application

Welcome to the Flask To-Do Application! This is a simple web-based task management app where users can create, view, update, and delete tasks. The project is built using Python's Flask microframework and allows you to manage your tasks efficiently in a minimalistic and user-friendly interface.

## Tech Stack

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)



- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite
- **Deployment**: Local Development Server (Flask)

## Features

- Add new tasks with ease.
- View a list of all tasks.
- Edit tasks to update the status or content.
- Delete tasks you no longer need.

## Project Structure

```
📁 flask_todo_app/
    ├── 📁 static/
    │   └── style.css  # Custom CSS for the app
    ├── 📁 templates/
    │   └── index.html  # Main page template for the application
    ├── app.py  # Main Flask application file
    ├── models.py  # Database model for tasks
    ├── README.md  # Project documentation (this file)
    └── requirements.txt  # Python dependencies
```

## Installation and Setup

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

- Python 3.x installed on your machine
- Virtual environment (optional but recommended)
- Flask (Python microframework)
- SQLite (comes with Python)

### Running the Application

1. **Clone the Repository**

   Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/your-username/flask-todo-app.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd flask-todo-app
   ```

3. **Set Up a Virtual Environment (Optional)**

   It's a good practice to use a virtual environment for Python projects. You can set it up with the following commands:

   - On macOS/Linux:
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

   - On Windows:
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```

4. **Install Dependencies**

   Install the required Python packages from the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Application**

   Start the Flask development server:
   ```bash
   python app.py
   ```

6. **Open in Browser**

   Open your web browser and go to:
   ```
   http://127.0.0.1:5000
   ```

   You should see the To-Do application up and running.

## Usage

- **Create Task**: Add a new task by entering the task description in the input box and clicking "Add Task."
- **View Tasks**: All added tasks will be listed on the main page.
- **Edit Task**: Click on the task to edit its content.
- **Delete Task**: Click on the "Delete" button next to the task to remove it.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request. All contributions are welcome!
