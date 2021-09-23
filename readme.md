## Step to reinstall
- update .env
- composer install
- php artisan key:generate
- php artisan migrate(make sure database correctly point)
- php artisan serve
- test it out using postman

## List of Route URL untuk test Backend

- Login,g: http://localhost:8000/oauth/token
- Register,g: http://localhost:8000/api/register
- List,g: http://localhost:8000/api/products
- Create,g: http://localhost:8000/api/products
- Show, g: http://localhost:8000/api/products/{id}
- Update,put: http://localhost:8000/api/products/{id}
- Delete,delete: http://localhost:8000/api/products/{id}

