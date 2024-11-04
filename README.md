# Social Network App

A simple social media app inspired by **X** (formerly Twitter), built with Django. Users can sign up, create posts, comment, and interact with others by liking or disliking posts and comments. The app also supports following and viewing followers.

## Features
- **User authentication** using Django AllAuth
- **Post and comment** system
- **User profiles and feed** to express yourself and keep track of recent posts
- **Likes and dislikes** for posts and comments
- **User following** and follower lists
- **Responsive design** with Bootstrap 5

---

## Installation

1. **Clone the repository and navigate to the project folder:**
   ```bash
   django-admin startproject socialnetwork
   cd socialnetwork
   ```

2. **Set up the Django apps:**
   ```bash
   python3 manage.py startapp social
   python3 manage.py startapp landing
   ```

3. **Run migrations and create a superuser:**
   ```bash
   python3 manage.py migrate
   python3 manage.py createsuperuser
   ```

4. **Install dependencies:**
   ```bash
   pip install django-allauth django-crispy-forms
   ```

## Running the App

1. **Navigate to the project directory**

2. **Start the development server:**
   ```bash
   python manage.py runserver
   ```

---

## Tech Stack

- **Language:** Python
- **Framework:** Django
- **Authentication:** Django AllAuth
- **Styling:** Bootstrap 5

---

