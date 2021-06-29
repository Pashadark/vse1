# MFC

Opisanie

[![Built with Django3 Site Template](https://img.shields.io/badge/Built%20with-Django3%20Site%20Template-blueviolet.svg)](https://github.com/griceturrble/django3-site-template/) [![Black code style](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/ambv/black)


## License

This project uses the MIT license. Please see the [LICENSE](LICENSE) for details.


## Installation

1. Create a new Python virtual environment.

   - Using `venv` on Linux:

     ```bash
     python3 -m venv .venv --prompt Test
     ```

   - Using `venv` on Windows:

     ```bash
     python3 -m venv .venv --prompt Test
     ```

   - Or, use whichever style of virtual environment management you prefer!

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

1. Migrate models to the database:

   ```bash
   python Test/manage.py migrate 
   ```

1. Create a superuser:

   ```bash
   python Test/manage.py createsuperuser
   ```

1. Run the development server:

   ```bash
   python Test/manage.py runserver
   ```

1. Open http://localhost:8000 to view the running site.
