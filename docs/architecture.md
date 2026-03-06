# Sysytem Architecture

## Dakkie Workwear Website

## 1. Overview

This document describes the **system architecture** of the official website for Dakkie Workwear.

The website is designed as a **modern e-commerce platform** that allows customers to browse products, manage accounts, and purchase workwear online. The architecture follows a **three-tier web architecture model**, ensuring scalability, maintainability, and performance.

---

## 2. Architecture Model

the system follows a **three-layer architecture:**

1. **Presentation Layer (Frontend)**
2. **Application Layer (Backend)**
3. **Data Layer (Database)**

This architecture separates responsibilities, making the system easier to maintain and expand.

---

## 3. Architecture Layers

### 3.1 Presentation Layer (Frontend)

The presentation layer is responsible for displaying the website interface and handling user interactions.

### Technologies

- HTML5
- CSS3
- JavaScript
- WordPress Themes
- Woocommerce Frontend Components

### Responsibilities

- Display product catalogue
- Render user interface
- Handle navigation and page layouts
- Collect user input from forms
- Display shopping cart and checkout interface

### User Interfaces

*The frontend includes the following major pages:*

- Home Page
- Shop / Products Page
- Product Details Page
- Cart Page
- Checkout Page
- Login Page
- Register Page
- User Account Dashboard
- Blog Page
- Contact Page

### 3.2 Application Layer (Backend)

The application layer handles business logic and system operations.

### Technologies

- PHP
- WordPress CMS
- WooCommerce

### Responsibilities

- Process user authentication
- Manage product catalogue
- Process shopping cart actions
- Handle checkout and order processing
- Manage user accounts
- Process contact form submissions
- Communicate with the database

### 3.3 Data Layer (Database)

The data layer stores all persistent website data.

### Technologies

- MySQL Database

### Stored Data

*The database stores the following information:*

- User accounts
- Product information
- Product categories
- Orders
- Customer details
- Blog posts
- Website settings

---

## 4. System Components

*The website consists of several key components:*

