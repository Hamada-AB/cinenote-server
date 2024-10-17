# CineNote Server

CineNote Server is the backend of the CineNote application, providing a RESTful API to manage movie data and handle user authentication.

## Overview

CineNote is designed to be a personal movie address book where users can log and manage their favorite movies. The server handles user authentication and movie management requests.

## Features

- **User Authentication:** Secure signup and login using JWT and bcrypt.
- **Movie Management:** Users can add and delete movies in the database.
- **Database Management:** Uses Prisma as an ORM to interact with a PostgreSQL database.

## Technologies Used

- **Backend:**
  - Express.js: For building the RESTful API
  - Prisma: As the ORM for database management
  - PostgreSQL: For the relational database
  - JWT (JSON Web Tokens): For secure user authentication
  - bcrypt: For hashing passwords

## Installation

### Prerequisites

- Node.js and npm installed on your machine.

### Steps

1. **Fork the repository:**

   Click the "Fork" button at the top right corner of the repository page to create your own copy.

2. **Clone the forked repository:**

   ```bash
   git clone <your-forked-repository-url>
   ```

3. **Navigate to the project directory.**

4. **Install dependencies:**

   ```bash
   npm install
   ```

5. **Set Up Environment Variables:**

   ```bash
   # In .env file
   DATABASE_URL=your_postgresql_database_url
   JWT_SECRET=your_jwt_secret_key
   ```

6. **Run the database migrations:**

   ```bash
   npx prisma migrate deploy
   ```

7. **Start the server:**

   ```bash
   npm start
   ```

## Contact

For any questions or feedback, please contact [Hamada](https://hmad.netlify.app/).
