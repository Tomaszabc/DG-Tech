# My Django App

This is a simple Django application that uses Tailwind CSS for styling. 

## Project Structure

```
my-django-app
├── my_django_app
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── app
│   ├── __init__.py
│   ├── views.py
│   ├── urls.py
│   └── templates
│       └── index.html
├── manage.py
└── README.md
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd my-django-app
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install Django:
   ```
   pip install django
   ```

4. Run migrations:
   ```
   python manage.py migrate
   ```

5. Start the development server:
   ```
   python manage.py runserver
   ```

6. Open your browser and go to `http://127.0.0.1:8000/`.

## Usage

You can modify the views in `app/views.py` and the templates in `app/templates/index.html` to customize the application according to your needs.

## License

This project is licensed under the MIT License - see the LICENSE file for details.