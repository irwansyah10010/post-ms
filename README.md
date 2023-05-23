# post-ms
Project post microservice menjadi parent dari pos, dalam `post-ms` terdapat 5 submodule yang terdiri dari 4 service project post dan 1 show server microservice.


## Skema Microservice
<img src="https://raw.githubusercontent.com/irwansyah10010/post-ms/main/diagram%20skema%20pos.png" alt="Markdownify" width="600" height="400">


Sebagai catatan, kami menggambarkan relasi yang terhubung pada setiap service dan aktifitas yang mesti dimulai terlebih dahulu sebelum menggunakan API pada setiap service tersebut. Berikut adalah rincian dari setiap service pada projek `pos`:
  - `user-service`: sebuah service yang menampung aktifitas user(CRUD dan juga termasuk login)
  - `customer-service`: sebuah service yang menampung aktifitas customer(CRUD)
  - `order-service`: sebuah service yang menampung aktifitas order(CRUD)
  - `discovery-ureka`: sebuah service untuk menampilkan service yang aktif pada project pos


Untuk detail mengenai API apa saja yang tersedia, anda bisa langsung mengakses service dari masing-masing service terkait.



