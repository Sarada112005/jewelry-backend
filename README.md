# Jewelry Backend API

## Project Overview
This project is a Jewelry Backend API developed using Django REST Framework.

## Features
- Product CRUD APIs
- Category APIs
- Products by Category
- Price Filter
- Base Metal Filter
- Product Sorting
- Django Admin Panel
- SQLite Database
- JWT Authentication

## Technologies
- Python
- Django
- Django REST Framework
- SQLite
- Postman

## API Endpoints

### Products
GET /api/products/

GET /api/products/<id>/

POST /api/products/

PUT /api/products/<id>/

DELETE /api/products/<id>/

### Categories
GET /api/categories/

GET /api/categories/<id>/products/

### Filters
GET /api/products/?min_price=1000&max_price=5000

GET /api/products/?metal=gold

GET /api/products/?sort=latest

### Authentication
POST /api/login/

POST /api/refresh/