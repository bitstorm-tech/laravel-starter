# Bitstorm Laravel Starter

## Initial steps before first use
1. Install composer dependencies
```
composer install
```

2. Create .env
```
cp .env.example .env
```

3. Generate application key
```
php artisan key:generate
```

4. Install NPM dependencies
```
npm install
```

5. Migrate database
```
php artisan migrate
```

6. Reinitialize Git
```
rm .git -rf && git init
```

All in one:
```
rm .git -rf && git init
composer install
cp .env.example .env
php artisan key:generate
npm install
php artisan migrate
```

## Dev Server
Run the dev server with `php artisan solo`.
