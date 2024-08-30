# Library Management System

This is a web-based Library Management System built using the Django framework. The system allows for the management of books, members, and transactions (such as borrowing and returning books) in a library.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Book Management**: Add, update, view, and delete books.
- **Member Management**: Manage library members (add, update, delete).
- **Transaction Management**: Manage book borrowing and returning transactions.
- **User Authentication**: Admin users can log in to manage the library.
- **Search Functionality**: Search for books and members.

## Requirements

- Python 3.x
- Django 3.x or later
- SQLite (default) or another supported database (PostgreSQL, MySQL, etc.)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/shreyags831/librarymanagement.git
   cd librarymanagement
   ```

2. **Create and activate a virtual environment:**

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up the database:**

   Run the following commands to set up the database:

   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (admin):**

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**

   ```bash
   python manage.py runserver
   ```

7. **Access the application:**

   Open your browser and navigate to `http://127.0.0.1:8000/` to view the application. The admin interface can be accessed at `http://127.0.0.1:8000/admin/`.

## Usage

Once the project is up and running:

- **Admin Interface**: Use the Django admin interface to manage books, members, and transactions.
- **Library Management**: Add, view, and manage books and members.
- **Transaction Management**: Record borrowing and returning of books.

### Main Components:

1. **`librarymanagement/`**: This is the main project directory containing the settings and configuration files for the Django project.
2. **`libraryapp/`**: This app contains the models, views, and templates for managing books, members, and transactions.
3. **`static/` and `templates/`**: These directories contain static files (e.g., CSS, JS) and HTML templates used for rendering the frontend.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
