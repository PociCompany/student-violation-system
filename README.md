# Student violation system

## Project based on Laravel 9

# How to install this project

- Clone this project
- Go to the folder application using cd command on your cmd or terminal
- Run composer update on your cmd or terminal
- Run npm install on your cmd or terminal
- Run cp .env.example .env using your terminal
- Open your .env file and change the database name (DB_DATABASE) to whatever you have, username (DB_USERNAME) and password (DB_PASSWORD) field correspond to your configuration.
- Run php artisan key:generate
- Run php artisan migrate
- Run php artisan db:seed (Opsional)
- Run php artisan storage:link
- Run php artisan serve
- Run npm run dev on another terminal

If the picture doesn't show up after you upload it you can go to .env change "APP_URL=http://localhost:8000" 8000 is your port when your do php artisan serve
