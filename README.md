# Hackathon_FindMyResturent2023
This project aims to develop the backend of a real-world application in Node.js, Express.js and MongoDB.

# Find My Restaurant Backend

This is the backend of the Find My Restaurant application, developed using Node.js, Express.js, and MongoDB.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [API Endpoints](#api-endpoints)
- [Database Schema](#database-schema)
- [HTTP Status Codes](#http-status-codes)
- [Version Control](#version-control)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed
- MongoDB installed and running
- Git for version control

### Installation

1. Clone this repository:

   ```bash
   git clone <repository-url>


Install dependencies:
npm install

Configure environment variables:
MONGODB_URI=<your-mongodb-uri>

Start the server:npm start


API Endpoints
POST /api/restaurants: Add details of a new restaurant.
GET /api/restaurants: List down all restaurants present in the locality.
GET /api/restaurants/categories: Find different categories of restaurants.
GET /api/restaurants/category/:categoryName: Find restaurants based on their categories.
GET /api/restaurants/:restaurantId: Find a particular restaurant.
GET /api/restaurants/rating/:minRating: Find restaurants based on their ratings.
PUT /api/restaurants/:restaurantId: Update details of a particular restaurant.
DELETE /api/restaurants/:restaurantId: Delete a restaurant.
DELETE /api/restaurants: Delete all restaurants.

Database Schema
The restaurant schema consists of the following fields:

name: STRING
description: STRING
category: STRING
imageURL: STRING
location: STRING
phone: STRING
rating: Number

HTTP Status Codes
HTTP Status OK (200): Used for successful responses.
HTTP Bad Request (400): Used for invalid syntax or internal errors.

Version Control
Commit often and make small, incremental commits.
Write clear and descriptive commit messages.
Ensure your code works before committing it.


Contributing
Contributions are welcome! Fork the repository and create a pull request with your improvements.
