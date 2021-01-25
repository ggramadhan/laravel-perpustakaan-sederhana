# Sistem Peminjaman Buku (Perpusku)
## Instalasi
 - jalankan composer update
 - copy dan pastekan .env copy.example
 - jalankan php artisan key:generate
 - buat database di phpmyadmin dengan nama 'perpusku_db'
 - melakukan setup .env sesuaikan dengan nama database yg dibuat beserta username dan password
 - jika sudah lakukan migrasi dengan cara php artisan migrate
 - lalu melakukan seeding php artisan db:seed
 
 ### Default akun
 username : admin123 | password : admin123 <br>
 username : user123 | password : user123

Terimakasih!
