# Security information and event management (SIEM) dashboards

## Data Log dan SIEM
Sebagai analis keamanan, salah satu tanggung jawab Anda adalah menganalisis data log untuk mengurangi dan mengelola ancaman (*threats*), risiko (*risks*), dan kerentanan (*vulnerabilities*).

### 1. Apa itu Log?
**Log** adalah catatan peristiwa yang terjadi di dalam sistem dan jaringan organisasi. 
Terdapat tiga sumber log umum yang sering digunakan oleh analis keamanan:
*   **Log Firewall (*Firewall Logs*):** Catatan koneksi yang dicoba atau berhasil dibuat untuk lalu lintas masuk (*inbound traffic*) dari internet. Log ini juga mencatat permintaan keluar (*outbound requests*) menuju internet dari dalam jaringan.
*   **Log Jaringan (*Network Logs*):** Catatan semua komputer dan perangkat yang masuk dan keluar dari jaringan. Log ini juga merekam koneksi antara perangkat dan layanan yang ada di jaringan.
*   **Log Server (*Server Logs*):** Catatan peristiwa yang berkaitan dengan layanan seperti situs web, email, atau berbagi file (*file sharing*). Log ini mencakup tindakan seperti proses *login*, penggunaan kata sandi (*password*), dan permintaan nama pengguna (*username*).

Dengan memantau log-log ini, tim keamanan dapat mengidentifikasi kerentanan dan potensi pelanggaran data (*data breaches*). Pemahaman tentang log ini sangat penting karena alat keamanan seperti SIEM sangat bergantung pada log.


### 2. SIEM (Security Information and Event Management)
**Alat SIEM** adalah aplikasi yang mengumpulkan dan menganalisis data log untuk memantau aktivitas penting di dalam suatu organisasi. 

### Fitur dan Manfaat SIEM:
*   Memberikan visibilitas secara *real-time*.
*   Melakukan pemantauan dan analisis peristiwa (*event monitoring and analysis*).
*   Memberikan peringatan otomatis (*automated alerts*) jika ada aktivitas mencurigakan.
*   Menyimpan semua data log di satu lokasi terpusat (*centralized location*).

Karena alat SIEM secara otomatis mengindeks dan menyaring log, ini sangat meminimalkan jumlah log yang harus ditinjau dan dianalisis secara manual oleh profesional keamanan. Hasilnya, alat ini meningkatkan efisiensi dan menghemat banyak waktu.

### Pentingnya Konfigurasi SIEM
Meskipun sangat canggih, alat SIEM tidak bisa dibiarkan begitu saja setelah diinstal. Alat ini harus dikonfigurasi dan disesuaikan untuk memenuhi kebutuhan keamanan unik dari masing-masing organisasi. Selain itu, seiring dengan munculnya ancaman dan kerentanan baru, organisasi harus terus menyesuaikan dan memperbarui alat SIEM mereka untuk memastikan ancaman tersebut dapat dideteksi dan ditangani dengan cepat.

## Dasbor SIEM (SIEM Dashboards)

Selain digunakan untuk mengumpulkan dan menganalisis data *log*, alat SIEM (*Security Information and Event Management*) juga memiliki fungsi penting lainnya, yaitu untuk membuat **dasbor (*dashboards*)**.

### 1. Fungsi Dasbor SIEM
Sama seperti aplikasi cuaca di ponsel Anda yang menyajikan informasi suhu, kecepatan angin, dan grafik perkiraan cuaca agar mudah dipahami, dasbor SIEM bekerja dengan cara yang serupa. Dasbor SIEM membantu analis keamanan untuk:
*   Mengakses informasi keamanan organisasi secara cepat dan mudah dalam format visual seperti bagan (*charts*), grafik (*graphs*), atau tabel.
*   Membuat keputusan yang cepat dan tepat berdasarkan data yang disajikan.

### 2. Contoh Penggunaan Dasbor SIEM
Ketika seorang analis keamanan menerima peringatan (*alert*) tentang upaya *login* yang mencurigakan, mereka dapat menggunakan dasbor SIEM untuk menyelidikinya.
*   **Kasus:** Analis menemukan adanya 500 upaya *login* untuk akun pengguna (misalnya, akun Ymara) hanya dalam rentang waktu lima menit.
*   **Investigasi:** Melalui dasbor, analis dapat melihat bahwa upaya tersebut berasal dari lokasi geografis yang tidak biasa dan terjadi di luar jam kerja normal pengguna tersebut.
*   **Kesimpulan Visual:** Representasi visual di dasbor (seperti garis waktu/ *timeline* upaya *login*, lokasi, dan waktu aktivitas secara presisi) memungkinkan analis untuk dengan cepat menyimpulkan bahwa aktivitas tersebut memang mencurigakan.

