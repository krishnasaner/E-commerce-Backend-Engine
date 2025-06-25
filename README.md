# E-Commerce Backend System

A RESTful API backend for an e-commerce shopping cart system, designed with scalability, modularity, and real-world functionality in mind. Built using Flask or Django, this backend supports user registration, authentication, product listings, cart management, order processing, and admin operations.

## Overview

This backend engine powers the core functionality of a shopping platform, handling user accounts, product catalogs, cart operations, and order workflows. The system is structured to support role-based access (admin/user), clean API documentation, and database integration with PostgreSQL or SQLite.

## Key Features

- **User Management**
  - Registration, login, logout
  - JWT or session-based authentication
  - Profile and address management

- **Product Catalog**
  - CRUD operations for products (admin-only)
  - Categories, descriptions, prices, stock management
  - Pagination and filtering support

- **Shopping Cart System**
  - Add/remove items from cart
  - Quantity updates
  - Cart persistence per user

- **Order Management**
  - Create and track orders
  - Status updates (pending, shipped, delivered)
  - Inventory deduction and validation

- **Admin Panel**
  - Product and order management
  - User and analytics dashboard (optional with Django admin or custom routes)

## Tech Stack

| Layer            | Technology Used         |
|------------------|--------------------------|
| Backend Framework | Flask / Django (REST framework) |
| Database          | PostgreSQL / SQLite      |
| Authentication    | JWT / Session Auth       |
| API Format        | RESTful (JSON responses) |
| ORM               | SQLAlchemy / Django ORM  |
| Testing           | Pytest / Django TestCase |
| Documentation     | Swagger / Postman        |



