# 🚗 CarHub API

A powerful and flexible Laravel-based RESTful API for managing car listings, dealers, and user favorites.

---

## 🔧 Features

- Add, edit, and delete car listings  
- Dealer authentication & dashboard  
- Search and filter cars by brand, model, price, year, etc.  
- Save favorite cars  
- JSON API responses  
- Built with Laravel 12.x

---

## 📦 Tech Stack

- Laravel 12  
- MySQL  
- RESTful API  
- Laravel Sanctum (for authentication)  
- Eloquent ORM

---

## 🚀 Getting Started

### 1. Clone the repo

bash
git clone https://github.com/your-username/carhub-api.git
cd carhub-api

2. Install dependencies

composer install
cp .env.example .env
php artisan key:generate

3. Setup database

Edit .env file with your database credentials, then run:

php artisan migrate

4. Run the app

php artisan serve


---

📂 Folder Structure

app/Models — Eloquent models

routes/api.php — API routes

app/Http/Controllers/Api — API controllers

database/migrations — Table structure



---

🛡 Authentication

Using Laravel Sanctum for secure token-based API authentication.
Users can register, login, and receive access tokens to access protected routes.


---

📌 To Do

[ ] Image upload for cars

[ ] Admin dashboard

[ ] Dealer profile and verification

[ ] Postman / OpenAPI documentation



---

📄 License

MIT License
