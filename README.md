# aap (android_app_points) - A functioning web app

video link -https://drive.google.com/file/d/12NtY4nVaD5cnVfzG_XjZn5sgp7HI_wFZ/view?usp=drive_link

deployed web app link -https://rishabhrathor0793.pythonanywhere.com/

inside aap directory
# cd aap
start the server
# python manage.py runserver

# myapp Interface

# Problem Set 3 - Questions
# A. Periodic Task Scheduling:

For scheduling periodic tasks, I would recommend using Celery with a message broker like RabbitMQ or Redis. Celery is reliable and can handle a large number of tasks, making it suitable for production environments. It scales well and allows for distributed task processing. If not using Celery, a simple cron job could suffice for smaller applications, but it lacks the flexibility and reliability of Celery.
# B. Flask vs. Django:

Use Flask when you need a lightweight, micro-framework for small applications or APIs where you want more control over components. It's great for prototyping and when you want to avoid the overhead of a full-stack framework.
Use Django for larger applications that require a robust framework with built-in features like ORM, authentication, and admin interface. Django is better suited for projects that need rapid development and scalability.