<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## Module 16 Laravel Migration Concepts

# Laravel Migration Assignment

This repository contains the solution for the Laravel Migration Assignment.

## Tasks

Below are the tasks and their corresponding commands:

### Task 1: Create a new Laravel project named "MigrationAssignment"

composer create-project --prefer-dist laravel/laravel MigrationAssignment

### Task 2: Create a new migration file named "create_products_table"

php artisan make:migration create_products_table

### Task 3: Run the migration to create the "products" table

php artisan migrate

### Task 4: Modify the existing migration file "create_products_table" to add a new column called "quantity" to the "products" table

php artisan migrate:rollback

php artisan migrate

### Task 5: Create a new migration file named "add_category_to_products_table"

php artisan make:migration add_category_to_products_table --table=products

### Task 6: Run the migration to add the "category" column to the "products" table

php artisan migrate

### Task 7: Create a new migration file named "create_orders_table"

php artisan make:migration create_orders_table

### Task 8: Run the migration to create the "orders" table

php artisan migrate



