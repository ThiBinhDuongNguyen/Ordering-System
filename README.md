**🍔 OrderMaster: Fast & Secure Ordering System**

Welcome to **OrderMaster: Fast & Secure Ordering System!** This web application makes ordering products easy, efficient, and secure. Built with **Express.js, MongoDB, and EJS**, OrderMaster streamlines the process from placing an order to generating a receipt. Whether you're an admin managing orders or a customer making a purchase, OrderMaster ensures a **smooth** and **intuitive experience** every time.

**🌟 Key Features**

**Admin & Customer Management**

- **Admin Login**: Secure login system for admins to manage and review all orders.
- **User Sessions**: Sessions keep track of admins' logged-in status for easy access to ordering features.
  
**Dynamic Ordering System**

- **Order Form**: Easy-to-use form for customers to select products, input their information, and place orders.
- **Receipt Generation**: After submitting the order, a detailed receipt with total price, taxes, and a breakdown of purchased products is instantly generated.
- **Validation**: Custom validation for phone numbers and required fields ensures only correct input is accepted.
  
**Order Processing**

- **Product List & Prices**: Available products (Mango, Berry, and Apple) are listed with fixed prices, and customers can select their desired quantity.
- **Tax Calculation**: Automatically calculates sales tax and the grand total based on order data.
- **Minimum Purchase Check**: Enforces a $10 minimum purchase to ensure users make significant orders.
  
**View All Orders**

- **Order List:** Admins can view all orders placed by customers, including their contact info, products bought, and total amounts.
  
**🔒 Secure & User-Friendly**

- **Session-Based Authentication**: Ensures only authorized users can access the admin panel and place orders.
- **Responsive UI**: Clean, intuitive design with **EJS** templating to render data dynamically.
  
**🛠️ Technology Stack**

- **Backend Framework**: Express.js
- **Database**: MongoDB
- **Frontend**: EJS (Embedded JavaScript templating)
- **Session Management**: Express-session for secure user login
- **Validation**: Express-validator for input validation
- **Routing**: Dynamic routes for order form, receipt generation, login, and order history
  
**📋 How to Use**

**Admin Login**

1. Navigate to the homepage (/).
2. Enter the admin credentials (username & password) to access the order management system.
   
**Placing an Order (For Customers)**

1. Visit the **Order** page (/order).
2. Fill out the order form with your name, phone number, and quantity of products you wish to buy (Mango, Berry, Apple).
3. Submit your order. A receipt will be generated that shows the details of your purchase.
   
**Viewing All Orders (For Admins)**
1. Visit the **All Orders** page (/allorders).
2. Review all customer orders, including the total prices and individual product quantities.

**🚀 Future Enhancements**
**OrderMaster** is just getting started, and we have plenty of exciting updates planned:

- **Multi-Level Admin Permissions**: Allow different levels of admin access (e.g., manager, customer service).
- **Email Notifications**: Automatically send order confirmations and receipts to customers after they place an order.
- **More Products & Categories**: Add more products, including discounts or special promotions.
- **Order History**: Implement an order history feature for customers to track their previous purchases.
- **Enhanced Security**: Strengthen user authentication with password hashing and JWT tokens.
- **Payment Integration**: Add payment gateway integration for seamless transactions.
- **Mobile Responsiveness**: Optimize for mobile users for easy browsing and ordering on the go.
  
**🏁 Getting Started**

1.Clone or download the repository.

2.Install dependencies: npm install

3.Ensure MongoDB is installed and running.

4.Start the server: node app.js

5.Access the app at http://localhost:2100/.

**💬 Feedback and Contributions**
We would love to hear from you! Whether it's a suggestion, bug report, or contribution, feel free to get in touch. We're always improving OrderMaster to make it the best experience possible for admins and customers alike.
![Screenshot 2024-12-18 141656](https://github.com/user-attachments/assets/cac14e01-0881-4874-bf0f-3bd3208a4292)

![Screenshot 2024-12-18 141709](https://github.com/user-attachments/assets/ab1c9e26-988e-4291-ae3e-68c657ac408f)

![Screenshot 2024-12-18 141731](https://github.com/user-attachments/assets/cbfd1044-5fbf-4433-95cd-fe009397fd49)

![Screenshot 2024-12-18 141745](https://github.com/user-attachments/assets/0c24516b-778f-4417-b9e8-ed539baa42e1)




