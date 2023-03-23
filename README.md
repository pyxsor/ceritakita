# ceritakita
Sebuah repository untuk terus belajar, kali ini dengan Laravel 10 

Our Goal:
1. Membuat Sebuah Laman Coret"an Untuk Menuliskan cerita sederhana
2. Terdapat user login
3. Sementara itu dulu 

btw ternyata laragon enak uyy

<h3 align="left">Let's Go!!!</h3>

<h4>Risalah Build Apps Stock Inventory</h4>

1. Install Laravel
   ```
   composer create-project laravel/laravel ceritakita
   ```
2. Setting .env
   ```
   DB_CONNECTION=mysql
   DB_DATABASE=ceritakita
   ```
3. Install Laravel Breeze
   ```
   composer require laravel/breeze --dev

   php artisan breeze:install react

   npm run dev

   php artisan migrate
   ```
   Make sure no error or something look sus... hehe
4. Register Akun anda sendiri?
   Laravel Breeze sudah menyediakan berbagai fitur autentikasi yang bisa dengan mudah di modifikasi dan digunakan !