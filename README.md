# fullstack-food-ordering-app

### Developed a food ordering app using Java Spring Boot framework for the backend and React JavaScript library for the frontend.

<br/>

## Technology Stack
•	Spring Boot 3

•	Spring Security 6

•	JWT

•	Spring Data JPA (Hibernate 6)

•	MySQL Database

•	REACT JS

•	Testing REST APIs using Postman Client

•	Intellij 

•	Visual Studio Code

<br/>

### Backend:
•	Spring Boot – Building RESTful APIs

•	Hibernate & Spring Data JPA – Simplify CRUD operations

•	MySQL - Relational database for structured data storage and retrieval

### Frontend:
•	React JS – Building user interfaces, allowing for responsive and engaging user experiences

•	HTML & CSS – Create visually appealing layout, ensure usability and accessibility

### Secure REST APIs:
•	Implemented JWT for stateless authentication

•	Enforcing authentication and role-based authorisation with Spring Security

### Method-Level Security: 
•	Utilizing the @PreAuthorize annotation to control access to specific methods based on user roles and permissions

### Role-Based Access Control:
•	Implemented a role-based authorization system, allowing different access levels for various user roles (e.g., admin, regular user)

### Database Authentication:
•	Set up database authentication using spring security to authenticate users against a database



https://github.com/user-attachments/assets/5eaeda5e-f2a3-46c7-b6f9-1bcefac75575

## Functionalities:

All users can register and log in to the application, with their credentials securely verified against the database. Whether registered or not, users can view product listings, add item their cart, view cart items, delete item from the cart, clear all items from the cart, increase quantity, decrease quantity, adjust quantities, calculate the total amount.
Registered users can view their profile page.
Admin user can manage product listings by adding or deleting items and view their own profile page.

### Non-Registered Users:

1. View Product Listings:

Browse available products without the need to log in.

2. Add Items to Cart:

Select products to add to their shopping cart.

3. Modify Quantity:

Increase or decrease the quantity of items in the cart.

4. Delete Single Item:

Remove an individual item from the cart.

5. Clear Cart:

Empty the entire shopping cart if desired.

6. Total Sum of Cart Items:

View the total price of all items currently in the cart.

7. Proceed to Checkout:

Move to the checkout page to finalize the purchase.

<br/>

### Registered Users:

1. View Profile Page:

Access personal information.

<br/>

### Admin User:

1. Manage Product Listings:

Add new products, edit existing product details, or remove products.

2. View Profile Page:

Access and manage their admin profile information.

<br/>


Build Add Product REST API

Build Get All Product REST API

Build Delete Product by Id REST API

Build Register REST API

Build Login REST API

Build User Profile REST API

Manage cart items in React frontend using React hook (useContext), using createContext hook to create context that holds the cart state and provides methods for adding, removing and clearing items, useReducer hook to manage the cart state, and useEffect to load and saving cart data.


### Home Page:

![foodapp_home](https://github.com/user-attachments/assets/7712ec9b-9535-49dd-b772-bf1c20e37d81)

<br/>

<br/>

### Cart Page:

![foodapp_cart_items](https://github.com/user-attachments/assets/d0f5e832-28c5-467f-980c-f9f4ec4158b9)

<br/>

![foodapp_cart_0](https://github.com/user-attachments/assets/12884c25-76a3-4f5f-9ea9-59916b87b829)

<br/>

<br/>

### Register Page:

![foodapp_register](https://github.com/user-attachments/assets/ad845996-0cda-4f93-b306-c1563856f28f)

<br/>

<br/>

### Login Page:

![foodapp_login](https://github.com/user-attachments/assets/eca601ad-0a04-4072-b724-ffb6c79c669b)

<br/>

<br/>

### User Profile Page: 

![foodapp_profile](https://github.com/user-attachments/assets/69aabce4-a8cf-47ea-933c-69ccb10cbcad)

<br/>

<br/>

### Admin User Page:

![foodapp_admin](https://github.com/user-attachments/assets/9b76ada3-767a-457d-84ea-3b1233947f1e)

<br/>

<br/>

### Add Product Page:

![foodapp_add_menu](https://github.com/user-attachments/assets/73244f94-d717-4a44-aa31-af94c8e4b382)

<br/>

![foodapp_added](https://github.com/user-attachments/assets/9ce79486-a8b8-46f9-830b-86e0f872b885)

<br/>

<br/>

### Delete Product:

![foodapp_delete](https://github.com/user-attachments/assets/53880ac2-8300-44b0-a11c-77005922a8d5)

<br/>

<br/>

![foodapp_after_delete](https://github.com/user-attachments/assets/64eaddbf-9fa7-4035-9af9-73c8dc77d299)
