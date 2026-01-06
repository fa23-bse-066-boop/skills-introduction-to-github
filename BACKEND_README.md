# Web Backend

A simple Node.js Express backend server with basic API endpoints.

## Features

- RESTful API endpoints
- JSON response format
- Health check endpoint
- Basic server setup

## Installation

```bash
npm install
```

## Running the Server

```bash
npm start
```

The server will start on port 3000 (or the PORT environment variable if set).

## API Endpoints

- `GET /` - Welcome message with server status
- `GET /health` - Health check endpoint
- `GET /api/info` - API information

## Example Usage

```bash
# Start the server
npm start

# Test the API (in another terminal)
curl http://localhost:3000/
curl http://localhost:3000/health
curl http://localhost:3000/api/info
```
