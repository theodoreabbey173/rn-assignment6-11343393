# User Information
- Name: Theodore Gyaqueh Abbey
- Student ID: 11343393

# Prerequisites
- Node.js
- npm or yarn
- React Native CLI

# Open Fashion App

## Overview

The Open Fashion app is a simple e-commerce application designed to allow users to browse and purchase items. The app includes the following key features:

- **HomeScreen**: Displays a list of available products.
- **CartScreen**: Displays selected items in the user's cart.
- **Add to Cart Button**: Allows users to add products to their cart.
- **Remove from Cart Button**: Allows users to remove products from their cart.

## Design Choices

### User Interface

- **Clean and Minimalistic Design**: The UI is designed to be simple and intuitive, focusing on usability and aesthetics.
- **Product List**: Displays products in a grid format, allowing users to easily browse through items.
- **Cart**: Displays selected items in a list format, making it easy for users to review their selections.

### Data Storage

- **Local Storage**: We use AsyncStorage to store selected items locally on the device. This ensures that the user's cart persists even if the app is closed or the device is restarted.

### Screenshots

Here are some screenshots of the app's main screens:

#### HomeScreen
![Home Screen](Screenshot/photo_1_2024-07-03_22-18-45.jpg)
![Home Screen](Screenshot/photo_2_2024-07-03_22-18-45.jpg)


## Implementation Details

### HomeScreen

The `HomeScreen` component fetches the list of available products and displays them in a grid format. Each product has an "Add to Cart" button.

### CartScreen

The `CartScreen` component fetches the items from AsyncStorage and displays them in a list. Each item has a "Remove from Cart" button.

### Navigation

We use React Navigation to navigate between the HomeScreen and CartScreen.

### Local Storage with AsyncStorage

AsyncStorage is used to store the cart items locally on the device. This ensures the cart persists across app sessions.


## Installation and Running the Application
1. **Clone the Repository**
   ```sh
   git clone https://github.com/theodoreabbey173/rn-assignment6-11343393.git