### 3. Metrik dan Kustomisasi Dasbor
Selain memberikan ringkasan komprehensif terkait keamanan, dasbor SIEM juga menyediakan **metrik (*metrics*)** kepada para pemangku kepentingan (*stakeholders*).
*   **Apa itu Metrik?** Metrik adalah atribut teknis utama seperti waktu respons (*response time*), ketersediaan (*availability*), dan tingkat kegagalan (*failure rate*) yang digunakan untuk menilai kinerja sebuah aplikasi perangkat lunak.
*   **Kustomisasi:** Dasbor SIEM dapat disesuaikan (*customized*) agar menampilkan metrik atau data tertentu yang paling relevan bagi berbagai peran di dalam organisasi.
*   **Contoh Kustomisasi:** Seorang analis keamanan dapat membuat dasbor khusus yang menampilkan metrik untuk memantau operasi bisnis sehari-hari, seperti volume lalu lintas jaringan yang masuk dan keluar (*inbound and outbound network traffic*).

## Masa Kini dan Masa Depan Alat SIEM
### 1. Solusi SIEM Saat Ini
*   **Fungsi Utama:** Alat SIEM mengumpulkan dan menganalisis data log untuk memantau aktivitas penting di dalam organisasi.
*   **Pemantauan Real-time:** SIEM menawarkan pemantauan dan pelacakan *real-time* dari log peristiwa keamanan (*security event logs*). Data ini kemudian digunakan untuk melakukan analisis menyeluruh terhadap potensi ancaman, risiko, atau kerentanan.
*   **Dasbor (*Dashboards*):** SIEM memiliki banyak pilihan dasbor yang membantu tim keamanan siber mengelola dan memantau data organisasi.
*   **Keterbatasan Saat Ini:** Saat ini, alat SIEM masih membutuhkan interaksi manusia (analis) untuk melakukan analisis terhadap berbagai peristiwa keamanan tersebut.

### 2. Masa Depan Alat SIEM
Seiring berkembangnya dunia keamanan siber, kebutuhan akan fungsionalitas *cloud* (komputasi awan) semakin meningkat. Alat SIEM terus beradaptasi untuk berfungsi di lingkungan *cloud*:
*   **Cloud-hosted SIEM:** Dioperasikan oleh vendor pihak ketiga yang bertanggung jawab untuk memelihara dan mengelola infrastrukturnya. Alat ini diakses melalui internet dan menjadi solusi ideal bagi organisasi yang tidak ingin repot membangun infrastruktur mereka sendiri.
*   **Cloud-native SIEM:** Mirip dengan *cloud-hosted* (dikelola vendor & diakses via internet), tetapi alat ini dirancang sejak awal untuk memanfaatkan kemampuan komputasi awan secara maksimal, seperti ketersediaan (*availability*), fleksibilitas (*flexibility*), dan skalabilitas (*scalability*).

### Evolusi Menghadapi Teknologi Baru
*   **Internet of Things (IoT):** Perkembangan perangkat yang saling terhubung ke internet (IoT) akan memperbesar area permukaan serangan (*attack surface*). Semakin banyak perangkat yang terhubung, semakin besar jumlah data yang berpotensi dieksploitasi oleh penyerang.
*   **AI dan Machine Learning (ML):** Seiring kemajuan *Artificial Intelligence* (AI) dan *Machine Learning* (ML), kemampuan SIEM akan terus ditingkatkan, terutama untuk mengidentifikasi ancaman, memperbaiki visualisasi dasbor, dan mengoptimalkan fungsi penyimpanan data.

### 3. SOAR (Security Orchestration, Automation, and Response)
Penerapan otomatisasi (*automation*) akan membantu tim keamanan merespons insiden dengan lebih cepat.
*   **Apa itu SOAR?** SOAR adalah kumpulan aplikasi, *tools*, dan alur kerja (*workflows*) yang menggunakan otomatisasi untuk merespons peristiwa keamanan. SOAR dapat melakukan banyak tindakan mitigasi tanpa harus menunggu perintah/respons dari manusia.
*   **Manfaat SOAR:** Penanganan insiden keamanan umum menjadi jauh lebih lancar (*streamlined*) dengan minim intervensi manual. Hal ini membebaskan analis keamanan agar bisa fokus menangani insiden yang lebih kompleks dan langka (yang tidak bisa diotomatisasi oleh SOAR).


