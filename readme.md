# Project Title

This repository contains a project developed as part of the coursework for the **Higher Degree in Multimedia Application Development (DAM)** at **IES El Cañaveral de Móstoles, Madrid**.

# Blog Project with Django

This is a simple blog application built with Django. Users can read blog posts that are listed in chronological order.

## Features

- List blog posts with titles, content, and timestamps.

## Prerequisites

- Python 3.6 or higher
- pip (Python package installer)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/blog_project.git
    cd blog_project
    ```

2. Create and activate a virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations to set up the database:

    ```bash
    python manage.py migrate
    ```

5. Create a superuser to access the Django admin:

    ```bash
    python manage.py createsuperuser
    ```

## Running the Application

1. Start the development server:

    ```bash
    python manage.py runserver
    ```

2. Open your web browser and go to `http://127.0.0.1:8000/` to see the blog posts.

3. Access the Django admin at `http://127.0.0.1:8000/admin/` to manage blog posts.
