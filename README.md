### Beauty Parlour Management System
A web-based application developed to streamline the operations of a beauty parlour. This system allows the management of appointments, customer data, services, staff, and payments through a user-friendly interface.

### Features
User Authentication: Secure login for administrators and staff.
Appointment Management: Book, edit, and cancel appointments.
Customer Management: Add and view customer details.
Service Management: Manage the list of services offered, including pricing and availability.
Staff Management: Track and assign staff for services.
Payment Management: Generate bills and manage transactions.
Reports: View daily/weekly service and revenue reports.
Responsive Design: Optimized for use on both desktops and mobile devices.
Technologies Used
### Frontend:
HTML5, CSS3, JavaScript
Bootstrap (optional for styling)
Backend:PHP
Database:MySQL
Others:
AJAX (for asynchronous operations)
JSON (for data exchange)
Installation and Setup
Prerequisites
XAMPP/WAMP/MAMP: To run PHP and MySQL locally.
Web Browser: Chrome, Firefox, or any modern browser.
Steps to Run Locally
Clone the Repository:
bash
Copy code
git clone <your-repository-url>
Move the Project to the Server Folder:
Copy the cloned folder to the htdocs directory in XAMPP/WAMP.

### Import the Database:

Open phpMyAdmin at http://localhost/phpmyadmin.
Create a new database (e.g., bpms).
Import the provided SQL file (database.sql) into the newly created database.
Update Database Configuration:

Open config.php (or any relevant database configuration file).
Modify the following credentials if needed:
php
Copy code
$host = 'localhost';
$user = 'root';
$password = '';
$database = 'beauty_parlour';
Start the XAMPP/WAMP Server:

### Launch Apache and MySQL from the control panel.
Run the Application:
Open your browser and navigate to:
http://localhost/bpms

### Project Structure
bash
Copy code
/project-folder
│
├── /css          # Stylesheets
├── /js           # JavaScript files
├── /images       # Images and assets
├── /includes     # Common PHP files (headers, footers, etc.)
├── /config.php   # Database configuration
├── /index.php    # Home page
├── /admin        # Admin dashboard
├── /customer     # Customer dashboard
└── /database.sql # SQL file to create tables and insert data
### Usage
Admin: Manage services, appointments, and staff.
Staff: View assigned appointments and manage availability.
Customer: Book and view appointments and services.
Future Enhancements
Integration with payment gateways for online payments.
Email and SMS notifications for bookings.
Review and rating system for services.
Contributing
Contributions are welcome! Please follow these steps to contribute:

### Fork the repository.
Create a new branch (feature/your-feature-name).
Commit your changes.
Push to your branch.
Create a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for more information.

### Contact
For any queries or suggestions, feel free to contact:
Developer:Shraddha Shinde
Email: [your-shraddhashinde0432@gmail.com]
Location: Nashik
