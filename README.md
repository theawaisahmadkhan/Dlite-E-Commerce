# Dlite E-Commerce Website
Dlite E-Commerce

# Description
Dlite E-Commerce is a fully functional E-Commerce website built using PHP Laravel. The website allows users to browse through various products, add them to their cart, and proceed to checkout for purchase. It provides a seamless shopping experience with features like product search, user authentication, secure payment processing, and order tracking.

# Features
Browse through a wide range of products across different categories.
Search for specific products by name or category.
User registration and login for personalized shopping experiences.
Add products to the cart and manage cart items.
Checkout with secure payment processing using popular payment gateways.
Order tracking to keep users updated about their delivery status.
Admin panel for managing products, categories, orders, and users.
Responsive design for optimal user experience on various devices.
Installation
To set up the Dlite E-Commerce website locally, follow the steps below:

# Clone the repository:

git clone https://github.com/theawaisahmadkhan/Dlite-E-Commerce.git
cd Dlite-E-Commerce
Install the required dependencies using composer:

composer install
Create a copy of the .env.example file and rename it to .env. Update the database and mail configurations as per your environment.

cp .env.example .env
Generate a new application key:

php artisan key:generate
Migrate the database:

php artisan migrate
Seed the database with sample data (optional):

php artisan db:seed
Start the development server:

php artisan serve
Open your web browser and visit http://localhost:8000 to access the website.
