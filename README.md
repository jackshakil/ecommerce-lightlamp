## Decorative Lights ecommerce Website with Razorpay Payment Gateway Integration using Django

This repository contains the source code for a Decorative Lights Website built using Django, a high-level Python web framework. The website serves as an online platform for showcasing and selling a wide range of decorative lights, with the added functionality of accepting payments through the Razorpay payment gateway.

### Key Features

- User-friendly interface: The website offers a clean and intuitive user interface, ensuring a seamless browsing and shopping experience for visitors.
- Product catalog: A comprehensive catalog of decorative lights is available, categorized by themes, styles, and occasions, making it easy for users to find their desired products.
- Product details: Each product listing includes detailed information such as description, price, images, and specifications, enabling users to make informed purchasing decisions.
- Shopping cart: Users can add products to their shopping cart, review the selected items, and proceed to checkout for a smooth purchasing process.
- User authentication: Secure user registration and login functionality are implemented, allowing users to create accounts, track their orders, and manage their profiles.
- Search functionality: A robust search feature enables users to quickly find specific products by keywords, filtering the catalog based on their preferences.
- Wishlist: Users can create and manage wishlists, saving their favorite products for future reference or sharing with others.
- Payment gateway integration: The website incorporates the Razorpay payment gateway, allowing users to securely make payments for their orders using various payment methods.
- Order management: Site administrators have access to an admin dashboard, where they can manage products, user accounts, orders, and payment transactions.

### Technologies Used

- Django: A high-level Python web framework for rapid development and clean, maintainable code.
- HTML/CSS: The standard markup language and styling technology used for building the website's user interface.
- JavaScript: Used to enhance user interactions and implement dynamic functionality on the client-side.
- Bootstrap: A popular front-end framework for designing responsive and mobile-first websites.
- SQLite: A lightweight and easy-to-use database management system, used for storing product, user, and order information.
- Razorpay: A secure and reliable payment gateway for accepting online payments.

### Installation

To set up the Decorative Lights Website with Razorpay integration locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install the required dependencies by running `pip install -r requirements.txt`.
4. Configure the database settings in the `settings.py` file, specifying the appropriate database credentials.
5. Set up a Razorpay account and obtain the necessary API keys.
6. Update the Razorpay API keys in the Django settings file.
7. Apply the database migrations using the command `python manage.py migrate`.
8. Start the development server with `python manage.py runserver`.
9. Access the website by visiting `http://localhost:8000` in your web browser.

Ensure that your local development environment has the necessary prerequisites and dependencies installed. Additionally, consult the documentation and resources provided by Razorpay for any specific integration instructions.
