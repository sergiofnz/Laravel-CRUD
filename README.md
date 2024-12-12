# Laravel Login Project

## Description
This project is a basic login application built with Laravel. It allows users to register, log in, and log out using secure authentication. Additionally, it includes a basic CRUD (Create, Read, Update, Delete) functionality for managing resources.

## Features
- User registration.
- Secure login.
- Logout functionality.
- Form validation.
- Database configuration for user storage.
- Basic CRUD operations for managing resources.

## Prerequisites
Ensure your system has the following components installed:
- [PHP](https://www.php.net/) >= 8.1
- [Composer](https://getcomposer.org/)
- [MySQL](https://www.mysql.com/)
- [Node.js](https://nodejs.org/) and npm (for compiling front-end assets)

## Installation

Follow the steps below to install and set up the project:

### 1. Clone the repository
```bash
git clone https://github.com/sergiofnz/laravel-CRUD.git
cd laravel-CRUD
```

### 2. Install dependencies
```bash
composer install
npm install
```

### 3. Configure the `.env` file
Copy the example file and edit it with your database configuration:
```bash
cp .env.example .env
```

Edit the `.env` file and update the following fields:
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
```



### 4. Run the database migrations
```bash
php artisan migrate
```

### 5. Compile the assets
```bash
npm run dev
```

### 6. Start the local server
```bash
php artisan serve
```
Access the application at [http://localhost:8000](http://localhost:8000).

## Usage
1. Register a new user.
2. Log in with the credentials you just registered.
3. Log out when finished.
4. Use the CRUD interface to manage resources:
   - **Create**: Add new records through the form.
   - **Read**: View a list of records.
   - **Update**: Edit existing records.
   - **Delete**: Remove records from the database.

## Relevant File Structure
- **`routes/web.php`**: Defines the application routes.
- **`app/Http/Controllers/Auth`**: Authentication controllers.
- **`app/Http/Controllers`**: Controllers for CRUD operations.
- **`resources/views`**: Views for authentication and CRUD interfaces.

## Technologies Used
- Laravel
- Blade (template engine)
- Bootstrap (for front-end design)
- MySQL (database)


**Thank you for using this project!**

