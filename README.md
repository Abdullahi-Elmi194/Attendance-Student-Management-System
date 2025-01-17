# *Student Attendance Management System*

This is a web-based *Student Attendance Management System* developed using *HTML, **CSS, **JavaScript, and **PHP, with **XAMPP* as the local server environment. The system allows for the efficient tracking and management of student attendance, providing features for both teachers and administrators.

---

## *Features*
- *Admin Dashboard*: Manage students, teachers, and attendance records.
- *Teacher Portal*: Mark daily attendance and generate reports.
- *Student and Parent Access*: View attendance history and records.
- *User-Friendly Interface*: Clean and responsive design for seamless usage.
- *Reports*: Export attendance data for analysis.

---

## *Technologies Used*
- *Frontend*: HTML, CSS, JavaScript  
- *Backend*: PHP  
- *Database*: MySQL (via XAMPP)  
- *Local Server*: XAMPP  

---

## *Setup Guide*
Follow these steps to set up the project on your local machine:

### *Step 1: Install XAMPP*
1. Download and install XAMPP from [Apache Friends](https://www.apachefriends.org/index.html).  
2. Start *Apache* and *MySQL* modules in the XAMPP Control Panel.

### *Step 2: Clone or Download the Project*
1. Clone this repository or download it as a ZIP file.  
2. Extract the ZIP file if needed.  


git clone https://github.com/abdullah-elmi194/attandence-student-management-system



Step 3: Configure the Project
Place the project folder in the htdocs directory inside your XAMPP installation folder. For example:


C:\xampp\htdocs\attandence-student-management-system

Open the XAMPP Control Panel and click Admin for MySQL to open phpMyAdmin.
Create a new database (e.g., attendance_system).
Import the SQL file included in the project into the newly created database:
Go to the Import tab in phpMyAdmin.
Select the SQL file (e.g., database.sql) from the project folder.
Click Go to import the database schema and data.

Step 4: Configure Database Connection
Open the config.php file in the project folder.
Update the database connection details as per your setup:


$servername = "localhost";
$username = "root";
$password = "";
$dbname = "attendance_system";
Step 5: Run the Project
Open your browser and go to:

http://localhost/attandence-student-management-system

Log in using the credentials provided in the database (or setup instructions).
Usage

Admin Panel: Manage students, teachers, and attendance data.
Teacher Access: Log in to mark attendance and view reports.
Students/Parents: View attendance records.
Folder Structure



Contributions are welcome! Please follow these steps:

Fork this repository.
Create a new branch:

git checkout -b feature-name
Commit your changes:

git commit -m "Add feature-name"
Push to the branch:

git push origin feature-name
Submit a pull request.
License

This project is licensed under the MIT License.

Contact

For any questions or feedback, feel free to reach out:

Abdullahi-Elmi194 Abdullahi Omar Elmi
20206393 20206393@std.neu.edu.tr
