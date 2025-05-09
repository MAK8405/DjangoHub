
# DjangoHub

**DjangoHub** is a personal collection of Django projects and applications, serving as a centralized hub for learning, experimenting, and demonstrating various features of the Django web framework.

## 📘 Overview

This repository includes:

- **MyTennisClub**: A Django project simulating a tennis club management system.
- **members**: An app within MyTennisClub handling member-related functionalities.

These projects are designed to explore and showcase Django's capabilities in building robust web applications.

## 📂 Repository Structure

- `MyTennisClub/`: The main Django project directory.
  - `members/`: Django app managing club members.
  - `manage.py`: Django's command-line utility for administrative tasks.

## 🚀 Getting Started

To run the project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/MAK8405/DjangoHub.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd DjangoHub/MyTennisClub
   ```

3. **Create and activate a virtual environment:**

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

4. **Install the required packages:**

   ```bash
   pip install django
   ```

5. **Apply migrations:**

   ```bash
   python manage.py migrate
   ```

6. **Run the development server:**

   ```bash
   python manage.py runserver
   ```

   Access the application at `http://127.0.0.1:8000/`.

## 🛠 Prerequisites

- Python 3.x
- Django

## 🤝 Contributing

As this is a personal project, contributions are not currently being accepted. However, feedback and suggestions are welcome.

## 📄 License

This project is open-source and available under the MIT License.
