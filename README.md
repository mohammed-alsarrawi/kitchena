# kitchena


# Kitchena - Cloud Restaurant Management System (Odoo)

![Kitchena Logo]("C:\Users\Orange\Desktop\kitchena.png") *(placeholder for logo)*

[website](https://kitchena2.odoo.com/)
## Overview
Kitchena is a comprehensive cloud-based restaurant management system built on Odoo ERP, specializing in fast food operations (burgers, pizza, steaks). Designed to streamline operations and enhance customer experience.

## Features

### 🍔 Order Management
- Dine-in, delivery, and takeaway order systems
- Real-time order tracking
- Meal-type categorization (Burgers/Pizza/Steaks)

### 📝 Menu Management
- Dynamic menu updates
- Ingredient and recipe management
- Meal tagging system (Spicy/Vegan/Gluten-Free)

### 📦 Inventory Control
- Automatic stock tracking
- Low-stock alerts
- Supplier management

### 👥 Staff Management
- Shift scheduling
- Role-based permissions
- Performance analytics

### 💳 Customer Loyalty
- Points-based rewards program
- Customer order history
- Special promotions

### 📊 Reporting & Analytics
- Sales by product/time
- Financial performance
- Inventory consumption reports

## Technical Requirements
- Odoo 16.0+
- Python 3.7+
- PostgreSQL 12+
- Linux/Windows Server

## Installation
```bash
git clone https://github.com/yourrepo/kitchena.git
cd kitchena
pip install -r requirements.txt
createdb kitchena
odoo-bin -c odoo.conf
