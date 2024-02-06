# ProShop (Under Development)

Welcome to our MERN stack ecommerce application! This application allows users to browse products, add them to their cart, and make purchases. It also provides an admin interface for managing products and orders.

## Features

- **User Authentication**: Users can sign up, log in, and log out securely.
- **Product Browsing**: Users can view available products and their details.
- **Shopping Cart**: Users can add products to their cart and proceed to checkout.
- **Admin Interface**: Admins can add, update, and delete products. They can also view and manage orders.
- **Responsive Design**: The application is designed to work seamlessly across different devices and screen sizes.

## Technologies Used

- **MongoDB**: NoSQL database used for storing product and user information.
- **Express.js**: Backend framework for handling server-side logic and routing.
- **React.js**: Frontend library for building user interfaces.
- **Node.js**: JavaScript runtime environment for running server-side code.
- **Redux**: State management library for managing application state.
- **JWT Authentication**: JSON Web Tokens used for user authentication and authorization.
- **Bootstrap**: Frontend framework for responsive design and UI components.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   npm install
   cd frontend
   npm install
   ```

2. **Run the application**:
   ```bash
    # Run frontend (:3000) & backend (:5000)
    npm run dev
    
    # Run backend only
    npm run server
   ```
   
3. **Create an .env file in the root directory of the project**:
    ```bash
    PORT=5000
    MONGO_URI=<your_mongo_db_uri>
    JWT_SECRET=<your_secret>
    PAYPAL_CLIENT_ID=<your_paypal_client_id>
    PAYPAL_APP_SECRET=<your_paypal_secret>
    PAYPAL_API_URL=https://api-m.sandbox.paypal.com
   ```

<img width="990" alt="screens" src="https://github.com/ashwaniMaddheshiya/ProShop/assets/98683284/c116248e-7126-4829-84da-ee8532222b6e">
