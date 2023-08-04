### BackEnd menggunakan Express 
### TOKO BELANJA

 "Aplikasi ini terdapat seseorang admin dan banyak customer yang memiliki wewenang untuk melakukan proses **CRUD** terhadap category dan product hanyalah admin saja. Sedangkan customer hanya bisa melakukan proses pembelian product dan melihat data transaksi pembeliannya, customer juga dapat melakukan top-up saldo untuk menambahkan saldo."


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
