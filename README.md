# Scar Drive - Car Dealership Management System

Scar Drive is a comprehensive web-based application designed for car dealerships. It provides a platform for users to browse available vehicles, view services, and calculate EMI, while offering dealership owners tools to manage their inventory and customer interactions.

## 🚀 Features

### User Features
*   **Car Inventory**: Browse a wide range of cars with detailed specifications and pricing.
*   **Search & Filter**: Find cars based on preferences.
*   **Services Overview**: View maintenance and repair services offered by the dealership.
*   **EMI Calculator**: Built-in tool to help customers estimate their monthly payments.
*   **Wishlist**: Users can add cars to their wishlist for future reference.
*   **Contact Form**: Easy way for customers to reach out to the dealership.

### Admin/Owner Features
*   **Owner Login**: Secure login for dealership administrators.
*   **Inventory Management**: Add new cars (`newcar.php`), edit details (`editdetails.php`), and remove listings (`deletecar.php`).
*   **Dashboard**: Overview of dealership activities.

## 🛠️ Technology Stack

*   **Frontend**: HTML5, CSS3, JavaScript
*   **Backend**: PHP
*   **Database**: MySQL
*   **Styling**: Custom CSS (responsive design)

## ⚙️ Installation & Setup

1.  **Prerequisites**:
    *   Install a local server environment like **XAMPP**, **WAMP**, or **MAMP**.

2.  **Clone/Download**:
    *   Download the project and extract it to your server's root directory (e.g., `htdocs` for XAMPP).

3.  **Database Setup**:
    *   Open **phpMyAdmin** (usually at `http://localhost/phpmyadmin`).
    *   Create a new database named `scar_drive`.
    *   Import the `scar_drive.sql` file located in the root directory of this project.

4.  **Configuration**:
    *   Open `scar_web/config.php` and ensure the database credentials match your local setup:
        ```php
        $server = "localhost";
        $user = "root";
        $pass = ""; // Enter your MySQL password if set
        $database = "scar_drive";
        ```

5.  **Run the Application**:
    *   Start Apache and MySQL modules in XAMPP/WAMP.
    *   Open your browser and navigate to:
        `http://localhost/Scar-drive-main/scar_web/home.php`

## 📂 Project Structure

*   `scar_web/`: Contains all source code (PHP, CSS, JS).
    *   `home.php`: Main landing page.
    *   `config.php`: Database connection file.
    *   `image/`: Directory for project images.
    *   `css/`: Stylesheets.
    *   `uploads/`: Directory for uploaded car images.
*   `scar_drive.sql`: Database export file for setup.

## 🤝 Contributing

Feel free to fork this project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

[MIT](https://choosealicense.com/licenses/mit/)
