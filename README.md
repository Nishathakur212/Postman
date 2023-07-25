This repository contains my Postman Collections :

Trello API Testing Collection

Description:

This repository contains a comprehensive set of API testing requests for the Trello API. Trello is a popular collaboration and project management tool, and this Postman collection allows you to automate the testing process for various Trello API endpoints.

Requirements:

Postman: Ensure you have Postman installed on your machine. If you don't have it yet, you can download it from the official website: https://www.postman.com/downloads/

Getting Started:

Clone this repository to your local machine using  "git clone https://github.com/yourusername/trello-postman.git".
Launch Postman and import the collection file Trello.postman_collection.json from the cloned repository.
To import the collection, click on the "Import" button in Postman and select the JSON file.
Once imported, you should see the collection named "Trello API Collection" in your Postman workspace.

Usage:

1. Open the imported collection in Postman.
2. Configure any necessary environment variables, such as base_url, api_key, token, etc. These variables may be required for authentication and accessing specific Trello boards and cards.
3. Review the requests in the collection and ensure that they match the endpoints of the Trello API you wish to test.
4. Run the entire collection or individual requests to execute API tests on Trello.
5. For individual requests, click on the request and then click the "Send" button to execute it.
6. For the entire collection, click on the collection folder and then click the "Run" button.


Grocery Store API
# Simple Grocery Store API

This API allows you to place a grocery order which will be ready for pick-up in the store. This API provides various endpoints to manage a virtual grocery store, allowing developers to access and manipulate data related to products, categories, orders, and customers. It is designed to streamline interactions with the grocery store's database and facilitate the development of applications that integrate with the store's services.

The API is available at `https://simple-grocery-store-api.glitch.me`

Alternative URL: `http://simple-grocery-store-api.online/` (HTTP only!)

## Endpoints

- [Status](#Status)
- [Products](#Products)
  - [Get all products](#Get-all-products)
  - [Get a product](#Get-a-product)
- [Cart](#Cart)
  - [Get a cart](#Get-a-cart)
  - [Get cart items](#Get-cart-items)
  - [Create a new cart](#Create-a-new-cart)
  - [Add an item to cart](#Add-an-item-to-cart)
  - [Modify an item in the cart](#Modify-an-item-in-the-cart)
  - [Replace an item in the cart](#Replace-an-item-in-the-cart)
  - [Delete an item in the cart](#Delete-an-item-in-the-cart)
- [Orders](#Orders)
  - [Get all orders](#Get-all-orders)
  - [Get a single order](#Get-a-single-order)
  - [Create a new order](#Create-a-new-order)
  - [Update an order](#Update-an-order)
  - [Delete an order](#Delete-an-order)
- [API Authentication](#API-Authentication)
  - [Register a new API client](#Register-a-new-API-client)

Response Format:
The API returns responses in JSON format. Each response will contain relevant data along with status codes for error handling.

Authentication:
Authentication is required to access certain endpoints. The API uses OAuth 2.0 for authentication. To authenticate, obtain an access token by following the authentication process outlined in the API documentation. Include the access token in the headers of your API requests using the Authorization header.







