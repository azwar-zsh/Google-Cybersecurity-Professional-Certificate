# Explore security information and event management (SIEM) tools

### 1. Jenis-jenis Alat SIEM (Berdasarkan Hosting/Infrastruktur)
*   **Self-hosted SIEM:** 
    Mengharuskan organisasi untuk menginstal, mengoperasikan, dan memelihara alat tersebut menggunakan infrastruktur fisik mereka sendiri (seperti kapasitas *server*). Aplikasi ini dikelola langsung oleh departemen TI internal organisasi. Jenis ini sangat ideal jika organisasi diwajibkan untuk mempertahankan kontrol fisik secara penuh atas data rahasia.
*   **Cloud-hosted SIEM:** 
    Dikelola dan dipelihara sepenuhnya oleh penyedia (*vendor*) SIEM, sehingga dapat diakses dengan mudah melalui internet. Solusi ini ideal untuk organisasi yang tidak ingin berinvestasi dalam membangun dan memelihara infrastruktur fisik mereka sendiri.
*   **Hybrid SIEM:** 
    Kombinasi antara alat SIEM *self-hosted* dan *cloud-hosted*. Organisasi memilih solusi *hybrid* ini untuk memanfaatkan fleksibilitas *cloud* sekaligus tetap mempertahankan kontrol fisik atas data-data yang sangat rahasia.

### 2. Contoh Alat SIEM Terkemuka di Industri
*   **Splunk Enterprise:** 
    Alat SIEM berjenis *self-hosted* yang digunakan untuk menyimpan, menganalisis, dan mencari data log organisasi. Tujuannya adalah untuk memberikan informasi keamanan dan peringatan (*alerts*) secara *real-time*.
*   **Splunk Cloud:** 
    Alat SIEM berjenis *cloud-hosted* yang digunakan untuk mengumpulkan, mencari, dan memantau data log. Alat ini sangat berguna bagi organisasi yang menjalankan lingkungan *hybrid* atau sepenuhnya *cloud* (*cloud-only*), di mana sebagian atau seluruh layanannya berada di *cloud*.
*   **Google Chronicle:** 
    Alat SIEM berjenis *cloud-native* yang dirancang untuk menyimpan, menganalisis, dan mencari data (termasuk pemantauan log dan pengumpulan data). Sama seperti *cloud-hosted*, alat ini dikelola penuh oleh vendor. Namun, bedanya adalah alat *cloud-native* dirancang secara spesifik dari awal untuk memaksimalkan seluruh kemampuan *cloud computing*, seperti ketersediaan (*availability*), fleksibilitas (*flexibility*), dan skalabilitas (*scalability*).

## Alat Open-Source vs Proprietary

Dalam dunia keamanan siber, para profesional menggunakan berbagai alat (*security tools*) untuk memantau dan mengidentifikasi potensi ancaman, risiko, dan kerentanan. Secara umum, alat-alat ini dibagi menjadi dua kategori utama: **Open-Source** dan **Proprietary**.


### 1. Alat Open-Source (*Open-Source Tools*)
Alat *open-source* adalah perangkat lunak yang kode sumbernya (*source code*) terbuka untuk publik. 
*   **Karakteristik:** Biasanya gratis untuk digunakan dan cukup ramah pengguna (*user-friendly*).
*   **Kolaboratif & Aman:** Karena dibangun secara kolaboratif oleh publik, alat ini sering kali menjadi lebih aman. Siapa pun dapat melihat, memodifikasi, dan meningkatkan materi proyek tersebut selama mereka mematuhi lisensinya.
*   **Kustomisasi:** Memungkinkan tingkat kustomisasi yang tinggi, sehingga pengguna dapat membangun berbagai layanan baru dari paket *software* dasar yang sama.
*   **Aksesibilitas:** *Source code* dan materi pelatihannya tersedia secara bebas di internet.

