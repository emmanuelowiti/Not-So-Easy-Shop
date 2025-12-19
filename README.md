# Not-So-Easy-Shop

Not-So-Easy shop is a Spring Boot based  e-commerce API that allows users to browse products, manage categories, add items to a shopping cart and complete orders. The API supports user authentication via JWT tokens and role based access control for administrative tasks.

This project involves:

1. Fixing existing bugs in the API.

2. Implementing new features such as category management.
   
3. Writing unit tests and debugging.

4. Demonstrating functionality using Postman and the front-end.

## Features.

## User Authentication

* Register new users

* Login existing users

* JWT-based authentication

## Product Management

* Browse products by Category

* Search and Filter products by price

* Admin only endpoints for adding and updating products

## Setup Pre-requisites
* Java 17+ (Project tested on Java 25)
  
* Maven
  
* MySQL
  
* Postman / Insomnia (for API testing)

## Known Bugs And Fixes

* Bug 1: Incorrect Comparison Logic and searh was ignoring max price

* Solution: Altered the SQL query to properly handle both Min and Max prices




<img width="568" height="265" alt="Screenshot 2025-12-19 005121" src="https://github.com/user-attachments/assets/9d0b2a0c-911c-44a0-be4a-fe83808d05b2" />


* Bug 2 solution: Fixed product update functionality by correcting the controller to call the update() DAO method instead of create().

<img width="805" height="156" alt="Screenshot 2025-12-19 005839" src="https://github.com/user-attachments/assets/476e0d5a-f6d4-4603-8f32-3e0b4cf8a193" />



## Web-Browser Snippet

## Home page

A glossary of the various items in the E-Commerce shop.


https://github.com/user-attachments/assets/faac7f10-1313-4901-8034-293b28438aaa


## Cart

A peak into the items added to the Cart

<img width="1468" height="873" alt="Screenshot 2025-12-18 223526" src="https://github.com/user-attachments/assets/9d106039-3b27-4453-9b04-5b10f30fdff5" />


## Future Enhancements
1. A functional Checkout and Cart system
2. Product rating and Reviews
3. Shipping Costs and Tax Calculation
4. Payment Gateway
5. Inventory Management
6. Guest Checkout option


# 👨‍💻 Author

Emmanuel Owiti

