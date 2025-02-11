# BlogSpot

BlogSpot is a multi-user blog application built using Django. It serves as more than just a blogging platform—it acts as a community space where users can engage with each other through posts and comments.

## Features

- **Multi-User Access in Real-Time**  
  - New users can instantly access all previous posts upon signing up.
  - Posts and comments are visible to all users.

- **Community Interaction**  
  - Users can comment on posts, fostering discussions within the platform.

- **User Profile Customization**  
  - Users can update their profile details, including:
    - Profile picture
    - Name
    - Email  
  - Modifications can be made at any time.

- **Backend & Database**  
  - Built entirely with **Django**.
  - Uses **Django ORM** for efficient database management.

## Installation

### Prerequisites
- Python (>=3.8)
- Django (>=4.0)
- SQLite (default) or PostgreSQL (optional for production)

### Setup

1. **Clone the Repository**
   ```sh
   git clone https://github.com/Murali-77/Blog-Application---Django
   cd BlogSpot_Community_Space--master

2. **Create a Virtual Environment**(Optional but recommended)
   ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`


3.**Install Dependencies** using : pip install -r requirements.txt

4. **Apply Migrations**
   ```sh
    python manage.py migrate
    Create a Superuser (Admin)

6. **Create a Superuser (Admin)**
   ```sh
    python manage.py createsuperuser
    Run the Development Server

7. **Run the Development Server**
 ```sh
    python manage.py runserver
    Access the application at http://127.0.0.1:8000/
