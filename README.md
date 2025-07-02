In this Laravel 12 tutorial, you'll learn how to build a complete CRUD (Create, Read, Update, Delete) application from scratch using plain Blade and Bootstrap 5. 

We cover all the essential features required in a professional Laravel application, including:

- Product listing with pagination  
- Image upload with validation  
- Search functionality  
- Soft deletes and restore system   
- Bootstrap 5 user interface  

This is a perfect beginner-to-intermediate level Laravel project that helps you understand how to work with models, controllers, Blade views, migrations, validation, and much more.

🔧 Tech Stack:
- Laravel 12
- Bootstrap 5
- Blade Templates
- PHP 8+
- MySQL

🧠 What You'll Learn:
- Setting up a Laravel project
- Creating migrations, models
- Form validations
- Handling file uploads securely
- Displaying and restoring soft deleted records
- Creating search filters in Eloquent
- Designing a clean Bootstrap 5 UI

# Clone the repository
git clone https://github.com/shayanahmad1999/laravel-12-crud.git

# Change Folder
cd <project-folder>

# Install PHP dependencies
composer install

# Copy and set up the environment configuration
cp .env.example .env

# Generate application key
php artisan key:generate

# Run database migrations
php artisan migrate

# Storage link
php artisan storage:link

# Run the development server again
php artisan serve
