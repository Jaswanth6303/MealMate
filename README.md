# 🍴 MealMate
- **Authentication and Authorization:** Both customers and vendors must authenticate before accessing specific functionalities.

## Database Requirements:
- **Users Table:** Store customer and vendor information (user type, email, password, etc.) and track user status (active/inactive).
- **Restaurants Table:** Store restaurant details (name, description, categories, menu items, opening hours, approval status).
- **Orders Table:** Store order details (customer, vendor, items, total price, payment status, order status).
- **Menus Table:** Store menu items for each restaurant, including item name, description, price, and availability.
- **Categories Table:** Store food categories (e.g., appetizers, main course, desserts) for each restaurant.

## Technologies and Tools:
- **Frontend:**
  - HTML, CSS, JavaScript
  - React.js or Vue.js for dynamic, responsive user interfaces
- **Backend:**
  - Django (with Django REST Framework) or Flask
  - MySQL or PostgreSQL for the database
  - JWT (JSON Web Tokens) for secure user authentication
- **Payment Integration:**
  - PayPal API for payment processing
- **Authentication:**
  - Django's built-in authentication or JWT for secure login and role-based access control
- **Error Handling:**
  - Proper error handling and redirection for unauthorized access

## Security Considerations:
- **Data Validation:** Ensure that all user inputs are validated and sanitized to prevent SQL injection and XSS attacks.
- **Role-based Access Control:** Ensure that only authorized users can access specific resources.

## Installation Instructions

### Prerequisites:
- Python 3.x
- Node.js
- MySQL or PostgreSQL database
- PayPal API credentials

### Backend Setup:
1. Clone the repository:
   ```bash
   git clone https://github.com/Jaswanth6303/MealMate
   cd MealMate

### Usage:
Register and log in as a customer or vendor.
Browse restaurants, place orders, and make payments (customers).
Manage restaurant details, orders, and menus (vendors).
Admins can manage users and approve restaurants.

### Contributing:
Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them.
Push to your fork and submit a pull request.
<br></br>



