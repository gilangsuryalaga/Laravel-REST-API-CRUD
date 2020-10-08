# Laravel-REST-API-CRUD
An REST API written using PHP and Laravel.This project includes Migrations,Model And Controllers, CRUD Fuctionality

# Requirements
* PHP
* Composer
* Xampp
* Postman

## Installation
    Follow these steps:
     1. Clone or download this project
     2. Create Database with the name 'rest-api' but, you can create the name with whatever you want but make sure to change the           .Env file
     3. Type:
     ...
     php artisan migrate
     ...
    4. Make sure there's no error
  
  ## How to use
    Follow these steps:
    1. Make sure your Xampp is On
    2. Open this project to your Code Editor
    3. Type:
    ...
    php artisan serve
    ...
    4. Open your Postman App
    5. Click the 'New' Button
    6. Paste The URL
    ...
    (Your Localhost URL)/api/products
    ...
    
   ## Show All Product
    Follow these steps:
      1. Paste The URL
        ...
        (Your Localhost URL)/api/products
        ...
      2. Make Sure it is 'GET'
      3. Click 'Sends' button
      
   ## Create Product
      Follow these steps:
        1. Paste The URL
          ...
          (Your Localhost URL)/api/products
          ...
        2. Change it to 'POST'
        3. Click 'Body' then choose 'raw'
        4. Don't Forget to Change it to JSON
        5. Type:
        ...
        {
          "name": "(Product Name)",
          "description": "(Product description)",
          "price": "(Product Price in number)",
        }
        ...
        6. Click the 'Send' Button
        
   ## Update Product
      Follow these steps:
        1. Paste The URL
          ...
          (Your Localhost URL)/api/products/(Product ID)
          ...
        2. Change it to 'PATCH'
        3. Click 'Body' then choose 'raw'
        4. Don't Forget to Change it to JSON
        5. Type:
        ...
        {
          "name": "(Product Name)",
          "description": "(Product description)",
          "price": "(Product Price in number)",
        }
        ...
        6. Click the 'Send' Button 
       
   ## Delete Product
     Follow these Steps:
       1. Paste The URL
          ...
          (Your Localhost URL)/api/products/(Product Id)
          ...
        2. Change it to 'DELETE'
        3. Click the 'Send' Button
