# 📝 Blog / Posts Management System (CRUD Project)

“I built a small blog application where users can add, edit, and delete posts.
I used migrations for database tables, controllers for CRUD logic, and Blade for the frontend.”

A simple **Blog Management System** built with **Laravel**, where users can **create, read, update, and delete (CRUD)** posts.  

This project demonstrates the use of **Routes, Controllers, Blade Templates, Eloquent ORM, and Validation** in Laravel.

---

## 🚀 Features

- Create, Read, Update, and Delete blog posts  
- Posts stored in **MySQL database** using **Migrations**  
- **Blade templates** for forms and displaying posts  
- **Validation** for post title & body before saving  
- Pagination for listing posts  

---

## 🛠️ Tech Stack

- **Laravel 10+** (Backend Framework)  
- **MySQL** (Database)  
- **Eloquent ORM** (Database operations)  
- **Blade Templates** (Frontend)  

---

## 📂 Project Structure

- **Routes** → `routes/web.php`  
- **Controller** → `app/Http/Controllers/PostController.php`  
- **Model** → `app/Models/Post.php`  
- **Views** → `resources/views/posts/`  
- **Migrations** → `database/migrations/`  

---

## ⚡ Installation & Setup

1.   Clone the repository:
   ```bash
   git clone https://github.com/yourusername/blog-crud.git
   cd blog-crud
   
2.  # Install dependencies:
    ```bash
    composer install
    
3.  # Set up the .env file:
    ```bash 
      cp .env.example .env
# Configure your database connection (DB_DATABASE, DB_USERNAME, DB_PASSWORD).

4. # Run migrations:
     ```bash 
    php artisan migrate
     
5.   # Start the development server:
    ```bash 
    php artisan serve
  
7.   # Visit the app in your browser:
      ```bash 
    http://127.0.0.1:8000/posts

 # 📘 CRUD Functionality

# Index Page → List all posts with pagination

# Create Page → Add a new post

# Show Page → View a single post

# Edit Page → Update an existing post

# Delete Action → Remove a post


📌 Learning Highlights

Routes → Map URLs to controller actions

Controllers → Handle CRUD logic

Eloquent ORM → Simplifies database queries

Validation → Ensures input data is correct before saving

Blade Templates → For clean and reusable UI


👨‍💻 Author

Anurag Maurya

GitHub: [Anurag876999](https://github.com/Anurag876999/My-Blog)
