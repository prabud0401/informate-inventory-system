
# INFORMATE Inventory System  

A web-based Inventory Management System for INFORMATE Technologies, designed to streamline inventory tracking, order management, and supplier coordination. Built using **HTML**, **CSS**, **JavaScript**, **Bootstrap** for the frontend, and **PHP** with **Laravel** for the backend, powered by **MySQL**. Developed using Agile SDLC for enhanced efficiency and scalability.  

---

## Features  
- Real-time Inventory Tracking  
- Order Management and Stock Replenishment  
- Supplier Management and Purchase Orders  
- User Authentication and Role-Based Access  
- Reports and Analytics Dashboard  

---

## Tech Stack  
- Frontend: HTML, CSS, JavaScript, Bootstrap  
- Backend: PHP with Laravel  
- Database: MySQL  
- Development Tools: Composer, VS Code  

---

## Prerequisites  
Ensure the following are installed on your system:  
- **Composer** - For managing PHP dependencies  
- **PHP** (version 8.0 or higher) with required extensions:  
  - OpenSSL  
  - PDO  
  - Mbstring  
  - Tokenizer  
  - XML  
  - Ctype  
  - JSON  
- **MySQL** - For database management  

---

## Installation Guide  
1. **Install Composer**  
   - [Download and Install Composer](https://getcomposer.org/download/)  

2. **Clone the Repository**  
```bash
git clone https://github.com/your-username/informate-inventory-system.git
cd informate-inventory-system
```  

3. **Install Laravel and Dependencies**  
```bash
composer install
```  

4. **Configure Environment**  
   - Copy `.env.example` to `.env`  
```bash
cp .env.example .env
```  
   - Update `.env` file with your database credentials:  
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
```  

5. **Generate Application Key**  
```bash
php artisan key:generate
```  

6. **Run Database Migrations**  
```bash
php artisan migrate
```  

7. **Start Development Server**  
```bash
php artisan serve
```  
   Access the system at `http://localhost:8000`  

---

## Additional Notes  
- Make sure all required PHP extensions are enabled.  
- To install additional dependencies, use Composer commands:  
```bash
composer require package-name
```  

---

## License  
This project is licensed under the MIT License.  

---

## Contributors  
