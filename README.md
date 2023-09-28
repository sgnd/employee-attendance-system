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

# Choose one of the following based on your operating system:

# 1. For Windows:

copy .env.example .env

# 2. For Unix (Ubuntu, macOS, and others):

cp .env.example .env

# Next, configure the .env file by specifying the database name (DB_DATABASE), username, and password.

# Create a new database either from phpMyAdmin or using command-line tools with the same name as specified in DB_DATABASE in the .env file.

# Generate a new application key, run migrations, seed the database, and start the development server:

php artisan key:generate

php artisan migrate

php artisan db:seed

php artisan serve

# Finally, open your web browser and visit http://localhost:8000/

```

## How to Install/Use (English)

-   Clone this repository

```sh

git clone https://github.com/muhammadpauzi/employee-attendance-system.git

# Ensure you are inside the project folder

cd employee-attendance-system

```

-   Install all required packages

```sh

composer install

```

-   Copy/rename the `.env.example` file to `.env`

```sh

# For Windows:

copy .env.example .env

# For Unix (Ubuntu, macOS, and others):

cp .env.example .env

```

-   Configure the `.env` file

    <br>

    Open your `.env` file and update the database name (DB_DATABASE), username (DB_USERNAME), and password (DB_PASSWORD) fields according to your database configuration.

-   Create the database

    <br>

    Create a database with the name specified in the DB_DATABASE field in the `.env` file.

-   Run artisan commands
```sh
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan serve
```
-   Access the application by going to http://localhost:8000
