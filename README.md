# ProgramRestaurant

Kelompok 13
Anggota : 1.  Nama : Hilman Maulana <br>
              NIM  : 1237050020
              Kelas : 1B Informatika
          2.  Nama  : Mochamad Fahmi Rizieq
              NIM   : 1237050074
              Kelas : 1B Informatika
          3.  Nama  : Nabilah Nuril Zahra M. Karim
              NIM   : 1237050120
              Kelas : 1B Informatika
          
Program yang tercakup dalam implementasi aplikasi toko menggunakan bahasa pemrograman Java menunjukkan fokus utamanya pada kelas `TokoController`. Kelas ini memiliki peran krusial dalam mengelola logika utama aplikasi dan berinteraksi dengan pengguna. Ketika aplikasi pertama kali dijalankan, langkah inisiasi data dilakukan melalui metode `setUp()`. Metode ini bertujuan untuk menginisialisasi data pembeli dan penjual, yang selanjutnya disimpan dalam struktur data yang efisien, yaitu `HashMap`. Pemilihan struktur data ini memungkinkan pengelolaan data yang cepat dan efisien, dengan kemampuan pencarian data berbasis kunci.

Salah satu fitur penting dalam aplikasi ini adalah kemampuan untuk menambahkan barang baru ke dalam sistem melalui metode `tambahBarang()`. Dalam proses ini, pengguna diminta untuk memberikan informasi terkait barang, seperti ID barang, nama barang, harga, dan ketersediaan. Data barang baru tersebut kemudian disimpan dalam `HashMap` yang secara unik memetakan ID barang ke objek barang yang bersangkutan. Selanjutnya, metode `lihatDaftarBarang()` memberikan kemampuan bagi pengguna untuk melihat daftar barang yang tersedia dalam toko. Hanya barang yang tersedia yang ditampilkan, memberikan pandangan yang jelas mengenai stok barang yang dapat dibeli.

Fitur belanja diimplementasikan melalui metode `belanja()`, di mana pengguna dapat dengan interaktif memilih barang, memasukkan jumlah yang akan dibeli, dan memutuskan untuk melanjutkan atau mengakhiri belanja. Detil penjualan, termasuk barang yang dipilih, harga, jumlah, dan subtotal, disimpan dalam struktur data yang sesuai. Metode `tampilkanDaftarBelanjaan()` berfungsi untuk menyajikan informasi secara terperinci mengenai barang-barang yang telah dibeli, memberikan ringkasan transaksi kepada pengguna. Selain itu, metode `hitungTotalBelanja()` mengelola perhitungan total pembelian berdasarkan detil penjualan yang tersimpan.

Lanjutnya, metode `tampilkanLaporanPenjualan()` memungkinkan pengguna untuk melihat laporan penjualan, yang mencakup detail transaksi seperti kode penjualan, tanggal transaksi, penjual, pembeli, dan rincian barang yang dibeli beserta total pembelian. Implementasi manajemen kesalahan menggunakan `try-catch` memberikan keandalan kepada program untuk menangani kemungkinan kesalahan input, sehingga memastikan pengalaman pengguna yang lebih baik dan menjaga konsistensi data.

Dengan demikian, program ini menyediakan fungsionalitas dasar untuk manajemen toko yang efisien, memfasilitasi penambahan barang, proses pembelian, serta pembuatan laporan penjualan. Struktur dan logika yang terimplementasi dengan baik menjadikan program ini sebagai dasar yang kuat untuk dikembangkan lebih lanjut sesuai kebutuhan bisnis.
