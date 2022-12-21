Saya menggunakan library Socialite pada pengerjaan tugas ini

Saya membuat fitur login, register, login with google, forgot password (reset password dikirim melalui email), dan verifikasi saat register (melalui email)

Langkah Instalasi Projek :

1. Unzip project
2. Buka projek dan pastikan berada dalam directory project
3. Jalankan "composer update"
4. Jalankan "composer require laravel/socialite"
5. Isi GOOGLE_CLIENT_ID dan GOOGLE_CLIENT_SECRET, dan ubah DB_DATABASE pada file '.env'
6. Jalankan "php artisan migrate:fresh" pada terminal
7. Jalankan "php artisan serve" 

Saya mengosongkan mail_username dan mail_password dan dapat diisi sendiri

Berikut adalah homepage url & callback url-nya
Homepage URL => http://127.0.0.1:8000
Callback URL => http://127.0.0.1:8000/auth/google/callback
MAIL_FROM_ADDRESS => putralukasa@gmail.com
