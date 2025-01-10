
#### Install composer dependencies

```
composer install
```

#### NPM dependencies and build assets

```
npm install
npm run build
```

#### Add .env Variables

Rename the `.env.example` file to `.env` and add your database values. Change driver and port as needed.

```
DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```

#### Run Migrations

```
php artisan migrate
```

#### Seed Database (Optional)

for  users, jobs and bookmarks

```
php artisan db:seed
```

the test account:

-   Email: test@test.com
-   Password: 12345678

#### Run Server


```
php artisan serve
```
