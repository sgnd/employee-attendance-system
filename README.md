# Employee Attendance System with QR Code

## Features
- [x] CRUD Positions (Manage Job Positions)  
- [x] CRUD Users (Admins, Operators, and Employees)  
- [x] CRUD Holidays (Manage Holidays)  
- [x] CRUD Attendances (Track Employee Attendance with QR Codes or Buttons)  
- [x] Utilizes Datatables (Powered by Livewire)  
- [x] Export Data to Excel and CSV Formats  
- [x] And More...  

## Installation Instructions (Local)

**Prerequisites**
- Git  
- Composer  
- PHP v8.1  

```sh
# First, clone the repository via command line (cmd, bash, or other terminals)
git clone https://github.com/sgnd/employee-attendance-system.git

# Navigate to the project folder
cd employee-attendance-system

# Install all required packages
composer install

# Copy example env to .env and configure the file by specifying the database name (DB_DATABASE), username, and password
cp .env.example .env

# Generate a new application key, run migrations, seed the database, and start the development server:
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan serve

# Finally, open your web browser
http://localhost:8000
```