### 2. Alat Proprietary (*Proprietary Tools*)
Berbeda dengan *open-source*, alat *proprietary* dikembangkan dan dimiliki secara eksklusif oleh individu atau perusahaan tertentu.
*   **Berbayar:** Pengguna biasanya harus membayar biaya lisensi/penggunaan dan biaya pelatihan.
*   **Akses Terbatas:** Hanya pemilik atau pembuatnya yang dapat mengakses dan memodifikasi *source code*.
*   **Ketergantungan pada Vendor:** Pengguna harus menunggu pembaruan (*updates*) resmi dari perusahaan perangkat lunak tersebut, dan terkadang pembaruan ini memerlukan biaya tambahan.
*   **Modifikasi Terbatas:** Pengguna hanya diizinkan untuk memodifikasi sejumlah fitur yang sangat terbatas sesuai kebutuhan organisasi mereka.
*   **Contoh:** Splunk® dan Google SecOps (Chronicle) SIEM.

### 3. Miskonsepsi Umum
Banyak yang salah mengira bahwa alat *open-source* kurang efektif atau tidak seaman alat *proprietary*. Faktanya:
*   Banyak alat *open-source* yang telah digunakan selama bertahun-tahun dan kini menjadi standar industri (*industry standards*).
*   Meskipun penyerang (*threat actors*) sering mencoba mencari celah di alat *open-source*, keterbukaan kode ini justru membuatnya **lebih sulit** untuk disalahgunakan. 
*   Karena *source code* terekspos secara luas, para profesional dan pengguna yang berniat baik dapat dengan cepat menemukan masalah atau celah keamanan dan langsung memperbaikinya (*patching*) saat itu juga.

### 4. Contoh Alat Open-Source Populer di Keamanan Siber
### A. Linux
*   Linux adalah sistem operasi (*operating system*) *open-source* yang sangat luas digunakan. 
*   Sistem operasi ini bertugas sebagai perantara antara perangkat keras (*hardware*) komputer dan aplikasi perangkat lunak (*software*).
*   Linux memungkinkan Anda untuk menyesuaikan sistem sesuai kebutuhan melalui antarmuka baris perintah (*command-line interface* atau CLI). Terdapat banyak versi (distribusi) Linux yang dirancang untuk tugas-tugas spesifik.

### B. Suricata
*   Suricata adalah perangkat lunak analisis jaringan dan deteksi ancaman (*network analysis and threat detection software*) yang bersifat *open-source*.
*   Fungsinya adalah untuk menginspeksi lalu lintas jaringan (*network traffic*), mengidentifikasi perilaku mencurigakan di berbagai pengguna/komputer/alamat IP, dan menghasilkan data log jaringan.
*   Dikembangkan oleh Open Information Security Foundation (OISF) untuk memastikan alat ini tetap gratis dan tersedia untuk publik. 
*   Suricata banyak digunakan di sektor publik maupun swasta, serta mudah diintegrasikan dengan berbagai alat SIEM.

## Menganalisis Dasbor SIEM (Splunk dan Chronicle)
### 1. Splunk
Splunk menawarkan dua opsi alat SIEM: **Splunk® Enterprise** dan **Splunk® Cloud**. Keduanya membantu tim keamanan mengelola infrastruktur internal dengan mengumpulkan, mencari, memantau, dan menganalisis data log dari berbagai sumber. Tujuannya adalah untuk mendapatkan visibilitas penuh (*full visibility*) terhadap operasi sehari-hari organisasi. Berikut adalah beberapa dasbor Splunk beserta fungsinya:

**Security Posture Dashboard**
Dasbor ini dirancang untuk pusat operasi keamanan (*Security Operations Centers* / SOCs). Dasbor ini menampilkan peristiwa keamanan penting dan tren dalam 24 jam terakhir. Analis dapat menggunakannya untuk memantau dan menyelidiki potensi ancaman secara *real-time*, seperti aktivitas jaringan mencurigakan dari alamat IP tertentu.

