# Online Examination System for Employees

## Overview
The Online Examination System for Employees is a web-based application developed as part of a **Year 1, Semester 2 project** at **SLIIT**. The system is designed to enable organizations to conduct online tests for their employees efficiently. It supports essential features like question management, user authentication, test evaluation, and results reporting.

## Features
- **User Authentication**: Secure login for administrators and employees.
- **Question Management**: Admins can add, edit, and delete questions for the exams.
- **Examination Interface**: A user-friendly interface for employees to take tests.
- **Automatic Grading**: Instant evaluation of test submissions.
- **Result Analysis**: Detailed result reporting for both employees and administrators.
- **Multi-role Access**: Separate dashboards for administrators and employees.

## Technologies Used
- **Backend**: PHP
- **Database**: MySQL (via XAMPP)
- **Frontend**: HTML, CSS, JavaScript
- **Development Environment**: XAMPP

## Installation Instructions
1. **Download and Install XAMPP**:
   - Download XAMPP from [Apache Friends](https://www.apachefriends.org/index.html).
   - Install and start Apache and MySQL.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/MethZ0/online-examination-system.git
   ```

3. **Setup the Database**:
   - Open phpMyAdmin (http://localhost:<your-port>/phpmyadmin).
   - Create a new database:
     - Click on **Databases** in the top navigation menu.
     - Enter `oesfe` as the database name and click **Create**.
   - Import the SQL file:
     - Select the `oesfe` database from the left sidebar.
     - Click on the **Import** tab.
     - Click **Choose File**, navigate to the `database` folder in the project, and select the SQL file.
     - Click **Go** to import the structure and data.

4. **Configure the Application**:
   - Open the `config.php` file in the project.
   - Update the database connection details:
     ```php
     $servername = "localhost:<your-port>";
     $username = "root";
     $password = "";
     $dbname = "oesfe";
     ```
     Replace `<your-port>` with the port number you are using for MySQL (default is 3306, but this project uses 3308).

5. **Run the Application**:
   - Place the project folder in the `htdocs` directory of XAMPP.
   - Access the application via `http://localhost/online-examination-system` in your browser.

## Usage Instructions
1. **Administrator Access**:
   - Log in with the administrator credentials.
   - Manage questions, view results, and monitor employee performance.

2. **Employee Access**:
   - Log in with employee credentials.
   - Take assigned exams and view results.


## Screenshots
![Login Page]()
*Login interface for employees and administrators.*

![Exam Interface](path/to/screenshot2.png)
*User-friendly examination interface for employees.*

## Contributing
Contributions are welcome! If you would like to improve or add new features, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For any queries or support, please contact:
- **Email**: methushanjula01@gmail.com
- **GitHub**: [MethZ0](https://github.com/MethZ0)
```
