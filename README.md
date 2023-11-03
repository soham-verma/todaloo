# To-Do List Application

The To-Do List Application is a Django-based web application that provides users with a simple and intuitive interface to manage their daily tasks.

## Features

- **User-Friendly Interface**: Manage your tasks with an easy-to-use web interface.
- **Task Management**: Add, update, and delete tasks with ease.
- **Persistent Storage**: Tasks are stored in a SQLite database, ensuring that your data persists between sessions.

## Quick Start

To get this application running on your local machine, you'll need Python and Django installed. Here are the steps to follow:

1. Clone the repository to your local machine.
2. Navigate to the project directory where `manage.py` is located.
3. Run `python manage.py makemigrations` to create migrations for the database schema.
4. Run `python manage.py migrate` to apply migrations to the database.
5. Finally, start the server with `python manage.py runserver`.
6. Open your web browser and go to `http://127.0.0.1:8000/` to view the application.

## Usage

Once the application is running, you can perform the following actions:

- **Viewing Tasks**: Simply visit the index page to see a list of all current tasks.
- **Adding a Task**: Use the provided form to enter a new task and click the submit button to add it to the list.
- **Updating a Task**: Click on the edit link next to a task to update its title or mark it as complete.
- **Deleting a Task**: Click on the delete link to remove a task from the list.

## Configuration

The application is currently in development mode, which is not suitable for a production environment. Before deploying, make sure to set `DEBUG = False` in `settings.py` and configure the `ALLOWED_HOSTS` appropriately.

## Contributing

Contributions to the To-Do List Application are welcome. Please feel free to fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
