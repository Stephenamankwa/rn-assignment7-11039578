# rn-assignment7-11039578

# Product Management App

## Overview
This project is a mobile application designed to manage products and allow users to interact with a product list. Users can view a list of products fetched from an external API, preview detailed information about each product, add products to their cart, and remove them if desired. The cart items are stored locally on the device.

## Features
- **HomeScreen**: Displays a list of available products.
- **ProductDetailScreen**: Shows detailed information about a selected product.
- **CartScreen**: Displays selected items that have been added to the cart.
- **Drawer/Navigation Menu**: Accessible through a swipe gesture or a button for easy navigation.
- **Add to Cart**: Button to add products to the cart from the product list or detail view.
- **Remove from Cart**: Button to remove products from the cart in the cart view.

## Technologies Used
- **React Native**: For building the mobile application.
- **React Navigation**: For handling navigation and drawer component.
- **Fetch or Axios**: For making API requests.
- **AsyncStorage, SecureStore, or FileSystem**: For storing selected items locally on the device.
- **Async/Await or Promises**: For managing asynchronous operations.

## Usage

### HomeScreen
- Displays a list of products fetched from the ex
ternal API.
- Each product has an "Add to Cart" button to add the product to the cart.

### ProductDetailScreen
- Shows detailed information about a product when a product is selected from the HomeScreen.
- Includes an "Add to Cart" button to add the product to the cart.

### CartScreen
- Displays the list of products added to the cart.
- Each item in the cart has a "Remove from Cart" button to remove the item from the cart.

### Drawer/Navigation Menu
- Accessible through a swipe gesture or a button.
- Allows easy navigation between HomeScreen, ProductDetailScreen, and CartScreen.

## Data Fetching
- The app fetches product data from an external API using `fetch` or `axios`.
- Asynchronous operations are managed with `async/await` or promises.

## Local Storage
- The app uses `AsyncStorage`, `SecureStore`, or `FileSystem` to store selected items locally on the device.
- This allows users to retain their cart items even after closing the app.

## Functionalit

- **View Products**: Users can view a list of available products from the external API.
- **Product Details**: Users can preview detailed information about a product.
- **Add to Cart**: Users can add products to their cart from both the HomeScreen and ProductDetailScreen.
- **Remove from Cart**: Users can remove products from their cart in the CartScreen.
- **View Cart**: Users can view the items in their cart
![WhatsApp Image 2024-07-12 at 21 37 32_1a036ac6](https://github.com/user-attachments/assets/039f426a-d59d-4c2a-ae19-74282b24b705)

![WhatsApp Image 2024-07-12 at 21 37 27_ab1f668e](https://github.com/user-attachments/assets/73c45b49-2109-4d00-9f50-49acee23190e)
684152)
![WhatsApp Image 2024-07-12 at 21 38 05_ab28d30d](https://github.com/user-attachments/assets/8eeec91e-2d1a-4f2f-b0d9-f8d9ab6e02b2)

![6](https://github.com/user-attachments/assets/f9f8d5f0-7d96-4d32-beed-a2b4989d7ad4)


  
