# Bitstorm Laravel Starter

## Initial steps before first use
1. Re-init git repository
```
rm .git -rf && git init
```

2. Update dependencies
```
composer update
```
 
3. Install composer dependencies
```
composer install
```

4. Create .env
```
cp .env.example .env
```

5. Generate application key
```
php artisan key:generate
```

6. Install NPM dependencies
```
npm install
```

7. Migrate database
```
php artisan migrate
```

All in one:
```
rm .git -rf && git init
composer update
composer install
cp .env.example .env
php artisan key:generate
npm install
php artisan migrate
```

## Dev Server
Run the dev server with `php artisan solo`.
