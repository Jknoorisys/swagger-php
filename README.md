# Steps to Integrate swagger-php in Laravel8
1. composer require "darkaonline/l5-swagger"
2. php artisan vendor:publish --provider "L5Swagger\L5SwaggerServiceProvider"
3. Connect Database.
4. Run php artisan migrate
5. php artisan l5-swagger:generate
6. http://127.0.0.1:8000/api/documentation/v1 (available in config/l5-swagger.php)
