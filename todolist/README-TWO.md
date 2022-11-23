1. Asynchronous programming sesuai dengan namanya asynchronous, suatu teknik programming yang mana operasinya dapat berjalan tanpa harus menunggu suatu operasi selesai baru mulai, sedangkan synchronous programming merupakan suatu teknik programming yang mana operasinya harus menunggu suatu operasi terlebih dahulu baru dapat memulai operasi lainnya.
2. Event-Driven Programming merupakan suatu paradigma yang mana alur programnya akan ditentukan oleh suatu event/peristiwa yang merupakan suatu keluaran atau tindakan pengguna, atau bisa berupa pesan dari program lainnya. Contoh dari pemakaian paradigma ini adalah pada saat penekanan suatu tombol dan terjadi perubahan pada salah satu objek.
3. Dalam AJAX, kita dapat memanggil program dalam tag script. Asynchronous programming akan terjadi pada pengiriman request. Request akan diproses di background sehingga user dapat melakukan operasi lainnya. Setelah selesai diproses, baru lah dapat dihubungkan dengan fungsi lainnya. Selama proses ini masih dapat melakukan operasi lain juga.
4. Implementasi setiap poin:
Poin 1: Saya membuat views untuk melakukan respons data berupa json yang pernah dilakukan di lab-lab sebelumnya lalu menghubungkan views tersebut dengan path json. Kemudian saya menuliskan script untuk melakukan AJAX GET dalam html yang saya telah saya buat.
Poin 2: Saya membuat sebuah modal terlebih dahulu dalam html beserta tombolnya, lalu saya menambahkan views untuk menerima data dari form dalam modal dan menghubungkan form dengan url. Dalam html saya menerapkan AJAX POST untuk mengirimkan data dari form dalam modal ke database lalu menutup modal dan langsung melakukan refresh pada page.