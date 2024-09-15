## Project Setup

### Prerequisites
- Python 3.6 or higher installed
- pip package manager
- virtualenv or pipenv for virtual environment management

### Installation

1. **Create and activate a virtual environment**:

    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

2. **Install Django**:

    ```bash
    pip install django
    ```

3. **Create a new Django project**:

    ```bash
    django-admin startproject myproject
    ```

    This will create a new Django project named `myproject`.

4. **Change into the project directory**:

    ```bash
    cd myproject
    ```

5. **Create a new Django app within the project**:

    ```bash
    python manage.py startapp myapp
    ```

    This will create a new Django app named `myapp` within your project.

6. **Apply database migrations**:

    ```bash
    python manage.py migrate
    ```

    This will create the necessary database tables for your project.

7. **Create a superuser account**:

    ```bash
    python manage.py createsuperuser
    ```

    Follow the prompts to create a superuser account for the admin interface.

8. **Start the development server**:

    ```bash
    python manage.py runserver
    ```

    This will start the Django development server at `http://127.0.0.1:8000/`.

- `manage.py`: A command-line utility that allows you to interact with your Django project.
- `myproject/`: The project directory containing the project-level settings and URLs.
- `myapp/`: The app directory containing the app-specific code.
