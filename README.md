# Desi Drape Store

A small MERN-style Indian clothes e-commerce demo built in plain JavaScript.

## What it does

- Browse Indian clothing products
- Filter by category and search by name
- Add items to cart with size selection
- Place a demo order through an Express API
- Store products and orders in MongoDB when configured, with a local demo fallback if MongoDB is not connected

## Project structure

- `client` - React app built with Vite
- `server` - Express API with MongoDB models
- `docs` - SRS, demo notes, and implementation references

## Quick start

1. Install dependencies at the repository root.
2. Create `server/.env` from `server/.env.example`.
3. Create `client/.env` from `client/.env.example` if you want to override the API URL.
4. Run the app in development mode.

```bash
npm install
npm run dev
```

## Demo flow

1. Open the home page and explain the brand idea.
2. Show the product list and category filters.
3. Add one or two items to the cart.
4. Open checkout and place an order.
5. Show the order success screen and explain the backend flow.

## Notes

- The frontend uses React with JavaScript only.
- The backend uses Express and Mongoose.
- If MongoDB is not available, the API falls back to in-memory demo data so the UI still works.

