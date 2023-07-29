# Django Book API

Django Book API is a RESTful web API built using Django and Django REST Framework (DRF) to manage book data.

## Installation

1. Clone the repository:

  
   git clone https://github.com/M0d3v1/Random-Book-API.git)https://github.com/M0d3v1/Random-Book-API.git
Navigate to the project directory:
cd django-book-api
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
Run the development server:
python manage.py runserver
Access the Django admin interface:

Navigate to http://127.0.0.1:8000/admin/ in your web browser. Log in with the superuser credentials created earlier to manage book data through the admin interface.

Access the API endpoints:

To view all books: http://127.0.0.1:8000/api/books/
To view a specific book (by primary key, e.g., 1): http://127.0.0.1:8000/api/books/1/
To filter books by author (e.g., "Author 1"): http://127.0.0.1:8000/api/books/?author=Author%201
API Endpoints
GET /api/books/: Retrieve a list of all books.
GET /api/books/{id}/: Retrieve a specific book by its primary key.
POST /api/books/: Create a new book.
PUT /api/books/{id}/: Update a specific book by its primary key.
DELETE /api/books/{id}/: Delete a specific book by its primary key.
Contributing
Contributions are welcome! If you find any issues or want to add new features, feel free to submit a pull request.
