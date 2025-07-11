
<p align="center">
 <h1 align="center">Sales_Website</h1>
</p>



## Introduction

Here is my Java source code for Sales website

## Main features
Main Features
-Login and Authorization: Secure user authentication and role-based access control.

-Account Registration: Allows users to create new accounts.

-Forgot Password: Mechanism to recover account access via email.

-Product Management (Seller): Sellers can add, update, and manage their products.

-Account Management (Admin): Admins can view and manage all user accounts in the system.

-Product Search by Price: Search products by price ranges (Min, Max, Under 100, 100-200, Above 200).

-Product Search by Name: Search products using their names.

-Product Selection and Payment: Users can select products and proceed to payment.

-Cart Management: Users can add, remove, or update items in their shopping cart.

-Invoice Management: Export all invoices, filter invoices by date, and export to Excel.
-Monthly Revenue Statistics: View revenue reports aggregated by month.

## Detailed Use Cases





-Manage All Accounts





Actors: Admin



Description: Admins can view, edit, or delete user accounts.



Precondition: Admin must be logged in.



Postcondition: Account changes are saved in the system.



Manage Personal Information





Actors: User



Description: Users can update their profile details (e.g., name, address, email).



Precondition: User must be logged in.



Postcondition: Profile updates are reflected in the system.


-View Store Products





Actors: User, Guest



Description: Users or guests can browse the store’s product catalog.



Precondition: None.



Postcondition: Product list is displayed.



-Search Products





Actors: User, Guest



Description: Search for products by name or price range.



Precondition: None.



Postcondition: Matching products are displayed.



-Place Product Orders





Actors: User



Description: Users can select products, add them to the cart, and complete the purchase.



Precondition: User must be logged in and have items in the cart.



Postcondition: Order is created, and a confirmation email is sent.



-Manage Shopping Cart





Actors: User



Description: Users can add, remove, or update quantities of items in their cart.



Precondition: User must be logged in.



Postcondition: Cart is updated.



-View Statistics





Actors: Admin



Description: Admins can view revenue and sales statistics by month.



Precondition: Admin must be logged in.



Postcondition: Statistics are displayed.



-Manage Seller Products





Actors: Seller



Description: Sellers can add, update, or remove their product listings.



Precondition: Seller must be logged in.



Postcondition: Product changes are saved.



-Create Account





Actors: Guest



Description: Guests can register for a new account.



Precondition: None.



Postcondition: New account is created, and user receives a confirmation email.



-Forgot Password





Actors: User



Description: Users can request a password reset link via email.



Precondition: User must provide a registered email.



Postcondition: Password reset link is sent to the user’s email.

## User Interface Layouts





-Home Page





Displays featured products, promotions, and navigation to other sections.



-Store Page





Lists all products with filtering and search options.



-Login Form





Input fields for username/email and password, with a "Forgot Password" link.



-Sign Up Form





Fields for username, email, password, and other required information.



-Forgot Password Form





Input field for email to receive a password reset link.



-Update Personal Information Page





Form to edit user profile details like name, address, and contact information.



-Product Details Page





Displays detailed information about a product, including price, description, and an "Add to Cart" button.



-Cart Management Page





Lists items in the cart with options to update quantities or remove items.



-Order Form





Form to input shipping and payment details for completing an order.



-Account Management Page





Admin interface to view and manage all user accounts.



-Product Management Page





Seller interface to add, edit, or delete product listings.



-Statistics Page





Displays monthly revenue and sales statistics for admins.



Order Confirmation Email Structure





Email template with order details, including items, total cost, and estimated delivery.



Password Reset Email Structure





Email template with a link to reset the user’s password.



-Add Product Form





Form for sellers to input product details (e.g., name, price, description, images).



-Update Product Form





Form to edit existing product details.



-Add Account Form





Admin form to create new user accounts.



-Monthly Revenue Interface





Displays charts and tables for monthly revenue.



-All Invoices Interface





Lists all invoices with options to filter by date and export to Excel.
* **Java,Html,Css,Bootstrap,jQuery**
* **Communications method with database:JDBC,JPA**
* **Model:MVC**
* **Website functions:Java Servlet,Ajax** 