**Executive Summary Dashboard**
Dasbor ini menganalisis dan memantau kesehatan organisasi secara keseluruhan dari waktu ke waktu. Analis keamanan sering menggunakannya untuk memberikan wawasan tingkat tinggi (*high-level insights*) kepada pemangku kepentingan (*stakeholders*), seperti ringkasan tren insiden keamanan selama periode waktu tertentu.

**Incident Review Dashboard**
Dasbor ini memungkinkan analis untuk mengidentifikasi pola mencurigakan dari sebuah insiden. Dasbor ini sangat membantu karena menyediakan garis waktu visual (*visual timeline*) dari kejadian-kejadian sebelum insiden, serta menyoroti item-item berisiko tinggi yang membutuhkan peninjauan segera.

**Risk Analysis Dashboard**
Dasbor ini membantu analis mengidentifikasi tingkat risiko untuk setiap objek risiko, seperti pengguna (*user*), komputer, atau alamat IP tertentu. Analis menggunakannya untuk melihat perubahan perilaku (contoh: *login* di luar jam kerja normal atau lalu lintas jaringan yang sangat tinggi) dan memprioritaskan upaya mitigasi risiko pada aset kritis.

### 2. Chronicle
Chronicle adalah alat SIEM *cloud-native* dari Google yang menyimpan, menganalisis, dan mencari data log. Alat ini memungkinkan Anda untuk mengumpulkan dan menganalisis data log berdasarkan aset spesifik (*specific asset*), nama domain (*domain name*), pengguna (*user*), dan alamat IP (*IP address*). Berikut adalah beberapa dasbor Chronicle beserta fungsinya:

**Enterprise Insights Dashboard**
Dasbor ini menyoroti peringatan (*alerts*) terbaru dan mengidentifikasi nama domain mencurigakan yang dikenal sebagai *Indicators of Compromise* (IOC). Setiap hasil dilengkapi dengan skor keyakinan (*confidence score*) dan tingkat keparahan (*severity level*). Analis menggunakannya untuk memantau akses ke aset penting dari perangkat atau lokasi yang tidak biasa.

**Data Ingestion and Health Dashboard**
Dasbor ini menampilkan jumlah log peristiwa, sumber log, dan tingkat keberhasilan data yang diproses ke dalam Chronicle. Dasbor ini digunakan untuk memastikan bahwa sumber log telah dikonfigurasi dengan benar dan data diterima tanpa kesalahan (*errors*).

**IOC Matches Dashboard**
Dasbor ini menunjukkan ancaman dan kerentanan tertinggi bagi organisasi. Profesional keamanan menggunakannya untuk mengamati tren nama domain, alamat IP, dan IOC perangkat dari waktu ke waktu, sehingga fokus tim dapat diarahkan pada ancaman dengan prioritas tertinggi (seperti melacak aktivitas lanjutan dari pengguna dengan lokasi geografis yang mencurigakan).

**Main Dashboard**
Dasbor utama ini menampilkan ringkasan tingkat tinggi terkait konsumsi data, peringatan, dan aktivitas peristiwa. Analis dapat mengakses garis waktu (*timeline*) peristiwa keamanan (misal: lonjakan percobaan *login* yang gagal) untuk mengidentifikasi tren ancaman di berbagai lokasi, perangkat, dan log.

**Rule Detections Dashboard**
Dasbor ini menyediakan statistik terkait insiden dengan tingkat kemunculan (*occurrences*) dan keparahan tertinggi. Analis menggunakannya untuk melihat daftar peringatan yang dipicu oleh aturan deteksi tertentu (misalnya aturan peringatan saat pengguna membuka lampiran email berbahaya) guna mengelola insiden berulang dan menetapkan taktik mitigasi.

**User Sign In Overview Dashboard**
Dasbor ini memberikan informasi tentang perilaku akses pengguna di seluruh organisasi. Analis menggunakannya untuk melihat daftar semua peristiwa *sign-in* dan mengidentifikasi aktivitas tidak wajar, seperti pengguna yang *login* dari beberapa lokasi berbeda pada waktu yang bersamaan.