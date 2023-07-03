# Django Portfolio

A simple Django-based portfolio website. It allows you to showcase your projects, skills, and experience in a clean and visually appealing way. The website is built using Django, a powerful web framework for creating dynamic web applications.

## Features

- **Project Showcase:** Display your projects with important details like titles, descriptions, images, and links.
- **Skills Section:** Highlight your skills and areas of expertise to give visitors a comprehensive overview of your abilities.
- **Experience:** Present your work experience and educational background to provide context and credibility.
- **Contact Form:** Include a contact form for visitors to reach out to you directly.
- **Responsive Design:** The website is designed to be mobile-friendly and accessible on different devices.
- **Admin Panel:** Use Django's built-in admin panel to easily manage and update your portfolio content.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
git clone https://github.com/initeshkaushik/django-portfolio.git

2. Go to the project directory:
cd django-portfolio

3. Create a virtual environment:
python -m venv env

4. Activate the virtual environment:
- Windows:

   ```
  .\env\Scripts\activate
  ```
- macOS/Linux:

  ```
  source env/bin/activate
  ```
5. Install the required dependencies:
pip install -r requirements.txt

6. Set up the database:
- Modify the database settings in `settings.py` to match your local environment.
- Run migrations:

  ```
  python manage.py migrate
  ```
7. Start the development server:
python manage.py runserver


The portfolio website should now be accessible at `http://localhost:8000`.

## Usage

Once the server is running, you can access the portfolio website through your browser. Here are some key actions you can take:

- **Admin Panel:** Create a superuser account by running `python manage.py createsuperuser` and access the admin panel at `http://localhost:8000/admin`. From there, you can add, edit, or remove projects, skills, experiences, and other portfolio content.
- **Display Projects:** The homepage showcases your projects. Click on a project to view its details.
- **Contact Form:** Visitors can use the contact form on the website to send you messages. You will receive these messages in the email associated with your Django installation.
