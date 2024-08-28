# roadmap cara bikin aplikasi expressjs

## Persiapan
1. init project `pnpm init`
2. akan muncul file `package.json`
3. buat file `index.js`
4. install package `expressjs, nodemon, mysql2`
5. ubah package.json `script : {"dev" : "nodemon index.js"}`
6. ubah package.json `type : module`
7. edit file index.js dan tambahkan kode express dan tentukan portnya
8. buat folder folder yang dibutuhkan misalkan
		- routes
		- controllers
		- models
		- config

## Design database
1. buat database
2. menentukan field table

## Konfigurasi
1. buat file konfigurasi database di folder config
2. tentukan username, password dan nama database
3. jika menggukanan `.env` buat juga file `.env`nya

## mulai development
1. mengisi file pada struktur folder routes yang telah dibuat misalkan isi folder routes : userRouter.js, postRouter.js
2. ujicoba apakah route sudah berhasil dipanggil dari postman
3. buat file controller pada struktur folder controller yang telah dibuat misalkan userController.js dan lainnnya
4. tambahkan kode controller ke dalam routes
5. ujicoba apakah controller sudah berhasil atau bisa diakses jika memanggil router
6. buat file model yang menggunakan konfigurasi dari `config/database.js` dan buat seluruh method yang dibutuhkan
7. implementasi model yang dibuat ke controller
8. ujicoba kembali secara menyeluruh
9. tambahkan middleware cors bila dibutuhkan agar API bisa diakses dari frontend
