# News Portal Project

A **Laravel-based News Portal** application designed for managing and publishing news content.  
It supports multiple user roles (Admin, Writer, User) with role-based access control for content creation, editing, and reading.

---

## ✨ Features

- **Role-Based Access**
  - Admin: Manage users, categories, and news
  - Writer: Create and edit news articles
  - User: Browse and read published news
- **Authentication System**
- **Admin Dashboard**
- **Responsive UI** (Blade + Tailwind CSS + Vite)
- **Database-Driven News Storage**

---

## 🛠️ Tech Stack

- **Backend:** PHP, Laravel  
- **Frontend:** Blade templating, Tailwind CSS, Vite  
- **Database:** MySQL  
- **Tools:** Composer, npm  

---

## 📋 Requirements

Make sure you have installed:

- PHP >= 8.0  
- Composer  
- Node.js & npm  
- MySQL (or MariaDB)

---

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/kietsengly/lykietseng_newsportal_project.git
   cd lykietseng_newsportal_project
2. **Environment setup**
   ```bash
   cp .env.example .env
   php artisan key:generate
   # You can copy my database too.

3. **Install dependencies**
    ```bash
    composer install
    npm install
    npm run build   # or npm run dev for hot reload

4. **Setup database**
    ```bash
    php artisan migrate --seed

5. **Default Login Credentials**
    ```bash
    Admin	admin@gmail.com password is password
    Writer	writer@gmail.com password 12345678
    User	user123@gmail.com 12345678

**Run the Application**
```bash
php artisan serve

