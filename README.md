# E-commerce Platform

This is a simplified E-commerce platform implemented in Python using Flask for the backend, HTML/CSS for the frontend, and SQLite for the database. The project includes basic user authentication, product management, cart functionality, and order processing.

## Project Structure

### 1. `app/`

- **`static/`**: Contains the CSS file for styling.
- **`templates/`**: Stores HTML templates for rendering web pages.
- **`app.py`**: The main Flask application defining routes and functionalities.

### 2. `database/`

- **`ecommerce.db`**: SQLite database file to store user, product, and order information.

### 3. `run.py`

- Script to run the Flask application.

## How to Run

1. Save the code in the respective files and folders as mentioned in the project structure.
2. Install Flask and SQLAlchemy using `pip install Flask SQLAlchemy`.
3. Run the program using the command:
    
    ```bash
    python run.py
    
    ```
    
4. Open your browser and go to http://127.0.0.1:5000/ to view the E-commerce platform.

## Features

1. **Product Listing**: Display a list of products with names and prices.
2. **Product Details**: Click on a product to view its details.
3. **User Authentication**: Register and log in to the platform.
4. **Add to Cart**: Add products to the shopping cart.
5. **View Cart**: See the items in the cart and proceed to checkout.
6. **Order History**: View past order history.
7. **Logout**: Log out from the platform.

## Customization

Feel free to customize and expand upon this project based on your requirements. This example is a starting point and does not include advanced features like payment processing, product categories, or security enhancements, which would be crucial for a real-world E-commerce platform.

---

## Author

Jeel patel
