# Mendix Customer Purchase Portal

## Project Overview

This is a comprehensive customer purchase portal developed using Mendix platform. The application facilitates online shopping with multiple user roles and complete order management system from product browsing to delivery tracking.

## User Roles

The application supports 5 different types of users:
1. **Admin**
2. **Customer (with login)**
3. **Customer (without login)**
4. **Shop Owner**
5. **Delivery**

## Features by User Role

### 👑 Admin
- **Product Management**: Create products with properties (name, price, description, product image)
- **CRUD Operations**: View, create, and delete products
- **Bulk Import**: Import multiple products through Excel sheet using Excel importer
- **Customer Analytics**: View customer details and their payment history
- **Data Export**: Download product details and payment details in Excel format using Excel exporter marketplace module

### 👤 Customer (with login)
- **User Registration**: Sign-up with details (name, email, phone number, username, password)
- **Product Browsing**: View detailed product information
- **Shopping Cart**: Add products to cart with quantity management
- **Price Calculation**: Automatic calculation of total products and sum of product prices in cart
- **Payment Processing**: Enter payment details (card holder name, card number, CVV) and process payment
- **Invoice Generation**: Download PDF invoice after successful payment
- **Payment History**: Access to personal payment transaction history

### 🛒 Customer (without login)
- **Product Browsing**: View product details without registration
- **Registration Prompt**: Pop-up display for sign-up when attempting to purchase
- **Seamless Transition**: Proceed to purchase after completing sign-up

### 🏪 Shop Owner
- **Order Management**: View all orders placed by customers
- **Order Confirmation**: Confirm orders by checking product availability and prepare for delivery
- **Payment Oversight**: View all payment transactions
- **Comprehensive Reports**: Access detailed information on products and payments
- **Bulk Import**: Import multiple products through Excel sheet using Excel importer

### 🚚 Delivery
- **Delivery Queue**: View orders ready for delivery
- **Status Updates**: Update delivery status once items are delivered
- **Order Tracking**: Monitor delivery progress and completion

## Technologies Used
- **Platform**: Mendix Low-Code Platform
- **Modules**: 
  - Excel Importer (Marketplace Module)
  - Excel Exporter (Marketplace Module)
  - PDF Generation
- **Database**: Mendix Built-in Database
- **Authentication**: Mendix User Management

## Key Functionalities
- Multi-role user management system
- Complete e-commerce workflow
- Real-time order tracking
- Automated invoice generation
- Bulk data import/export capabilities
- Secure payment processing
- Comprehensive reporting system

## Installation & Setup
1. Import the Mendix project file (.mpk)
2. Configure marketplace modules (Excel Importer, Excel Exporter)
3. Set up user roles and security
4. Configure payment gateway integration
5. Deploy to Mendix Cloud or on-premises



## A small tour: https://youtu.be/nA95TN49v1I

**SNAPSHOTS**


**  ANONYMOUS USER**

    HOME PAGE
![image](https://github.com/user-attachments/assets/8cf0a4c4-4138-4b81-a27d-748d55ab0351)


**
  USER INTERFACE**
  
      HOME PAGE
![Screenshot 2025-01-03 211151](https://github.com/user-attachments/assets/b5089cad-1c0e-4af3-9abb-14f5e61e8e17)

  
    SIGN IN PAGE
![image](https://github.com/user-attachments/assets/74275813-0232-47d7-a030-205c015f929f)

    REGISTER PAGE
![image](https://github.com/user-attachments/assets/e3678424-b45f-4c79-ba76-93dfbfd5108f)

    CART PAGE
![image](https://github.com/user-attachments/assets/56857f04-fe68-4716-bb6b-43f90f45d366)


    ADDRESS PAGE
![image](https://github.com/user-attachments/assets/7c5e53b9-51d8-4459-bd1b-7bf5c327cd9e)

    PAYMENT PAGE
![image](https://github.com/user-attachments/assets/4739510f-d79a-4c89-bc00-091b215da891)

    POP UP PAGE
![image](https://github.com/user-attachments/assets/251b41fc-828e-4aa2-a7dc-bd3649bb04c2)

    INVOICE PAGE
![image](https://github.com/user-attachments/assets/03fea6e3-4d45-486f-98e6-040e89c574fb)

    USER PAYMENT HISTORY
![image](https://github.com/user-attachments/assets/d51dab26-8f77-4b6d-a34a-1862561b02ac)


 ** ADMIN INTERFACE**
 
    EDITING PRODUCTS
![image](https://github.com/user-attachments/assets/2ed3f6fe-214d-4f3e-a584-64bf6c3e6736)


    CUSTOMER OVERVIEW
![image](https://github.com/user-attachments/assets/761e6f02-770b-4ed4-b495-9dbf7eb7c37f)

    PAYMENT OVERVIEW
![image](https://github.com/user-attachments/assets/8500d88c-3303-4b04-a5d4-e305c719f9e4)

    EXCELL IMPORTER
![image](https://github.com/user-attachments/assets/d297b405-3e06-45ff-8f7b-c332169cce4d)

    EXCELL EXPORTER
![image](https://github.com/user-attachments/assets/29e514c2-1aed-4f33-885c-870b0fec8103)


  **OWNER INTERFACE**

      ORDERS
![image](https://github.com/user-attachments/assets/6f76f4f5-3c16-4e01-b158-da7884d0af94)

    EDITING ORDER
![image](https://github.com/user-attachments/assets/6d5537b0-6d7e-4cd6-bbc9-7428db5bc75c)

    PRODUCTS TO BE DELIVERED
![image](https://github.com/user-attachments/assets/cadc6565-b7f9-4bde-9366-6c78c2ea193a)

    EDITING PRODUCTS AVAILABILITY
![image](https://github.com/user-attachments/assets/523b35ee-34ed-40b1-b004-e5d98751604c)

    DELIVERY ADDRESS VIEW
![image](https://github.com/user-attachments/assets/d1cb6d66-282e-4481-937c-cb6c91e9ee9d)



  **DELIVERY INTERFACE**
  
    UPDATING DELIVERED SECTION
![image](https://github.com/user-attachments/assets/6e512a81-3a47-445f-82d8-027f9603269b)

    OPTIONS AVAILABLE FOR EDITING
![image](https://github.com/user-attachments/assets/05ccf9db-53ba-4eab-940d-d84206688a6e)

    ITEMS PROODUCT
![image](https://github.com/user-attachments/assets/8175d13b-0e02-4c4b-a00c-bf694ca84993)

    ADDRESS 
![image](https://github.com/user-attachments/assets/9ad95963-4baf-4b1f-ac87-7c0c0761e0e4)
