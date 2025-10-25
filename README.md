# Django Todo App

A simple web application for managing tasks (todo list) built with Django.

## Features

- Add new tasks with title and description
- Mark tasks as complete or incomplete
- Edit existing tasks
- Delete tasks
- View all tasks in a list

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd django-todo-app
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS/Linux: `source venv/bin/activate`

4. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

5. Run migrations:
   ```
   python manage.py migrate
   ```

6. Run the development server:
   ```
   python manage.py runserver
   ```

7. Open your browser and go to `http://127.0.0.1:8000/`

## Usage

- Navigate to the home page to see all tasks.
- Click "Add New Task" to create a new task.
- Use the buttons next to each task to mark as complete/incomplete, edit, or delete.

## Admin Interface

You can access the Django admin interface at `http://127.0.0.1:8000/admin/` to manage tasks directly.

## Technologies Used

- Django 5.2.7
- Python 3.x
- HTML/CSS (Bootstrap-like styling)

## Contributing

Feel free to fork this repository and submit pull requests.

## License

This project is open source and available under the [MIT License](LICENSE).
