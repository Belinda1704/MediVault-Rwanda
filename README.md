# MediVault.rw - Integrated Patient Management System (IPMS)

Transforming healthcare in Rwanda through seamless digital record-keeping.

---

## 📌 Overview

**MediVault.rw** is a web-based **Integrated Patient Management System (IPMS)** designed to improve healthcare efficiency in Rwanda by providing a centralized platform for managing patient data. The system simplifies the management of patient records, prescriptions, employee data, and more, empowering hospitals to deliver better care through technology.

---

## 🎯 Key Features

### Administrator Features
- **Patients Management**:
  - Register, view, and manage patient records.
- **Employees Management**:
  - Add, view, manage, transfer, and assign employees to departments.
- **Prescriptions Management**:
  - Add, view, and manage prescriptions.
- **Reporting**:
  - Generate reports for:
    - Inpatient records
    - Outpatient records
    - Employee records
    - Medical records.
- **Medical Records**:
  - Add and manage patient medical records.
- **Payroll Management**:
  - Add and manage payroll details.

### Doctor Features
- **Patients Management**:
  - Add, view, manage, discharge, and transfer patients.
- **Prescriptions Management**:
  - Add, view, and manage prescriptions.
- **Payroll Information**:
  - View personal payroll details.

---

## 🔑 Login Details

### Admin Login
- **Email**: admin@mail.com  
- **Password**: Password@123  

### Doctor Login
- **ID**: YDS7L  
- **Password**: password  

---

## 💻 Technologies Used

- **Backend**: PHP
- **Database**: MySQL
- **Frontend**: HTML, CSS, and JavaScript

---

## ⚙️ How It Works

1. **Admin Features**:
   - Administrators oversee all hospital operations, including staff and patient management.
   - Admins can log in using their email and password.

2. **Doctor Features**:
   - Doctors can manage patient records, prescriptions, and view payroll details.
   - Doctors log in using their unique Doctor ID and password.

---

## 🎯 Target Audience

Hospitals in Rwanda looking to digitize their medical records and processes for improved healthcare delivery.

---

## 📸 Screenshots

*(Add screenshots of the website here after development.)*

---

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- PHP 7.4 or higher
- MySQL 5.7 or higher
- A web server (e.g., Apache or Nginx)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/MediVault.git

2. Navigate to the project directory:
    cd MediVault

3. **Set up the database**:
- Import the provided `database.sql` file into your MySQL server.
- Create a new database in your MySQL server (e.g., `mediavault`).
- Run the SQL commands from `database.sql` to set up the required tables.

4. **Configure the database connection**:
- Open the `config.php` file.
- Update the database connection settings (`host`, `username`, `password`, `dbname`) with your MySQL server credentials.

5. **Start your local server**:
- If using **XAMPP**, open the XAMPP Control Panel and start Apache and MySQL.
- If using **WAMP** or **MAMP**, start the respective services.

6. **Access the application**:
- Open your browser and navigate to `http://localhost/MediVault` (or the appropriate directory on your server).

### Example Login Details:

#### Admin Login:
- **Email**: admin@mail.com
- **Password**: Password@123

#### Doctor Login:
- **ID**: YDS7L
- **Password**: password

## Screenshots

*Screenshots of the application will be added here later.*

## License

This project is licensed under the MIT License.

## Contact

For questions or collaboration opportunities, reach out to:

  **Email**: mediavault@support.com
  **Phone**: +250-788-330-821
