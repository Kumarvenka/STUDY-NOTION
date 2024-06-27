---

# E-Commerce React Application

This project is a responsive e-commerce web application built using React, Redux, and several other modern web technologies. The app allows users to browse products, add them to their cart, and manage their cart items. 

## Features

- *Product Listing*: Fetches and displays a list of products from the FakeStore API.
- *Product Details*: Displays key details of each product, including the title, description, image, and price.
- *Cart Management*: Users can add products to their cart, view the items in the cart, and remove items. The cart state is managed globally using Redux.
- *Toast Notifications*: Utilizes react-hot-toast to show notifications for actions like adding or removing items from the cart.
- *Routing*: Implements client-side routing using react-router-dom for smooth navigation between the Home and Cart pages.
- *Loading Spinner*: Displays a loading spinner while data is being fetched.

## Technologies Used

- *React*: For building the user interface.
- *Redux*: For state management.
- *React Router*: For handling client-side routing.
- *React Hot Toast*: For displaying toast notifications.
- *FakeStore API*: For fetching product data.
- *Tailwind CSS*: For styling the application.

## Project Structure

The project is structured as follows:

- *index.js*: Entry point of the application. Sets up the Redux store, routing, and renders the main App component.
- *App.jsx*: Main component that includes the Navbar and sets up the routes for the Home and Cart pages.
- *Navbar.jsx*: Contains the navigation bar with links to the Home and Cart pages. Shows the number of items in the cart.
- *Home.jsx*: Fetches and displays a grid of products. Shows a loading spinner while data is being fetched.
- *Cart.jsx*: Displays the items in the cart and the total amount. Allows users to proceed to checkout or remove items from the cart.
- *CartItem.jsx*: Represents an individual item in the cart with options to remove it.
- *Product.jsx*: Represents an individual product with options to add it to the cart or remove it if already added.
- *Spinner.jsx*: A simple loading spinner component.
- *redux/Store.js*: Configures the Redux store.
- *redux/Slices/cartSlice.js*: Defines the cart slice with actions to add and remove items from the cart.

## To Run the Project

To run this project locally:

1. Clone the repository.
2. Install dependencies with npm install.
3. Start the development server with npm start.

--
