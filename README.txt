To launch this app you have to:
1. in back folder open a terminal and run composer update then composer install.
2. run php artisan storage:link
3. move the public folder to /back/storage/app and unzip the productImages which is in public
4. update the /back/.env and put your db connection credentials
5. we have create some products, there are in the sql file in db forlder, import them in your mysql
   the db name must be called "ecommerce"
6. run php artisan serve
7. in front folder, open a terminal and run npm i
8. verify that the proxy property in package.json is "http://localhost:8000" if you launch the app in localhost else it must be the proxy of the server
9. run npm start
