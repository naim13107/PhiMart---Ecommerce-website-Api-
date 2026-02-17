# PhiMart — Ecommerce Website API

**PhiMart** is a RESTful API backend for an ecommerce platform built with **Django**. It provides endpoints for products, users, orders, carts, and more, enabling frontend applications and mobile apps to power a complete online shopping experience.

---

##  Features

1. User authentication and authorization (register/login/logout)  
2. Product listing, detail, create/update/delete (admin only)  
3. Cart management (add/remove/update items)  
4. Order creation and status tracking  
5. Protected routes and permissions  
6. Product image upload support  
7. Clean URL structure and JSON responses  

---

##  Tech Stack

1. **Python**  
2. **Django**  
3. **Django REST Framework**  
4. **SQLite** (default; can be replaced with PostgreSQL/MySQL)  

---

##  Installation

1. **Clone the repository**

```bash
git clone https://github.com/naim13107/PhiMart---Ecommerce-website-Api-.git
cd PhiMart---Ecommerce-website-Api-
```
2. **Create and activate a virtual environment**
```bash
python -m venv venv
# macOS/Linux
source venv/bin/activate
# Windows
venv\Scripts\activate
```
3. **Install dependencies**
```bash
pip install -r requirements.txt
```
4. **Apply database migrations**
```bash
python manage.py migrate
```
5. **Run the development server**
```bash
python manage.py runserver
```

##  API Documentation

This project supports **interactive API documentation** using **Swagger** and **Redoc**. You can explore all endpoints, see request/response examples, and test them directly from your browser.

### 7.1 Swagger UI

Swagger provides an interactive API documentation interface.

- URL (after running the server) : http://127.0.0.1:8000/swagger/



### 7.2 Redoc

Redoc provides a clean and mobile-friendly API documentation interface.

- URL (after running the server) : http://127.0.0.1:8000/redoc/

