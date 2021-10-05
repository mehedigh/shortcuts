Mac laravel migrate solution:

Add this in config > database
DB_SOCKET=/Applications/MAMP/tmp/mysql/mysql.sock

Then run on terminal: 
php artisan optimize OR php artisan config:cache
