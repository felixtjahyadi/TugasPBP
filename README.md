1. Kaitan dari url.py, views.py, models.py, dan berkas HTML terdapat pada kaitan dengan alur proses permintaan sesuai dengan bagan. Suatu permintaan yang masuk pertama-tama akan di proses melalui urls.py yang kemudian tersalurkan ke views.py ke fungsi yang sama di dalamnya. Jika dalam proses membutuhkan suatu keterlibatan database, maka views.py akan melakukan atau memanggil query (permintaan data ke database) ke models.py yang akan melakukan transaksi data dengan database dan dikembalikan kembali ke views.py. Dari views.py ini, hasil dari proses akan dipetakan ke dalam HTML yang sudah didefinisikan.

![IMAGE](bagan.jpg)

2. Virtual environment adalah suatu tools atau alat yang memungkinkan kita untuk membuat suatu lingkungan virtual yang terisolasi mengapa? Pada saat kita membuat aplikasi dan aplikasi tersebut berjalan dengan sempurna dengan suatu versi django misalkan. Kemudian django merilis versi baru dan aplikasi sebelumnya menjadi tidak bisa dijalankan karena adanya perubahan fungsi. Lalu kita diperlukan membuat aplikasi lain yang menggunakan versi baru. Oleh karena itu, kita perlu membuatnya menggunakan virtual environment agar setiap aplikasi memiliki modul versinya sendiri dalam satu komputer.

3. Untuk poin 1: saya pertama-tama membuat fungsi yang menerima parameter request dan akan mereturn render dari katalog.html. Kemudian melakukan import models ke dalam views, lalu saya membuat fungsi untuk melakukan query ke models dan menyimpannya ke dalam suatu variabel. Terakhir tambahkan ke dalam fungsi render.
   Untuk poin 2: saya melakukan routing dengan pertama-tama mengimport fungsi dari views dan menambahkan suatu urlpatterns dengan path ke fungsi tersebut.
   Untuk poin 3: saya pertama-tama mengganti nama dan NPM atau student ID pada bagian Fill me! sesuai dengan yang ada dalam variabel di views. Lalu saya melakukan iterasi untuk setiap isi dari tabel dikarenakan berbeda dengan nama dan NPM, isi dari tabel merupakan suatu objek dalam suatu kontainer sehingga harus dipanggil nama objek secara spesifik satu per satu.
   Untuk poin 4: pertama-tama saya mengisikan API key dan nama aplikasi untuk heroku pada konfigurasi repositori github, kita tambahkan kedua hal tersebut dan kita lakukan add, commit, dan push. 

Link untuk app heroku: https://tugaspbp2.herokuapp.com/
