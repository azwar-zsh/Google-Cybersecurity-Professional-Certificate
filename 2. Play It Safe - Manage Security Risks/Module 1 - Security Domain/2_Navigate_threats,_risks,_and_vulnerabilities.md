# Navigate threats, risks, and vulnerabilities

## Ancaman, Risiko, dan Kerentanan
Sebagai analis keamanan tingkat pemula, salah satu peran Anda adalah menangani aset digital dan fisik organisasi. **Aset (*Assets*)** adalah segala sesuatu yang dianggap memiliki nilai bagi organisasi (seperti ruang kantor fisik, komputer, *Personally Identifiable Information* / PII pelanggan, dan *Intellectual Property* / kekayaan intelektual seperti paten atau hak cipta). 
Sayangnya, organisasi beroperasi di lingkungan yang penuh dengan ancaman, risiko, dan kerentanan terhadap aset-aset tersebut.

### 1. Ancaman (*Threats*)
Ancaman adalah keadaan atau peristiwa apa pun yang dapat berdampak negatif pada aset. 
*   **Contoh Ancaman Utama:** *Social Engineering* (rekayasa sosial), yaitu teknik manipulasi yang mengeksploitasi kesalahan manusia untuk mendapatkan informasi pribadi, hak akses, atau barang berharga.
*   **Phishing:** Ini adalah salah satu metode *social engineering* yang paling umum, menggunakan tautan berbahaya (*malicious link*) di dalam email yang seolah-olah berasal dari sumber yang sah. Tujuannya adalah untuk mencuri data sensitif seperti *username*, kata sandi, atau informasi perbankan.

### 2. Risiko (*Risks*)
Risiko berbeda dengan ancaman. Risiko adalah segala sesuatu yang dapat memengaruhi kerahasiaan (*confidentiality*), integritas (*integrity*), atau ketersediaan (*availability*) suatu aset. Singkatnya, risiko adalah **kemungkinan** terjadinya sebuah ancaman.
*   **Contoh Risiko:** Kurangnya protokol pencadangan (*backup protocols*) untuk memastikan informasi dapat dipulihkan jika terjadi insiden keamanan atau kecelakaan.

Organisasi biasanya menilai tingkat risiko aset berdasarkan kemungkinan ancaman dan nilai aset tersebut:
1.  **Risiko Rendah (*Low Risk*):** Aset berupa informasi publik yang, jika dikompromikan, tidak akan merusak reputasi atau keuangan organisasi (contoh: konten situs web publik atau data penelitian yang sudah dipublikasikan).
2.  **Risiko Menengah (*Medium Risk*):** Informasi non-publik yang dapat menyebabkan kerusakan finansial, reputasi, atau operasional jika bocor (contoh: rilis awal laporan pendapatan kuartalan yang dapat memengaruhi harga saham).
3.  **Risiko Tinggi (*High Risk*):** Informasi yang dilindungi oleh undang-undang atau peraturan, yang dampaknya akan sangat parah bagi organisasi jika dikompromikan (contoh: kebocoran SPII, PII, atau kekayaan intelektual).

### 3. Kerentanan (*Vulnerabilities*)
Kerentanan adalah kelemahan yang dapat dieksploitasi atau dimanfaatkan oleh ancaman. Perlu diingat bahwa **harus ada ancaman dan kerentanan** agar sebuah risiko bisa terjadi.
*   **Contoh Kerentanan Teknis:** *Firewall*, perangkat lunak (*software*), atau aplikasi yang sudah usang (*outdated*); kata sandi yang lemah; atau data rahasia yang tidak dilindungi.
*   **Manusia sebagai Kerentanan:** Tindakan orang-orang (klien, vendor eksternal, atau karyawan) dapat sangat memengaruhi keamanan jaringan internal organisasi.

