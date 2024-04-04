# Paginated API using Node.js, Express, and Mongoose

This is a simple example of how to create a paginated API using Node.js, Express, and Mongoose.

## Requirements

- Node.js
- npm (Node Package Manager)
- MongoDB

## Installation

1. Clone this repository:
https://github.com/swapnildubey29/Paginated-Api-Express/


2. Install dependencies:
npm -y init


## Usage

The API provides endpoints for paginated retrieval of data. You can interact with these endpoints using HTTP requests.

### Endpoints

- `GET /api/items`: Retrieve a paginated list of items.

#### Query Parameters

- `page`: Page number (default: 1)
- `limit`: Number of items per page (default: 10)

Example request:

Example response:

```json
{
  "page": 1,
  "limit": 10,
  "totalPages": 3,
  "totalItems": 25,
  "items": [...]
}
