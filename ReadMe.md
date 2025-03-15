# **Ecommerce Website in PHP with MySQL**

## **Overview**
This is a fully functional eCommerce website built with PHP and MySQL, designed to handle various essential aspects of an online shopping platform. The system includes features for both customers and administrators, allowing for product management, order handling, customer management, and more. This project can be a great choice for final-year IT students looking for a college project, as it simulates real-world eCommerce website functionalities.

## **Features**

### **Customer Side:**
- **User Registration & Login:** Customers can create an account and log in to the system.
- **Product Browsing & Filtering:** Customers can browse through products, apply filters, and search for specific items.
- **Add to Cart:** Users can add items to the shopping cart and manage them, including updating quantities or removing items.
- **Checkout & Order History:** Customers can complete the purchase through the checkout process and view their order history.
- **Product Categories:** Customers can view products by category (e.g., men's clothing, electronics, etc.).
- **Featured, Latest, and Popular Products:** Sections that display products based on their popularity, recency, or special features, allowing customers to interact with the website more efficiently.

### **Admin Side:**
- **Product Management:** Admins have full control to add, edit, and delete products, including product details like name, price, category, description, and images.
- **Order Management:** Admins can view, update, and track customer orders, including updating the order status (e.g., pending, shipped, completed).
- **Customer Management:** Admins can view and manage customer accounts, including verifying email addresses and deactivating accounts if needed.
- **Website Settings:** Admins can modify website settings such as header, footer, branding, and color schemes.
- **Order Status & Payment Tracking:** Admins can update payment and shipping statuses, ensuring smooth order processing.
- **Communication with Customers:** Admins can send messages to customers regarding orders or product issues.

### **Additional Features:**
- **Admin Dashboard:** Provides an overview of the website, orders, and customer activity.
- **Search Functionality:** Allows customers to search for products using keywords.
- **Image Sliders:** Admin can manage image sliders to showcase promotions or featured products.

## **Requirements**
Before setting up the project, ensure that the following software is installed:
- **PHP** (version 7.0 or higher)
- **MySQL** (version 5.7 or higher)
- **Apache Server** (or any compatible web server)
- **PHPMyAdmin** (for easy database management)

## **Setup**

### **Step 1: Clone or Download the Repository**
Clone this repository or download the zip file from the project page.
```bash
git clone <repository-url>
```

### **Step 2: Database Setup**
1. Create a new MySQL database using PHPMyAdmin or through the MySQL command line.
2. Import the provided `ecommerce.sql` database file into your database.
3. Update the database connection settings in `config.php` (located in the root folder) with your database credentials (username, password, and database name).

### **Step 3: Configuration**
Navigate to the project folder and open the `config.php` file.
Update the following details to match your local server:
- **Database username**
- **Database password**
- **Database name**
- **Website base URL**

### **Step 4: Running the Project**
1. Start your Apache server and MySQL database.
2. Open your web browser and navigate to `localhost/your-project-folder`.
3. You should be able to see the homepage of the eCommerce website.
4. Log in as an admin using the default credentials (provided in `admin_login.php` or documentation).

### **Admin Default Credentials**
- **Username:** admin
- **Password:** admin123

## **Project Structure**
```bash
/ecommerce-website
    /assets               # Static assets like images, CSS, JS files
    /includes             # Includes for header, footer, and other reusable sections
    /admin                # Admin panel files
    /customer             # Customer-facing pages
    /config.php           # Database and website configuration
    /index.php            # Home page
    /product.php          # Product details page
    /cart.php             # Shopping cart page
    /checkout.php         # Checkout page
    /order-history.php    # Customer's order history page
```

## **Screenshots**
- **Homepage:** Display of featured, latest, and popular products.
- **Admin Dashboard:** Admin panel overview with controls to manage products, orders, and customers.
- **Product Management:** Interface for admins to add or modify products.

## **License**
This project is open-source and free to use for educational purposes. You can modify and adapt it according to your needs.

## **Conclusion**
This eCommerce website project demonstrates essential eCommerce features such as product browsing, user accounts, cart management, and order processing. The admin panel offers full control over product listings, customer data, and order management. Whether you're an IT student or someone looking to create an online store, this project provides a solid foundation for building a more advanced eCommerce platform.

