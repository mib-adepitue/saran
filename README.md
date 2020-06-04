<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>


## Informasi Aplikasi
Aplikasi ini di buat Oleh Khaeruddin Asdar sebagai kordinator iptek 2019-2020 cek githubnya <a href="https://github.com/Khaeruddinasdar12">disini</a>
1) Menggunakan Framework Laravel 6
2) Menggunakan Mysql sebagai database
3) Menggunakan Jquery dan yajra datatable (datatable serverside)

Aplikasi ini adalah keluhan pelanggan yang sangat sederhana, bagian atau departmen yang dituju untuk dilaporkan merupakan data statis yang ada di database, namun tidak ada untuk penambahan data di aplikasi.

## Instalasi

Kebutuhan :
* Xampp
* Composer

1. Download Aplikasi ini 
2. Akses foldernya di cmd atau terminal lalu ketikkan (koneksi internet) <blockquote>composer install</blockquote>

6. Setting Env Anda, file .env.example yang ada di dalam folder project Anda, rename file<blockquote> .env.example</blockquote>
 ubah menjadi <blockquote>.env</blockquote>

7. Jalankan Perintah <blockquote>php artisan key:generate/<blockquote>

8. Edit env Anda , perhatikan format berikut :<blockquote>
	DB_DATABASE=nama_db<br>
	DB_USERNAME=user_db<br>
	DB_PASSWORD=password_db
    <blockquote>

9. Karena aplikasi ini memiliki fitur send email, maka atur di env sebagai berikut :<blockquote>
	MAIL_DRIVER=smtp
	MAIL_HOST=smtp.gmail.com
	MAIL_PORT=465
	MAIL_USERNAME=gmail_anda
	MAIL_PASSWORD=password_gmail_anda
	MAIL_ENCRYPTION=ssl
    </blockquote>

10. Pastikan email Anda tidak verifikasi 2 akun, dan less secure app access nya on.
11. Ketikkan perintah <blockquote>php artisan migrate:refresh --seed</blockquote> di cmd atau terminal
12. Ketikkan perintah <blockquote>php artisan serve</blockquote> di cmd atau terminal
13. Ketik <blockquote>localhost:8000/<blockquote> di browser untuk halaman pelanggan
14. untuk mengakses halaman admin, ketik <blockquote>localhost:8000/app/admin</blockquote> akan otomatis tersedia akun sebagai berikut
	login dengan <blockquote>
	email : angelica@gmail.com<br>
	password : 12345678
        </blockquote>
15. Selamat menikmati. 

