# Job Board API

This is a simple job board API built with Node.js, Express, and MongoDB. It allows users to create, read, and manage job listings.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [License](#license)

## Features

- Create new job listings
- Retrieve all job listings
- Retrieve a single job listing by ID
- Validate required fields for job creation

## Technologies Used

- Node.js
- Express
- MongoDB
- Mongoose
- dotenv
- cors

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/job-board-api.git
   cd job-board-api
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your MongoDB URI:
   ```plaintext
   MONGODB_URI=your_mongodb_uri
   PORT=5000
   ```

## Usage

1. Start the server:
   ```bash
   npm start
   ```

2. The server will run on `http://localhost:5000`.

Note: add your MongoURL in the .env

## API Endpoints

- **GET** `/api/jobs` - Retrieve all job listings
- **GET** `/api/jobs/:id` - Retrieve a single job listing by ID
- **POST** `/api/jobs` - Create a new job listing

### Example Request

To create a new job listing, send a POST request to `/api/jobs` with the following JSON body:

## Environment Variables

- `MONGODB_URI`: Your MongoDB connection string.
- `PORT`: The port on which the server will run (default is 5000).

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.