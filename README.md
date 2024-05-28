# E-Commerce Website

## Overview

This repository contains the source code for a fully functional e-commerce website built using HTML, CSS, ReactJS, and the MERN stack (MongoDB, Express, React, Node.js). The application features a modern front-end design, efficient back-end architecture, and allows users to add and manage their own products.

## Features

- **User Authentication**: Secure user registration and login functionality using JWT.
- **Product Management**: Users can add, update, and delete their own products.
- **Product Listing**: Display all products with search and filter capabilities.
- **Product Details**: View detailed information about each product.
- **Shopping Cart**: Add products to a shopping cart and manage the cart.
- **Checkout Process**: Simulated checkout process for demonstration.
- **Responsive Design**: Fully responsive layout for an optimal viewing experience on all devices.

## Technologies Used

### Front-End

- **HTML**: For structuring the web pages.
- **CSS**: For styling the application and ensuring a responsive design.
- **ReactJS**: For building the user interface and managing state.

### Back-End

- **Node.js**: For the server-side environment.
- **Express.js**: For creating the RESTful APIs.
- **MongoDB**: For the database to store user and product information.
- **Mongoose**: For object data modeling (ODM) to interact with MongoDB.

## Getting Started

### Prerequisites

- Node.js
- MongoDB
- npm or yarn

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/ecommerce-website.git
    cd ecommerce-website
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up environment variables**: Create a `.env` file in the root directory and add the following:
    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

4. **Run the application**:
    ```bash
    npm run dev
    ```

### Folder Structure

- **client**: Contains the front-end React application.
- **server**: Contains the back-end Express server and MongoDB connection.

### Scripts

- `npm run dev`: Starts both the client and server concurrently.
- `npm run client`: Starts only the React client.
- `npm run server`: Starts only the Express server.

## Usage

- **Register/Login**: Create a new account or log in with existing credentials.
- **Add Products**: Navigate to the 'Add Product' section to add new products.
- **Manage Products**: View, edit, or delete your products from the 'My Products' section.
- **Shop**: Browse the product catalog, add items to the cart, and proceed to checkout.

## Contributions

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, please open an issue or contact me at [utkarshsingh954@gmail.com].