### 4. Peran Analis dan Upaya Mitigasi
Menjaga keamanan harus menjadi upaya bersama (*unified effort*). Analis tingkat pemula sangat berperan dalam mengidentifikasi dan mengurangi kerentanan melalui langkah-langkah berikut:
*   **Edukasi Pengguna:** Mendidik dan memberdayakan orang agar lebih sadar akan keamanan (*security awareness*), misalnya mengajari cara mengidentifikasi email *phishing*.
*   **Keamanan Fisik:** Menggunakan kartu akses (*access cards*) untuk membatasi ruang fisik hanya bagi karyawan dan mencegah pengunjung luar yang tidak berkepentingan.
*   **Pemantauan Aktif:** Memantau dan mendokumentasikan akses karyawan ke aset penting secara aktif.
*   **Budaya Keamanan:** Mendorong karyawan untuk selalu melaporkan aktivitas yang mencurigakan.

## Ransomware, Lapisan Web, dan Dampak Keamanan
Dalam materi ini, kita akan membahas jenis *malware* yang disebut *ransomware*. Kemudian, kita juga akan membahas tiga lapisan web dan tiga dampak utama dari ancaman, risiko, dan kerentanan pada operasi organisasi.

### 1. Ransomware
*Ransomware* adalah serangan berbahaya di mana penyerang (*threat actor*) mengenkripsi data organisasi, kemudian meminta pembayaran (tebusan) untuk memulihkan akses.
*   **Dampak Awal:** Setelah disebarkan, *ransomware* dapat membekukan sistem jaringan, membuat perangkat tidak dapat digunakan, dan mengunci data rahasia sehingga tidak dapat diakses.
*   **Kunci Dekripsi (*Decryption Key*):** Penyerang menuntut tebusan sebelum memberikan kunci dekripsi (berfungsi seperti kata sandi) agar organisasi dapat kembali menjalankan operasi bisnis normal mereka.
*   **Web Gelap (*Dark Web*):** Negosiasi tebusan atau pembocoran data yang dicuri oleh penyerang umumnya dilakukan melalui jaringan web gelap.

### 2. Tiga Lapisan Web
Meskipun banyak orang menggunakan mesin pencari standar untuk menjelajah internet, itu hanyalah sebagian kecil dari keseluruhan web. Web sebenarnya terdiri dari tiga lapisan:
*   **Surface Web (Web Permukaan):** Lapisan yang paling banyak digunakan. Berisi konten yang bebas diakses menggunakan *browser* web standar.
*   **Deep Web (Web Dalam):** Lapisan yang membutuhkan otorisasi (izin) untuk mengaksesnya. Contohnya adalah intranet organisasi yang hanya dapat diakses oleh karyawan yang memiliki akses yang sah.
*   **Dark Web (Web Gelap):** Lapisan yang hanya dapat diakses dengan menggunakan perangkat lunak khusus. Lapisan ini sering memiliki konotasi negatif karena sangat disukai oleh penjahat siber berkat kerahasiaan (*anonymity*) yang ditawarkannya.

### 3. Tiga Dampak Utama dari Ancaman, Risiko, dan Kerentanan
Ketika aset organisasi dikompromikan (misalnya oleh serangan *malware*), terdapat tiga dampak utama yang dapat dialami:

**A. Dampak Finansial (*Financial Impact*)**
Konsekuensi keuangan dari sebuah serangan bisa sangat signifikan. Ini mencakup terhentinya produksi dan layanan, biaya untuk memperbaiki masalah teknis, serta denda tambahan jika insiden tersebut terjadi akibat ketidakpatuhan terhadap hukum dan peraturan keamanan.

**B. Pencurian Identitas (*Identity Theft*)**
Menyimpan data sensitif (seperti informasi pribadi pelanggan, karyawan, dan vendor luar) menghadirkan risiko besar bagi organisasi. Data sensitif seperti Informasi Identitas Pribadi (PII) dapat dicuri lalu dijual atau dibocorkan di *dark web*. Di sana, para penyerang dapat bertransaksi tanpa takut akan konsekuensi hukum karena tingginya tingkat kerahasiaan.

**C. Kerusakan Reputasi (*Reputational Damage*)**
Basis pelanggan yang solid sangat penting untuk mendukung misi dan tujuan keuangan organisasi. Kerentanan yang dieksploitasi dapat menyebabkan hilangnya kepercayaan, sehingga pelanggan beralih ke pesaing. Selain itu, liputan media yang buruk (*bad press*) dapat menyebabkan kerusakan permanen pada reputasi organisasi. Kebocoran data pelanggan juga hampir selalu diikuti oleh hukuman hukum dan denda.

