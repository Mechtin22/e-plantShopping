# e-plantShopping
# Paradise Nursery

Paradise Nursery is a React-based online plant shopping application where users can browse houseplants, add plants to a shopping cart, manage quantities, and view their total cart amount.

## Project Overview

The application provides a simple and interactive shopping experience for plant enthusiasts.

Users can:

- View the Paradise Nursery landing page
- Learn about the company through the About Us section
- Browse different categories of houseplants
- View plant names, images, and prices
- Add plants to the shopping cart
- Increase or decrease plant quantities
- Remove plants from the cart
- View the total cart amount
- Continue shopping
- Access a checkout option marked as coming soon

## Technologies Used

- React.js
- JavaScript (ES6)
- JSX
- CSS
- Redux Toolkit
- React Redux
- Vite

## Main Features

### Landing Page
The landing page displays:

- Paradise Nursery branding
- "Where Green Meets Serenity" tagline
- Background nursery image
- Get Started button
- About Us information

### Product Listing

The product listing contains multiple categories of houseplants, including:

- Air Purifying Plants
- Aromatic Plants
- Insect Repellent Plants
- Medicinal Plants
- Low Maintenance Plants

Each category contains at least six plants with:

- Plant image
- Plant name
- Price
- Add to Cart button

### Shopping Cart

The shopping cart allows users to:

- View selected plants
- View individual plant prices
- Increase plant quantity
- Decrease plant quantity
- Remove plants
- View the total cost of each plant
- View the total cart amount
- Continue shopping
- Access the checkout option

## State Management

Redux Toolkit is used to manage the shopping cart state.

The cart stores:

- Product information
- Product ID
- Product name
- Product image
- Product price
- Product quantity

The cart count in the navigation bar updates dynamically according to the number of items in the cart.

## Project Structure

```text
e-plantShopping/
│
├── src/
│   ├── App.jsx
│   ├── App.css
│   ├── AboutUs.jsx
│   ├── CartItem.jsx
│   ├── CartItem.css
│   ├── CartSlice.jsx
│   ├── ProductList.jsx
│   ├── ProductList.css
│   ├── store.js
│   ├── main.jsx
│   └── index.css
│
├── public/
│
├── package.json
├── package-lock.json
└── README.md
