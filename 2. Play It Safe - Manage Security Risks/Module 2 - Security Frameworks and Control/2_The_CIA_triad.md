# The CIA triad: Confidentiality, integrity, and availability

Saat bekerja sebagai analis keamanan tingkat pemula (*entry-level security analyst*), tanggung jawab utama Anda adalah membantu melindungi aset dan data sensitif organisasi dari pelaku ancaman (*threat actors*). **CIA Triad** adalah model keamanan inti yang membantu menginformasikan bagaimana organisasi mempertimbangkan risiko ketika menyiapkan sistem dan kebijakan keamanan.

## 1. Tiga Komponen Inti CIA Triad

### A. Confidentiality (Kerahasiaan)
*   **Definisi:** Memastikan bahwa hanya pengguna yang berwenang (*authorized users*) yang dapat mengakses aset atau data tertentu.
*   **Prinsip Kunci:** Data sensitif harus diberikan berdasarkan prinsip *need-to-know* (kebutuhan untuk mengetahui), sehingga hanya pihak yang berhak menangani data tersebut yang memiliki hak akses.

### B. Integrity (Integritas)
*   **Definisi:** Memastikan bahwa data tersebut benar, autentik, dan dapat diandalkan (*reliable*), serta tidak dimodifikasi secara tidak sah.
*   **Peran Analis:** Menentukan integritas data dan menganalisis cara penggunaannya akan membantu analis memutuskan apakah suatu data dapat dipercaya atau tidak.

### C. Availability (Ketersediaan)
*   **Definisi:** Memastikan bahwa data dan layanan dapat diakses secara tepat waktu oleh pihak yang memiliki izin ketika dibutuhkan.
*   **Peran Analis:** Data yang tidak dapat diakses tidak akan berguna dan dapat menghambat operasional pekerjaan. Analis bertanggung jawab memastikan bahwa sistem, jaringan, dan aplikasi berfungsi normal untuk menyediakan akses yang andal.

## 2. Contoh Penerapan CIA Triad (Studi Kasus Perbankan)

Sebuah institusi finansial/bank mengelola data pribadi dalam jumlah besar, sehingga penerapan ketiga prinsip ini sangat krusial:

*   **Penerapan Confidentiality:** Bank wajib menjaga kerahasiaan informasi identitas pribadi dan data keuangan nasabah agar tidak bocor ke pihak luar.
*   **Penerapan Integrity:** Jika pola transaksi belanja atau lokasi pembelian nasabah berubah drastis secara tiba-tiba, bank dapat menonaktifkan sementara akses akun sampai berhasil memverifikasi bahwa transaksi dilakukan oleh pemilik asli, bukan penyerang.
*   **Penerapan Availability:** Bank berupaya memastikan nasabah dapat mengakses informasi akun melalui portal web dengan mudah dan andal, sembari menerapkan proses validasi keamanan untuk meminimalkan kerusakan jika akun dicurigai terkompromi (*compromised*).
