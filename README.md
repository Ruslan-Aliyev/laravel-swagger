# Mandatory steps

`composer require darkaonline/l5-swagger`

`php artisan vendor:publish --provider "L5Swagger\L5SwaggerServiceProvider"`

`php artisan make:controller Api/UserController --resource`

See the annotative comments in `app/Http/Controllers/Controller.php` & `app/Http/Controllers/Api/UserController.php` <-- Those are the bare minimum.

`php artisan l5-swagger:generate`

`php artisan serve`

Visit `http://127.0.0.1:8000/api/documentation`

# Tutorials

- Good tutorial: https://blog.quickadminpanel.com/laravel-api-documentation-with-openapiswagger 
	- https://github.com/LaravelDaily/Laravel-OpenAPI-Swagger-Documentation-Example
- An up-to-date example: https://github.com/WailanTirajoh/laravel-swagger-example