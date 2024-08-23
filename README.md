# E-Commerce-Back-End

## Description

This project is a back end for an e-commerce website that leverages the latest technologies to provide a robust and scalable solution for managing product data, categories, and tags. The application is built using Node.js with an Express.js API and integrates with a PostgreSQL database via Sequelize ORM. This setup allows your company to efficiently manage its e-commerce platform and stay competitive in the market.

## User Story

**AS** a manager at an internet retail company  
**I WANT** a back end for my e-commerce website that uses the latest technologies  
**SO THAT** my company can compete with other e-commerce companies

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd e-commerce-backend
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Create a `.env` file in the root directory and add your PostgreSQL credentials:
   ```env
   DB_NAME=your_database_name
   DB_USER=your_postgresql_username
   DB_PASSWORD=your_postgresql_password
   DB_HOST=localhost
   DB_DIALECT=postgres
   ```
5. Set up the database by running the schema and seed commands:
   ```bash
   npm run schema
   npm run seed
   ```

## Usage

1. Start the server:
   ```bash
   npm start
   ```
2. Use Insomnia Core or another API client to interact with the API endpoints.

## API Endpoints

- **GET** `/api/categories` - Retrieve all categories
- **GET** `/api/products` - Retrieve all products
- **GET** `/api/tags` - Retrieve all tags
- **POST** `/api/categories` - Create a new category
- **POST** `/api/products` - Create a new product
- **POST** `/api/tags` - Create a new tag
- **PUT** `/api/categories/:id` - Update a category by ID
- **PUT** `/api/products/:id` - Update a product by ID
- **PUT** `/api/tags/:id` - Update a tag by ID
- **DELETE** `/api/categories/:id` - Delete a category by ID
- **DELETE** `/api/products/:id` - Delete a product by ID
- **DELETE** `/api/tags/:id` - Delete a tag by ID

## Technologies Used

- Node.js
- Express.js
- PostgreSQL
- Sequelize
- Insomnia Core (for API testing)

## Acknowledgements

This project was created as part of a learning exercise and may contain simplistic implementations.
