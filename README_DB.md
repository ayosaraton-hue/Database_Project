# B2S Online Store – Database Management System

## Project Overview

This project focuses on analyzing business requirements and designing a database system for **B2S**, a retail business specializing in books, stationery, toys, art supplies, office supplies, and lifestyle products.

The project explores the business processes of B2S Online and identifies the data requirements and relationships needed to support its online shopping operations.

The project was developed as part of the **ITDS221 – Database Management System** course at Mahidol University.

## Project Objectives

- Analyze business requirements for an online retail business.
- Study and document the main business processes.
- Define business rules and relationships between business entities.
- Identify data requirements for each business process.
- Design an ER/EER Diagram to represent the database structure.

## Business Processes

This project analyzes three main business processes:

### 1. Online Member Registration

Analyzes the process of creating a customer account on B2S Online.

**Key activities:**

- Register a new membership account.
- Enter personal information.
- Validate registration information.
- Verify customer identity.
- Store member information in the database.

### 2. Online Ordering Process

Analyzes the process of purchasing products through B2S Online.

**Key activities:**

- Search and browse products.
- View product details and availability.
- Add products to the shopping cart.
- Review shopping cart items and total price.
- Enter shipping information.
- Select a payment method.
- Confirm the order.

### 3. Online Payment Process

Analyzes the process of completing payments for online orders.

**Key activities:**

- Select a payment method.
- Verify order information.
- Process payment transactions.
- Verify payment information through the payment provider.
- Record payment information in the database.
- Update payment and order statuses.
- Forward order information for product preparation and delivery.

## Business Rules

Defined business rules to describe the relationships between entities and their constraints across the three business processes.

The rules cover:

- Membership registration and member accounts.
- Membership types and membership statuses.
- Identity verification and shipping addresses.
- Member benefits, promotions, and discount coupons.
- Product categories and products.
- Shopping carts and shopping cart items.
- Orders and order details.
- Payment transactions and payment methods.
- Payment providers and payment statuses.
- Tax invoices and billing addresses.

The relationships include **One-to-One (1:1), One-to-Many (1:M), and Many-to-Many (M:N)**.

## Business Data Requirements

Identified the required data entities and their attributes for each business process.

### Member Registration

- Customer
- Member Account
- Membership Type
- Identity Verification
- Shipping Address
- Billing Address
- Membership Status
- Member Benefits
- Promotions
- Discount Coupons

### Online Ordering

- Product
- Book
- Stationery and Art Supplies
- Educational Toys
- Product Category
- Shopping Cart
- Order
- Order Item
- Order Status
- Discount Coupon

### Online Payment

- Payment Method
- Payment Provider
- Payment Status
- Payment Transaction
- Tax Invoice

## Business Constraints and Policies

Defined business conditions, limitations, and policies affecting business operations and data management, including:

- OTP expiration within 5 minutes.
- Email addresses and phone numbers must be unique during registration.
- Passwords must be hashed before being stored in the database.
- Free shipping for orders with a total product value of at least 899 THB.
- Product prices, shipping fees, and stock quantities cannot be negative.
- Inventory is deducted only after successful payment.
- Orders must be paid within 24 hours after confirmation.
- Tax invoices can only be issued after successful payment.

## ER/EER Diagram

Designed an Entity-Relationship (ER/EER) Diagram to represent the database structure, entities, attributes, and relationships based on the identified business rules and data requirements.

## Project Information

- **Course:** ITDS221 – Database Management System
- **University:** Mahidol University
- **Semester:** 3/2567
- **Project Type:** Database Design and Business Process Analysis