## NIST Risk Management Framework (RMF)
Institut Standar dan Teknologi Nasional (NIST) menyediakan banyak *framework* (kerangka kerja) yang digunakan oleh profesional keamanan untuk mengelola risiko, ancaman, dan kerentanan. Salah satu yang sangat penting adalah **NIST Risk Management Framework (RMF)**. 
Sebagai analis tingkat pemula (*entry-level*), Anda mungkin tidak terlibat langsung dalam semua langkah ini. Namun, memiliki pemahaman dasar yang kuat tentang cara mengurangi dan mengelola risiko menggunakan RMF dapat membedakan Anda dari kandidat lain saat mencari pekerjaan di bidang keamanan.

### 7 Langkah dalam NIST RMF

**1. Prepare (Mempersiapkan)**
*   Langkah ini mengacu pada kegiatan yang diperlukan untuk mengelola risiko keamanan dan privasi sebelum terjadinya pelanggaran (*breach*). 
*   Analis tingkat pemula biasanya menggunakan langkah ini untuk memantau risiko dan mengidentifikasi *security controls* (kontrol keamanan) yang dapat digunakan untuk mengurangi risiko tersebut.

**2. Categorize (Mengkategorikan)**
*   Langkah ini digunakan untuk mengembangkan proses dan tugas manajemen risiko. 
*   Profesional keamanan mengembangkan tugas tersebut dengan memikirkan bagaimana kerahasiaan (*confidentiality*), integritas (*integrity*), dan ketersediaan (*availability*) sistem serta informasi dapat dipengaruhi oleh suatu risiko. 
*   Analis harus memahami cara mengikuti proses yang ditetapkan organisasi untuk mengurangi risiko terhadap aset penting, seperti informasi pelanggan pribadi.

**3. Select (Memilih)**
*   Berfokus pada memilih, menyesuaikan, dan mendokumentasikan kontrol keamanan yang melindungi organisasi. 
*   Contoh penerapannya adalah menjaga pedoman tetap terbaru atau membantu mengelola dokumentasi lain yang memungkinkan tim mengatasi masalah dengan lebih efisien.

**4. Implement (Menerapkan)**
*   Menerapkan rencana keamanan dan privasi di dalam organisasi. Memiliki rencana yang baik sangat penting untuk meminimalkan dampak dari risiko keamanan yang sedang berlangsung. 
*   Contoh: Jika Anda melihat pola di mana karyawan terus-menerus membutuhkan *reset* kata sandi, menerapkan perubahan pada persyaratan kata sandi dapat membantu menyelesaikan masalah ini.

**5. Assess (Menilai)**
*   Menentukan apakah kontrol keamanan yang telah ditetapkan sudah diterapkan dengan benar. 
*   Penting untuk meluangkan waktu menganalisis apakah protokol, prosedur, dan kontrol yang ada benar-benar memenuhi kebutuhan organisasi agar dapat beroperasi seefisien mungkin. 
*   Pada langkah ini, analis mengidentifikasi kelemahan potensial dan menentukan apakah alat, prosedur, atau protokol organisasi harus diubah untuk mengelola risiko dengan lebih baik.

**6. Authorize (Mengotorisasi)**
*   Berarti bertanggung jawab atas risiko keamanan dan privasi yang mungkin ada di dalam organisasi. 
*   Bagi seorang analis, langkah ini dapat melibatkan pembuatan laporan, pengembangan rencana tindakan, dan penetapan pencapaian (*milestones*) proyek yang selaras dengan tujuan keamanan organisasi Anda.

**7. Monitor (Memantau)**
*   Menyadari dan mengamati bagaimana sistem beroperasi sehari-hari. Menilai dan memelihara operasi teknis adalah tugas harian analis.
*   Bagian dari mempertahankan tingkat risiko yang rendah adalah mengetahui bagaimana sistem saat ini mendukung tujuan keamanan organisasi. Jika sistem yang ada tidak memenuhi tujuan tersebut, perubahan mungkin diperlukan. 
*   Analis perlu memastikan bahwa prosedur tersebut bekerja sebagaimana mestinya untuk meminimalkan risiko bagi organisasi dan orang-orang yang dilayaninya.