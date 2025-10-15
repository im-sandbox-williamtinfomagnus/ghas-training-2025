# GHAS Training 2025 - Node.js Project

A simple Node.js application built with Express.js for GitHub Advanced Security (GHAS) training purposes.

## Features

- Express.js web server
- RESTful API endpoints
- Health check endpoint
- Static file serving
- Error handling middleware

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

### Development
```bash
npm run dev
```

### Production
```bash
npm start
```

The server will start on port 3000 by default. You can change this by setting the `PORT` environment variable.

## API Endpoints

- `GET /` - Welcome message
- `GET /api/health` - Health check endpoint
- `GET /api/users/:id` - Get user by ID

## Project Structure

```
├── package.json       # Project configuration and dependencies
├── index.js          # Main application file
├── public/           # Static files (to be created)
└── README.md         # This file
```

## License

MIT