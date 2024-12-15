# Student-management-system
Student Management System
A simple Student Management System built with Django. This web application allows administrators and teachers to manage student data, including adding, updating, and deleting student records, as well as viewing student details and performance reports.

Features
Student Registration: Add new students with personal details such as name, age, class, and more.
Student Information: View individual student profiles, including performance and attendance records.
CRUD Operations: Perform Create, Read, Update, and Delete operations for student records.
Authentication: Admin login functionality to manage the system.
User Roles: Different levels of access for admin and teachers.

Technologies Used
Django: Python web framework used to build the application.
SQLite: The default database used to store student records.
HTML/CSS: For rendering the user interface.
Bootstrap: Front-end framework for responsive design (optional based on implementation).

Installation
Prerequisites
Python 3.6 or higher
Django 4.x
SQLite (included by default with Django)

Steps to Install
1.Clone the repository:
$ git clone https://github.com/yourusername/student-management-system.git
$ cd student-management-system

2.Create a virtual environment (optional but recommended):
$ python -m venv venv
# On Windows, use venv\Scripts\activate

3.Install required dependencies:
$ pip install -r requirements.txt

4.Apply database migrations:
$ python manage.py migrate

5.Create a superuser to access the admin panel:
python manage.py createsuperuser

Follow the prompts to set up the admin credentials.

6.Run the development server:
$ python manage.py runserver

7.Open your browser and go to http://127.0.0.1:8000/ to view the application. To access the admin panel, visit http://127.0.0.1:8000/admin/ and log in using the superuser credentials.

Folder Structure
student_management/: Main Django app for handling student data.
templates/: Contains HTML files for views.
static/: Static files like CSS and JavaScript.
migrations/: Database migrations for the Django app.
manage.py: Django's command-line utility for administrative tasks.

Contributing
Feel free to fork the repository and submit pull requests if you'd like to contribute to the project. If you encounter any issues or have feature suggestions, please open an issue in the repository.

License
This project is open-source and available under the MIT License.
