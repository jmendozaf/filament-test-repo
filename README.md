```
git clone https://github.com/jmendozaf/filament-test-repo.git && cd filament-test-repo
```
```
composer install
```
```
cp .env.example .env
```
```
php artisan key:generate
```
```
touch database/database.sqlite
```
```
php artisan migrate:refresh --seed
```
```
npm install
```
```
npm run dev
```
> [http://filament-test-repo.test/admin](http://filament-test-repo.test/admin)

> User: admin@admin.com 
> Password: password


