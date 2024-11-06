 # E-comerce-project
use - Html, Css ,JavaScript
https://e-commerce-project-rs.netlify.app/
The e-commerce frontend features a responsive design, intuitive navigation, quick add-to-cart functionality and high-quality images.

## Features

- [ ] **Modern UI/UX**: Intuitive, responsive design for a seamless shopping experience.
- [ ] **Product Management**: Admin interface for adding, updating, and removing products.
- [x] **User Authentication**: Secure user registration, login, and JWT-based authentication.
- [ ] **Search and Filters**: Search for products and apply filters based on categories, prices, and more.
- [ ] **Shopping Cart**: Add, update, or remove items from the cart, with real-time calculations.
- [ ] **Checkout Process**: Easy and secure checkout experience.
- [x] **Responsive Design**: Optimized for all devices (mobile, tablet, and desktop).

## Tech Stack

ScrollMe is built using the following technologies:

### Frontend
- **Html
- **CSS
- **JavaScript (ES6+)**: Core language for building dynamic features.

-   
## Installation

To get started with website locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone 
   cd 
   ```
2. **Install dependencies for both frontend and backend**:
   ```bash
   # Install frontend dependencies
   npm install

   # Install backend dependencies
   cd ./backend
   npm install
   ```
3. **Set up environment variables**:  
   In the `backend` directory, we have a `.env.example` file. You can create your own `.env` file by copying this file and adding the necessary environment variables:
   
   ```bash
   cp backend/.env.example backend/.env
   ```
4. **Start the development server**:
   ```bash
   # Start the backend
   cd backend
   npm run start

   # Start the frontend
   npm start
   ```

5. **Visit the app in your browser**:  
   Open `http://localhost:3000` to view the application.


## Usage

Once the project is set up, you can:

- Browse products, add items to the cart, and proceed to checkout.
- Register or log in to track your orders.
- Admins can manage products and orders through the admin dashboard.

## Contributing

We welcome contributions from the community! To contribute to ScrollMe, follow these steps:

1. **Fork the repository** on GitHub.
2. **Checkout the `develop` branch**

```bash
   git checkout develop
```

3. **Install dependencies**
   Run the following command to install project dependencies:

 ```bash
   # Install frontend dependencies
   cd frontend
   npm install

   # Install backend dependencies
   cd ../backend
   npm install
```

4. **Create a branch** for your feature or bugfix

   ```bash
   git checkout -b feature-name
   ```

5. **Commit your changes**

   ```bash
   git commit -m "Add feature-name"
   ```

6. **Push to your fork**

   ```bash
   git push origin feature-name
   ```


