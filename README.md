# 🛒 Zapkart-B2B

## Advanced Laravel B2B Ecommerce & Delivery Management Platform

Zapkart-B2B is a complete high-level B2B ecommerce and delivery management system developed using Laravel.

The platform is designed to manage the entire workflow between:

* 👨‍💼 Admin
* 🏪 Shopkeepers / Sellers
* 👤 Customers / Users
* 🚚 Delivery Partners
* 🏬 Warehouse Management

This project provides a real business workflow where the admin controls sellers, products, deliveries, warehouse operations, and customer orders from a centralized dashboard.

---

# 🚀 Core Business Workflow

```text
                         ┌──────────────────┐
                         │      ADMIN       │
                         │ System Control   │
                         └────────┬─────────┘
                                  │
              ┌───────────────────┼───────────────────┐
              │                   │                   │
              ▼                   ▼                   ▼
      ┌──────────────┐    ┌──────────────┐    ┌──────────────┐
      │ SHOPKEEPERS  │    │   WAREHOUSE  │    │ DELIVERY BOY │
      │ / SELLERS    │    │ MANAGEMENT   │    │   SYSTEM     │
      └──────┬───────┘    └──────┬───────┘    └──────┬───────┘
             │                   │                   │
             ▼                   ▼                   ▼
      ┌──────────────────────────────────────────────────────┐
      │               PRODUCT MANAGEMENT                    │
      └──────────────────────┬──────────────────────────────┘
                             │
                             ▼
                    ┌────────────────┐
                    │     USERS      │
                    │ Ecommerce App  │
                    └──────┬─────────┘
                           │
                           ▼
                   ┌─────────────────┐
                   │  ADD TO CART    │
                   │ ORDER PURCHASE  │
                   └────────┬────────┘
                            │
                            ▼
                  ┌──────────────────┐
                  │ ONLINE PAYMENT   │
                  │ ORDER CONFIRM    │
                  └────────┬─────────┘
                           │
                           ▼
                  ┌──────────────────┐
                  │ DELIVERY TRACK   │
                  │ ORDER COMPLETED  │
                  └──────────────────┘
```

---

# 📌 Project Overview

Zapkart-B2B is not just a normal ecommerce project.

It is a complete B2B business management platform where:

* Admin creates and manages shopkeepers
* Shopkeepers become sellers on the platform
* Sellers manage and upload products
* Products can also be managed through warehouse workflow
* Users browse and purchase products online
* Customers can add products to cart and place orders
* Online payment system handles purchases
* Delivery partners manage order delivery
* Customers can track deliveries live
* Orders can be cancelled by users/admin
* Full authentication and role management system is implemented

The project follows a real-world ecommerce and B2B operational workflow.

---

# 👨‍💼 Admin Panel Features

The Admin controls the complete platform.

## Admin Responsibilities

✅ Create Shopkeepers / Sellers
✅ Manage Seller Accounts
✅ Product Approval & Management
✅ Warehouse Management
✅ User Management
✅ Delivery Partner Management
✅ Order Monitoring
✅ Payment Monitoring
✅ Category Management
✅ Delivery Assignment
✅ System Analytics
✅ Platform Security Control
✅ Authentication & Access Control

---

# 🏪 Shopkeeper / Seller Module

Shopkeepers are created by the Admin and work as sellers inside the platform.

## Seller Features

✅ Seller Dashboard
✅ Product Upload System
✅ Product Management
✅ Inventory Management
✅ Product Pricing Control
✅ Order Handling
✅ Sales Tracking
✅ Customer Order Monitoring
✅ Product Availability Management

---

# 👤 User Ecommerce System

Users can use the platform like a professional ecommerce application.

## User Features

✅ User Registration & Login
✅ Secure Authentication
✅ Product Browsing
✅ Product Search & Filtering
✅ Add To Cart System
✅ Checkout System
✅ Online Purchase Workflow
✅ Online Payment Integration
✅ Order Placement
✅ Order Tracking
✅ Delivery Status Tracking
✅ Order History
✅ Order Cancellation

---

# 🚚 Delivery Partner System

The platform contains a complete delivery management workflow.

## Delivery Features

✅ Delivery Partner Registration
✅ Delivery Assignment System
✅ Order Pickup Workflow
✅ Delivery Status Updates
✅ Delivery Tracking System
✅ Completed Delivery History
✅ Order Delivery Confirmation

---

# 🏬 Warehouse Workflow

The platform also supports warehouse-level product handling.

## Warehouse Features

✅ Product Storage Workflow
✅ Product Dispatch Management
✅ Seller Product Coordination
✅ Order Processing Support
✅ Inventory Handling

---

# 🛒 Ecommerce Workflow

```text
User Registration/Login
          │
          ▼
Browse Products
          │
          ▼
Add Products To Cart
          │
          ▼
Checkout Process
          │
          ▼
Online Payment
          │
          ▼
Order Placement
          │
          ▼
Seller Receives Order
          │
          ▼
Warehouse Processing
          │
          ▼
Delivery Partner Assignment
          │
          ▼
Live Delivery Tracking
          │
          ▼
Successful Delivery
```

---

# 🔐 Authentication & Security

The system includes a secure authentication and authorization workflow.

## Security Features

✅ Login Authentication
✅ Role-Based Access Control
✅ Admin Authentication
✅ Seller Authentication
✅ User Authentication
✅ Secure Session Management
✅ Middleware Protection

---

# ⚙️ Technology Stack

## Backend

