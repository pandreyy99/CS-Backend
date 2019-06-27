# CS-Backend
A simple backend for CS-APP.

Backend setup (backend directory)
You will need php and composer installed on your system.

1. Create a file named .env in the main directory with your database credentials. It should be identical to .env.example file.
    - Install all the things needed with:
    ``` composer install ```
    
2. Migrate the table for products to your database with:
    ``` php artisan migrate ```
    
3. Create some random entries with:
    ``` php artisan db:seed ```

4. Start the server with:
   ``` php -S localhost:8000 -t public ```

You can use the following routes:

GET /items <br/>
GET /item/{id} <br/>
POST /item <br/>
PUT /item/{id} <br/>
DELETE /item/{id} <br/>
