# ProductManager

Spring Boot application for managing products.

Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
- [Endpoints](#endpoints)

## Introduction
The Product Manager Application provides functionalities to manage products effectively. It offers endpoints for retrieving, updating, and saving product details.

### Features
- Retrieve all products
- Retrieve individual product
- Add new products
- Update existing products
- Delete individual products
- Delete all products

## Setup
### Prerequisites
Before running the application, make sure you have the following installed:
- Java JDK
- MySQL
- Preferred IDE

### Installation
1. Clone this repository.
2. Configure MySQL database settings in `application.properties`.
3. Run the application.

## Endpoints
- `POST /api/product`: Add a new product
- `GET /api/products`: Retrieve all products
- `GET /api/product/{id}`: Retrieve a product by ID
- `PUT /api/product/{id}`: Update an existing product
- `DELETE /api/product/{id}`: Delete a product by ID
- `DELETE /api/products`: Delete all products