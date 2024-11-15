# Real Estate Marketplace API

A Real Estate Marketplace API built using Node.js.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Dependencies](#dependencies)

## Introduction
This repository contains the code for a Real Estate Marketplace API, which serves as the backend service for managing real estate listings, user authentication, and more.

## Features
- User authentication and authorization
- CRUD operations for real estate listings
- Middleware for security, compression, and rate limiting

## Installation
To get started with this project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/GantalaAvinash/Real_Estate-API.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Real_Estate-API
    ```

3. Install the dependencies:
    ```sh
    npm install
    ```

4. Create a `.env` file in the root directory and add the following environment variables:
    ```env
    DATABASE=<your-mongodb-connection-string>
    ```

5. Start the server:
    ```sh
    npm start
    ```

## Usage
Once the server is running, you can access the API at `http://localhost:8000`. The server includes various endpoints for managing users and real estate listings.

## API Endpoints
Here are some of the main API endpoints:

- **Auth Routes**: Located in `./routes/auth.js`
- **Ad Routes**: Located in `./routes/ad.js`

### Example Endpoints
- `POST /api/register` - Register a new user
- `POST /api/login` - Login a user
- `GET /api/ads` - Get all real estate listings
- `POST /api/ads` - Create a new real estate listing

## Dependencies
The project uses the following dependencies:

- `@aws-sdk/client-s3`
- `@aws-sdk/client-ses`
- `compression`
- `cors`
- `dotenv`
- `email-validator`
- `express`
- `express-rate-limit`
- `helmet`
- `jsonwebtoken`
- `mongoose`
- `morgan`
- `multer`
- `nanoid`
- `node-geocoder`
- `nodemon`
- `sharp`
- `slugify`

---