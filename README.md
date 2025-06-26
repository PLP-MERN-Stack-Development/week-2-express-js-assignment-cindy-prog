# Express.js REST API

## 📦 Setup
1. Install dependencies:
2. Copy `.env.example` to `.env` and set your API key.
3. Run development server:

## 📌 API Endpoints

### Get All Products  
`GET /api/products`
### Get a specified product
`GET /api/products:id`
**Query Parameters**
- `category`
- `page`
- `limit`

### Search Products  
`GET /api/products/search?name=`

### Get Stats  
`GET /api/products/stats`

...

## 📌 Authentication
All endpoints require `x-api-key` header.

