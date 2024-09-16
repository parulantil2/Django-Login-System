# Django Login System with Pagination, CRUD Operations, and JWT Authentication

## Overview

This project is a Django-based web application that includes:
- **User Authentication**: Registration, login, logout, and JWT-based authentication.
- **CRUD Operations**: Create, read, update, and delete functionality for a specific model (e.g., user profiles, posts).
- **Pagination**: Efficient pagination for list views.
- **Email Notifications**: Send email after user registration.
- **REST API**: Built using Django REST Framework with JWT for authentication.

## Features

- **User Authentication**: Users can register, log in, log out, and reset passwords.
- **JWT Authentication**: Protect API endpoints using JSON Web Tokens.
- **CRUD Functionality**: Perform CRUD operations on the provided models (e.g., posts, users).
- **Pagination**: Data is paginated for better performance and UX.
- **Email Notifications**: Users receive a welcome email upon registration.

## Technologies Used

- **Backend**: Django 4.x, Django REST Framework
- **Frontend**: HTML, CSS, JavaScript 
- **Database**:  SQLite 
- **Authentication**: JWT Authentication using `djangorestframework-simplejwt`
- **Pagination**: Django REST Framework's built-in pagination system
- **Email**: Django's email system for sending notifications

## Setup and Installation

### Prerequisites

Before running this project, ensure that you have the following installed on your local machine:
- Python 3.x
- Django
- MySQL/PostgreSQL/SQLite
- Git

### Installation Steps

1. **Clone the repository:**
  (https://github.com/parulantil2/Django-Login-System.git)

## Usage

### Authentication

- **Register**: Visit `/register/` to create a new user.
- **Login**: Use `/login/` to log in with credentials.
- **JWT Authentication**: 
  - Obtain a JWT token by accessing `/api/token/`.
  - Refresh the JWT token by accessing `/api/token/refresh/`.

### CRUD Operations

- **Create**: Use the appropriate form or API endpoint to create a new resource.
- **Read**: View details or lists of resources with pagination.
- **Update**: Edit existing resources.
- **Delete**: Remove resources.

### Pagination

- Lists are paginated to show a limited number of results per page. You can navigate through pages using the provided controls or API pagination.

## API Documentation

The following API endpoints are available:

### Authentication

- `/api/token/`: Obtain a JWT token.
- `/api/token/refresh/`: Refresh the JWT token.
- `/api/token/verify/`: Verify the JWT token.

### CRUD Operations

- `/users/`: List all items (paginated).
- `/users/<int:pk>/`: Retrieve, update, or delete a specific item.

### Email Notifications

- After registering, users will receive an email confirming their registration.


