# video-games-api

# video-games-api
Video Games REST API

A scalable RESTful API built with Node.js, Express, and MongoDB, designed to manage video game data with authentication, advanced querying, and clean architecture principles.

Features

User authentication & authorization (JWT)
Full CRUD operations for video games
Advanced filtering, sorting, and pagination
Aggregation endpoints (e.g., top-rated games, statistics)
MVC architecture for maintainable code structure
Centralized error handling and middleware

Tech Stack

Backend: Node.js, Express
Database: MongoDB (Mongoose)
Authentication: JWT, bcrypt
Architecture: MVC
Tools: Postman, Nodemon

API Features
Game Endpoints

GET /api/v1/games → Get all games (with filtering, sorting, pagination)
GET /api/v1/games/:id → Get single game
POST /api/v1/games → Create game
PATCH /api/v1/games/:id → Update game
DELETE /api/v1/games/:id → Delete game

Advanced Queries

Filter by fields (genre, rating, etc.)
Sort results dynamically
Limit fields returned
Paginate large datasets

Auth Endpoints

POST /api/v1/users/signup
POST /api/v1/users/login
Protected routes using JWT middleware

Project Structure
controllers/    → Route logic (games, users)
models/         → Mongoose schemas
routes/         → API route definitions
utils/          → Error handling & helpers
middleware/     → Authentication & global error ha