* Laravel Framework
* PHP
* MySQL Database
* MVC Architecture
* RESTful Workflow

## Frontend

* Blade Templates
* HTML5
* CSS3
* JavaScript
* Bootstrap / Tailwind CSS

## System Features

* Authentication System
* Ecommerce System
* Delivery Tracking
* Order Management
* Cart Management
* Seller Management
* Warehouse Workflow
* Multi-user Role System

---

# 🔄 Complete Business Flow Architecture

```text
                    ┌───────────────────────────┐
                    │           ADMIN           │
                    │ Complete System Control   │
                    └─────────────┬─────────────┘
                                  │
          ┌───────────────────────┼────────────────────────┐
          │                       │                        │
          ▼                       ▼                        ▼
 ┌────────────────┐    ┌──────────────────┐    ┌──────────────────┐
 │ SHOPKEEPERS /  │    │   WAREHOUSE      │    │ DELIVERY PARTNER │
 │    SELLERS     │    │ MANAGEMENT SYSTEM│    │    MANAGEMENT    │
 └────────┬───────┘    └─────────┬────────┘    └────────┬─────────┘
          │                      │                      │
          └──────────────┬───────┴──────────────┬───────┘
                         │                      │
                         ▼                      ▼
                 ┌────────────────────────────────────┐
                 │      PRODUCT MANAGEMENT SYSTEM     │
                 │ Product • Stock • Inventory • SKU  │
                 └────────────────┬───────────────────┘
                                  │
                                  ▼
                      ┌───────────────────────┐
                      │        USERS          │
                      │ Browse & Purchase     │
                      └──────────┬────────────┘
                                 │
                                 ▼
                       ┌────────────────────┐
                       │   ADD TO CART      │
                       │ CHECKOUT PROCESS   │
                       └─────────┬──────────┘
                                 │
                                 ▼
                       ┌────────────────────┐
                       │ ONLINE PAYMENT     │
                       │ ORDER CONFIRMATION │
                       └─────────┬──────────┘
                                 │
                                 ▼
                       ┌────────────────────┐
                       │ DELIVERY TRACKING  │
                       │ OTP VERIFICATION   │
                       └─────────┬──────────┘
                                 │
                                 ▼
                       ┌────────────────────┐
                       │ SUCCESSFUL DELIVERY│
                       │ EMAIL NOTIFICATION │
                       └────────────────────┘
```

---

# 📦 Complete Ecommerce Workflow

```text
User Registration/Login
          │
          ▼
Browse Products
          │
          ▼
Add Products To Cart
          │
          ▼
Checkout Process
          │
          ▼
Online Payment Processing
          │
          ▼
Order Successfully Placed
          │
          ▼
Seller Receives Order
          │
          ▼
Warehouse Product Processing
          │
          ▼
Admin Assigns Delivery Partner
          │
          ▼
Delivery Partner Picks Order
          │
          ▼
OTP Verification Delivery
          │
          ▼
Successful Delivery Completed
```

---

# 📧 Notification & Email Workflow

```text
User Registration
        │
        ▼
Welcome Email Sent

Order Placed
        │
        ▼
Order Confirmation Email

Payment Successful
        │
        ▼
Payment Notification Email

Seller Receives Order
        │
        ▼
Seller Notification Email

Delivery Assigned
        │
        ▼
Delivery Partner Notification

Order Out For Delivery
        │
        ▼
Live Tracking Notification

Order Delivered
        │
        ▼
Delivery Success Email
```

---

# 💰 Commission & Earnings Workflow

```text
Customer Purchases Product
              │
              ▼
Online Payment Received
              │
              ▼
System Calculates Commission
              │
 ┌────────────┼─────────────┐
 ▼            ▼             ▼
Admin      Seller      Delivery Boy
Commission Earnings     Earnings
```

---

# 📊 Stock & Inventory Workflow

```text
Admin/Seller Adds Product
             │
             ▼
Warehouse Stock Updated
             │
             ▼
Product Available For Sale
             │
             ▼
Customer Purchases Product
             │
             ▼
Stock Automatically Reduced
             │
             ▼
Inventory Updated In System
```

---

# 🌟 Advanced Platform Features

✅ Advanced B2B Workflow
✅ Ecommerce Marketplace
✅ Seller Management System
✅ Warehouse Integration
✅ Delivery Tracking System
✅ Online Purchase Workflow
✅ Add To Cart System
✅ Order Cancellation
✅ Multi-user Authentication
✅ Admin Control System
✅ Inventory & Product Management
✅ High-Level Laravel Architecture

---

# 📂 Main Modules

* Admin Management
* Seller Management
* User Management
* Ecommerce System
* Product Management
* Inventory Management
* Warehouse Management
* Cart System
* Payment System
* Delivery Tracking
* Authentication & Authorization
* Order Management

---


# 🎯 Purpose of the Project

The goal of Zapkart-B2B is to build a complete advanced B2B ecommerce ecosystem where:

* Admin manages the entire platform
* Sellers manage products and orders
* Users purchase products online
* Delivery partners manage deliveries
* Warehouse supports inventory workflow
* The entire ecommerce process works in a professional business structure

This platform combines ecommerce, B2B operations, delivery management, seller workflow, and warehouse coordination into one complete Laravel application.

---

# 👨‍💻 Developer

## Ayesha Siddiqui

GitHub:
[https://github.com/aayasha-siddiqui](https://github.com/aayasha-siddiqui)

---

# 📄 License

This project is developed for educational, portfolio, and advanced commercial learning purposes.
