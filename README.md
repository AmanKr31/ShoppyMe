ShoppyMe - An E-commerce Platform
A dynamic e-commerce web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). ShoppyMe allows users to seamlessly browse products, register/login, manage carts, and place orders, while admins can manage products, view orders, and oversee the platform through a secure admin dashboard. The responsive design ensures optimal usability across devices.

Table of Contents
Overview

Features

Technology Stack

Installation

Usage

License

Contact

Overview
ShoppyMe is designed as a fully functional e-commerce website that provides a smooth shopping experience for users and efficient management capabilities for administrators. It offers all the essential features of a modern online store, including authentication, product browsing, cart management, and admin controls. The modular architecture and use of modern technologies make the application scalable and easy to maintain.

Features
User Authentication: Secure sign-up and login system with JWT authentication.

Product Management: Admins can add, update, and delete products.

Shopping Cart: Users can add items to cart, update quantities, and place orders.

Order Management: View order history and order status.

Admin Dashboard: Separate admin interface to manage products and orders.

Responsive Design: Works smoothly on both desktop and mobile devices.

RESTful APIs: Backend communication through robust REST APIs.

Technology Stack
Frontend: React.js, Redux Toolkit, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JWT (JSON Web Token)

State Management: Redux

Other Tools: Postman (for API testing), Git & GitHub (for version control)

Installation
Clone the Repository

bash
Copy
Edit
git clone https://github.com/AmanKr31/ShoppyMe.git
Backend Setup

Navigate to the backend folder:

bash
Copy
Edit
cd backend
Install dependencies:

bash
Copy
Edit
npm install
Configure .env file with the following variables:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Run the server:

bash
Copy
Edit
npm start
Frontend Setup

Navigate to the frontend folder:

bash
Copy
Edit
cd ../frontend
Install dependencies:

bash
Copy
Edit
npm install
Start the frontend:

bash
Copy
Edit
npm run dev
Usage
Users can register, log in, browse products, manage cart items, and place orders.

Admins can log in to access a dedicated dashboard for managing product listings and viewing order summaries.

The app is responsive and optimized for different screen sizes.

License
This project is open-source and available under the MIT License.

Contact
Aman Kr
GitHub: @AmanKr31
