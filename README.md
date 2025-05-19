# Blood Bank & Donor Management System

This is a PHP-based Blood Bank & Donor Management System. Follow the steps below to set up and run the project locally using XAMPP.

## Prerequisites

- [XAMPP](https://www.apachefriends.org/index.html) installed on your system (includes Apache, PHP, and MySQL)
- A web browser

## Installation & Setup

1. **Download or Clone the Repository**

   Download the project files or clone the repository:

   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. **Copy Project to XAMPP `htdocs` Folder**

   Move the project folder (e.g., `obdms`) to the `htdocs` directory inside your XAMPP installation.  
   Example path:  
   `C:\xampp\htdocs\obdms`

3. **Start XAMPP**

   - Open XAMPP Control Panel.
   - Start the **Apache** and **MySQL** modules.

4. **Create the Database**

   - Open your browser and go to [http://localhost/phpmyadmin](http://localhost/phpmyadmin).
   - Click on **Import** and select the SQL file provided with the project (e.g., `obdms.sql`).
   - Click **Go** to import the database.

5. **Configure Database Connection**

   - Open the project folder in a code editor.
   - Locate the database configuration file (commonly in `includes/config.php` or similar).
   - Update the database username, password, and database name if needed.

6. **Access the Application**

   - Open your browser and go to:  
     [http://localhost/bbdms](http://localhost/obdms)

## Default Admin Login

- **Username:** `admin`
- **Password:** `Test@123`  
  (Change these after first login for security.)

## Features

- Donor registration and management
- Organ management
- Request and search for donors
- Admin dashboard and controls

## Troubleshooting

- Make sure Apache and MySQL are running in XAMPP.
- If you see database connection errors, check your database credentials and ensure the database is imported.

---

## About the Developer

I'm **Md Sefat Hossain**,  
BSc in CSE, Green University of Bangladesh  
📧 Email: contact.shiplo@gmail.com

**Note:** This project is for educational purposes. Please secure your deployment before using it in production.

