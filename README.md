
# Responsive E-commerce Platform

## Table of Contents
2. [Technologies Used](#technologies-used)
3. [Features](#features)
4. [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
5. [State Management](#state-management)
6. [Form Handling and Validation](#form-handling-and-validation)
7. [Responsive Design](#responsive-design)
8. [Folder Structure](#folder-structure)

## Project Overview
This project is a responsive e-commerce platform built using **HTML, CSS, JavaScript, Tailwind CSS, React.js, Redux Toolkit, Formik, and Yup**. The platform features a landing page, product listings, detailed product pages, a shopping cart, a multi-step checkout process, an order history page, and an admin panel for managing products and user accounts.

The goal is to provide users with a seamless and intuitive shopping experience, allowing admins to efficiently manage the platform's product offerings and user base.

## Technologies Used
- **Frontend**: React.js, Tailwind CSS, HTML, JavaScript, CSS
- **State Management**: Redux Toolkit
- **Form Handling**: Formik
- **Form Validation**: Yup
- **API Integration**: RapidAPI
- **Build Tool**: Vite
- **Styling**: Tailwind CSS for modern and responsive UI design


## Features
- **Landing Page**: A visually appealing homepage to showcase featured products.
- **Product Listings**: Browse and filter through products.
- **Product Detail Pages**: Detailed view of each product, including pricing and descriptions.
- **Shopping Cart**: Add, update, or remove items from the cart.
- **Admin Panel**: Admin access to manage products and user accounts (Create, Read, Update, Delete - CRUD).
- **Fully Responsive**: Adaptable design across all device sizes.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/e-commerce-platform.git
    cd e-commerce-platform
    ```

2. Install the dependencies:
    ```bash
    npm install
    # or
    yarn install
    ```

3. Start the development server:
    ```bash
    npm run dev
    # or
    yarn dev
    ```

4. Open your browser and navigate to:
    ```
    http://localhost:3000
    ```
## State Management
We use **Redux Toolkit** for managing the global state of the application. Key states include:
- **Products**: For listing products, filtering, and sorting.
- **Cart**: For adding, updating, and removing products.
- **Orders**: For storing order information and tracking order history.
- **Admin**: Manage CRUD operations for products and users.
