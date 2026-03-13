# Swagger Petstore – API Testing with Postman

This repository contains my API testing collection for the **Swagger Petstore** API. It shows how I use Postman and JavaScript tests to check that a REST API works as expected.

## What is included

- Tests for **Pets**, **Store orders**, and **Users**  
  These requests cover the main features of the Swagger Petstore API, like adding pets, placing store orders, and creating or deleting users.

- Successful and failing cases (good input, bad input, not found)  
  I send both valid data (which should work) and invalid data (which should fail) to check that the API returns the right success or error codes, such as 200, 400, and 404. 

- Checks for status codes, response data, and headers  
  Each test verifies that the HTTP status code is correct, the response body contains the expected values, and important headers like `Content-Type` are set properly. 

- Clear `pm` test scripts that are easy to read and change  
  The tests use Postman’s `pm.test` and `pm.expect` functions so other people can quickly understand what is being checked and update the tests when the API changes. 


## How to run the tests

1. Import the Postman collection JSON file into Postman.
2. Make sure you are connected to the internet.
3. Run single requests or use the **Collection Runner** to run all tests.

## Skills shown

- Working with REST APIs and HTTP status codes
- Writing automated API tests in **Postman** using **JavaScript**
- Organizing tests in folders for different features
- Verifying both behaviour and returned data
