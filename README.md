# Warehouse Management System
A WMS made using the Laravel PHP framework.

![Screenshot of web page](https://github.com/fmahaztra/warehouse-management-system/blob/master/screenshot.png "Screenshot of web page")

# Features

* Login/logout
* Email password recovery
* Write data to database
* Update data in database
* Read data from database
* Delete data from database

# Example Usage

Create an .env file with the following format, with the DB and MAIL variables being the most important:

```
APP_NAME=Laravel
APP_ENV=local
APP_KEY=
APP_DEBUG=true
APP_LOG_LEVEL=debug
APP_URL=http://localhost

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret

BROADCAST_DRIVER=log
CACHE_DRIVER=file
SESSION_DRIVER=file
QUEUE_DRIVER=sync

REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_DRIVER=smtp
MAIL_HOST=smtp.mailtrap.io
MAIL_PORT=2525
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=

```

Migrate tables with ```php artisan migrate```. Install dependencies via ```composer install``` and ```npm install```. Use a MySQL server.


