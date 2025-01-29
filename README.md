

## Overview

FurniCraft is a project aimed at creating an efficient and user-friendly online furniture store. It utilizes various technologies to provide a seamless experience for users browsing through furniture products, managing their cart items, and placing orders. The project incorporates features such as user authentication, product filtering, pagination, error handling, and more.



## Project Structure

```
README.md
src
├── App.jsx
├── assets
│   ├── 404not.svg
│   ├── hero1.webp
│   ├── hero2.webp
│   ├── hero3.webp
│   ├── hero4.webp
│   └── Warning.svg
│
├── components
│   ├── CartItem.jsx
│   ├── CartItemsList.jsx
│   ├── CartTotals.jsx
│   ├── CheckoutForm.jsx
│   ├── ErrorElement.jsx
│   ├── FeaturedProducts.jsx
│   ├── Filters.jsx
│   ├── FormCheckBox.jsx
│   ├── FormInput.jsx
│   ├── FormRange.jsx
│   ├── FormSelect.jsx
│   ├── Header.jsx
│   ├── Hero.jsx
│   ├── index.js
│   ├── Loading.jsx
│   ├── Navbar.jsx
│   ├── NavLinks.jsx
│   ├── OrderList.jsx
│   ├── OrderPaginationContainer.jsx
│   ├── PaginationContainer.jsx
│   ├── ProductsContainer.jsx
│   ├── ProductsGrid.jsx
│   ├── ProductsList.jsx
│   ├── SectionTitle.jsx
│   └── SubmitBtn.jsx
│
├── features
│   ├── cart
│   │   └── cartSlice.js
│   └── user
│       └── userSlice.js
│
├── pages
│   ├── About.jsx
│   ├── Cart.jsx
│   ├── Cart.jsx
│   ├── Checkout.jsx
│   ├── Error.jsx
│   ├── HomeLayout.jsx
│   ├── index.js
│   ├── Landing.jsx
│   ├── Login.jsx
│   ├── Orders.jsx
│   ├── Products.jsx
│   ├── Register.jsx
│   └── SingleProduct.jsx
│
├── index.css
├── main.jsx
├── store.js
└── utils

```

## Features

- User authentication (login, logout, register)
- Easy navigation between pages
- Clear error pages for handling errors
- Global loading indicator for API requests
- Featured products showcased on the landing page
- Product filtering by company, type, free shipping, and price
- Search functionality to find specific products
- Pagination for both product and order pages
- Notifications for various actions such as login/logout
- CRUD operations for cart items
- Checkout page for users to finalize their orders
- Order page for users to view all their past orders


## Technologies Used

- React
- Redux Toolkit
- React Query
- React Router DOM
- Axios
- Dayjs
- React Icons
- React Toastify
- Tailwind CSS
- DaisyUI
- Vite

## Contact


## How to Run FurniCraft Locally

1. **Clone the Repository**: 

2. **Install Dependencies**: 
   Navigate to the project directory and install the required dependencies using npm or yarn:
   ```sh
   cd FurniCraft-React_Redux
   npm install
   ```
   or
   ```sh
   yarn install
   ```

3. **Start the Development Server**: 
   After installing the dependencies, start the development server using npm or yarn:
   ```sh
   npm start
   ```
   or
   ```sh
   yarn start
   ```

4. **Access the Application**: 
   Once the server starts successfully, you can access the application by opening your web browser and navigating to `http://localhost:3000/`.

5. **Explore the Application**: 
   You can now explore the FurniCraft application locally. Feel free to interact with different features and functionalities.

6. **Optional Configuration**:
   - If you want to make changes to the API endpoint or any other configurations, you can do so by modifying the relevant files in the project directory.
   - You may need to configure environment variables if required.
