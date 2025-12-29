This project contains API testing for Demoblaze application using Postman. The tests cover basic CRUD operations, response validation, and automation using Postman collections.

Demoblaze is an e-commerce demo website commonly used for testing API and UI automation.

Project Features

Test GET, POST, PUT, DELETE requests

Validate status codes, response body, and headers

Use Postman environments for flexibility

Automated test scripts in Postman

Supports collection runner for bulk testing

API Endpoints Tested
HTTP Method	Endpoint	Description
GET	/products	Get all products
GET	/products/{id}	Get product by ID
POST	/users	Create a new user
POST	/cart/add	Add product to cart
DELETE	/cart/delete/{id}	Delete product from cart

⚠️ Replace {id} with actual product or cart ID.

Postman Setup

Download and install Postman

Import the collection from this repository:
Demoblaze_API_Testing.postman_collection.json

Import the environment (optional):
Demoblaze_API_Env.postman_environment.json

Update baseUrl in environment:

https://demoblaze.com/api


Run the collection or individual requests.

How to Run Tests

Open Postman

Select the Demoblaze API Testing collection

Choose the environment (Demoblaze API Env) if available

Click Run or execute requests individually

Check the Tests tab for validation results

Test Scenarios Covered

Verify GET requests return 200 OK and correct data

Verify POST requests create new records successfully

Verify DELETE requests remove data properly

Validate response time and headers

Validate data types in response body
