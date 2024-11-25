# Django Customer and Order Management

## Overview
This project implements a simple Django application with `Customer` and `Order` models. Each customer can place multiple orders, while each order belongs to a single customer.

## Features
- One-to-many relationship between `Customer` and `Order`.
- Fields:
  - **Customer**: `customer_name`, `customer_email`, `updated_at`.
  - **Order**: `customer`, `order_date`, `total_amount_of_order`, `updated_at`.

---

## Setting Up the Environment
### Steps
1. **Clone the repository**:
    git clone https://github.com/Maxwell619/CAT2/tree/main
    cd C:\Users\gatua\OneDrive\Desktop\API CAT2\CAT2
    

2. **Set up a virtual environment**:
    python -m venv venv
   .\.venv\Scripts.\Activates.ps1
   

3. **Apply migrations**:
    python manage.py migrate
   
4. **Run the development server**:
    python manage.py runserver
   

5. **Access the application**:
    Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

6. **View SQL statement**:
   py manage.py sqlmigrate CAT2 0001
