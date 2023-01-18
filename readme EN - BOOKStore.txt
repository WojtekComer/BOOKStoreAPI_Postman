BOOKSTORE.postman_collection


1. 'BOOKStore' project tests a sample REST API 'Simple Books API' avaliable at https://simple-books-api.glitch.me
   Documentation available at https://github.com/vdespa/introduction-to-postman-course/blob/main/simple-books-api.md

2. Project description:
   This project is suppose to test the possibility of:
   - reading a book list or reading detailed info of a single book based on its ID
   - creating or reading a new book order
   - updating or deleting book order
   - reading a list of all created orders.

   Project uses basic CRUD methods: POST, READ, PUT(PATCH), DELETE and Bearer Token authorization which is set for the whole Collection 
   in 'bearerToken' variable.
   
   'url', 'bookID', 'orderID' and 'customerName' are defined as Colletion varaibles and are next passed to the consecutive requests.

   'API Authentication' request is run first in order to obtain the token and then stores it in the 'bearerToken' Collection variable .     

3. The purpose of this simple 'end-to-end' project is to present some basic POSTMAN REST API testing skills that I acquired during my 
   online tutorial self-studying. 

4. Scope of knowledge:
   - Creating collections, requests, basic tests and scripts.
   - Using 'Collection Runner'
   - Creating and accessing variables at different levels (inside body, endpoints, tests, query parameters, path parameters, collections)
   - Creating simple scripts:
     > Passing data between requests and accessing variables at different leves.
     > Creating simple tests
     > Console logging
     > Using Snippets
   