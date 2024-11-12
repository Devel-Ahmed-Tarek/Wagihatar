# Wagihatar - E-Commerce Platform for UI Designs

**[Demo](#)** | **[GitHub](#)**

## Project Overview

**Wagihatar** is an innovative e-commerce platform designed for selling UI designs, featuring a **multi-vendor** system that allows multiple designers to showcase and sell their digital products. Built with **Laravel 11**, the platform ensures a seamless and secure shopping experience for both vendors and customers, providing a user-friendly interface, secure payment gateways, and robust backend management.

The platform enables designers to create stores, upload their UI designs, and manage transactions, while customers can browse, purchase, and download high-quality UI design assets.

## Key Features

- **Multi-Vendor System**: Supports multiple vendors, allowing different designers to sell their UI designs on the platform.
- **Product Catalog**: Vendors can upload their UI designs, including images and descriptions, to be listed in the product catalog.
- **User Authentication**: Secure login and registration for customers and vendors, using **Laravel Sanctum** for API authentication.
- **Shopping Cart**: Customers can add UI designs to the cart, review their orders, and proceed to checkout.
- **Payment Integration**: Integrated payment gateways (e.g., Stripe, PayPal) to securely process transactions.
- **Order Management**: Vendors can manage orders, track sales, and handle customer interactions directly through an admin dashboard.
- **Search & Filters**: Customers can search for UI designs based on categories, tags, or price, and apply filters to refine results.
- **Reviews and Ratings**: Customers can leave reviews and ratings on products, helping other users make informed purchasing decisions.
- **Admin Dashboard**: A robust admin panel to manage users, products, orders, and overall platform settings.

## Technologies Used

- **Backend**:
  - **Laravel 11**: A powerful PHP framework used for building secure and scalable backend APIs and business logic.
  - **RESTful API**: Facilitates communication between the frontend mobile app and the backend, enabling smooth interaction with the platform.
  - **Authentication**: Utilized **Laravel Sanctum** for secure user authentication and token-based authorization.
  - **Database**: **MySQL** or **PostgreSQL** to store vendor, customer, product, and order data.
  - **Queue System**: For handling background tasks such as email notifications and order processing.

- **Frontend** (Mobile App):
  - **React Native** or **Flutter**: Mobile frameworks used to build cross-platform mobile applications for iOS and Android.
  - **JavaScript**: Used in combination with React Native or Flutter to build dynamic mobile applications and handle interactivity.
  - **API Integration**: The mobile app communicates with the backend via **RESTful APIs** to fetch data, process orders, and handle authentication.
  - **UI/UX**: The mobile app is designed with a focus on user experience, providing an intuitive and smooth interface for both vendors and customers.


## Installation

To set up **Wagihatar** on your local machine, follow the instructions below:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/wagihatar.git
