### BackEnd menggunakan Express 
### TOKO BELANJA

Aplikasi "Tokobelanja" adalah sebuah back-end API yang ditulis menggunakan JavaScript dengan runtime Node.js, serta menggunakan framework Express.js dan database PostgreSQL. Aplikasi ini dirancang untuk mendukung fitur manajemen kategori dan produk, yang hanya dapat diakses oleh admin untuk melakukan proses CRUD (Create, Read, Update, Delete). Sementara itu, customer dapat menggunakan API untuk melakukan pembelian produk, melihat data transaksi pembelian mereka, serta melakukan top-up saldo untuk menambahkan saldo di akun mereka.

Proyek ini fokus pada pengembangan back-end API yang handal dan aman, memastikan bahwa admin dan customer memiliki wewenang yang sesuai untuk berinteraksi dengan aplikasi. Melalui aplikasi ini, kami berusaha memberikan pengalaman belanja yang lebih efisien dan nyaman bagi para pelanggan. Penggunaan ORM Sequelize juga mendukung pengelolaan data yang efisien dalam aplikasi ini.


* * *
##
# User
- Register (POST) : /users/register/
- Login (POST) : /users/login/
- Topup (PATCH) : /users/topup
- Delete (DELETE) : /users/:id

# Kategori
- GetAll (GET) : /categories/
- Create (POST) : /categories/
- Delete (DELETE) : /categories/:id


# Product
- Create (POST) : /products/
- GetAll (GET) : /products/
- UpdateAll (PUT) : /products/:id
- UpdateById (PUT) : /products/:id
- Delete (DELETE) : /products/:id


# Transaction-History
- Create (POST) : /transactions/
- GetAll (GET) : /transactions/user
- Admin (GET) : /transactions/admin
- TransactionId (GET) : /transactions/:id
