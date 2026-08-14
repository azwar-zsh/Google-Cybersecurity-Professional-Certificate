# CISSP security domains

## 8 Domain Keamanan CISSP
Terdapat delapan domain (kategori) keamanan yang diidentifikasi oleh CISSP. Tim keamanan menggunakannya untuk mengatur tugas sehari-hari, mengidentifikasi celah keamanan, dan menetapkan **postur keamanan** (*security posture*). 
*Postur keamanan* adalah kemampuan organisasi untuk mengelola pertahanan terhadap aset dan data penting serta bereaksi terhadap perubahan.
Berikut adalah fokus dari empat domain pertama:

### 1. Security and Risk Management (Keamanan dan Manajemen Risiko)
Domain ini berfokus pada beberapa area utama:
*   **Menentukan Tujuan dan Sasaran Keamanan:** Bertujuan mengurangi risiko terhadap aset dan data penting seperti PII (*Personally Identifiable Information*).
*   **Mitigasi Risiko (*Risk Mitigation*):** Memiliki prosedur dan aturan yang tepat untuk mengurangi dampak risiko (seperti pelanggaran data) dengan cepat.
*   **Kepatuhan (*Compliance*):** Metode utama untuk mengembangkan kebijakan keamanan internal, memenuhi persyaratan peraturan, dan standar independen.
*   **Kelangsungan Bisnis (*Business Continuity*):** Kemampuan organisasi mempertahankan produktivitas sehari-hari dengan menetapkan rencana pemulihan bencana (*disaster recovery plan*).
*   **Peraturan Hukum (*Legal Regulations*):** Mengikuti aturan dan standar perilaku etis untuk meminimalkan kelalaian, penyalahgunaan, atau penipuan.

### 2. Asset Security (Keamanan Aset)
Domain ini difokuskan pada pengamanan aset digital dan fisik.
*   Terkait dengan penyimpanan, pemeliharaan, retensi, dan penghancuran data.
*   Aset penting seperti PII atau SPII (*Sensitive PII*) harus ditangani dan dilindungi dengan aman (baik di komputer, jaringan, atau saat dikumpulkan secara fisik).
*   Mengetahui data apa yang dimiliki dan siapa yang memiliki akses ke sana sangat penting untuk postur keamanan yang kuat.
*   **Contoh Tugas:** Sebagai analis keamanan, Anda mungkin diminta untuk mengawasi penghancuran *hard drive* secara fisik agar data di dalamnya tidak jatuh ke tangan penyerang (*threat actor*).

### 3. Security Architecture and Engineering (Arsitektur dan Rekayasa Keamanan)
Domain ini berfokus pada optimalisasi keamanan data dengan memastikan alat, sistem, dan proses yang efektif tersedia.
*   **Tanggung Jawab Bersama (*Shared Responsibility*):** Konsep inti di mana *semua* individu dalam organisasi mengambil peran aktif dalam menurunkan risiko dan menjaga keamanan fisik maupun virtual.
*   Dengan kebijakan yang mendorong pengguna untuk mengenali dan melaporkan masalah keamanan, banyak masalah dapat ditangani dengan cepat.

### 4. Communication and Network Security (Komunikasi dan Keamanan Jaringan)
Domain ini berfokus pada pengelolaan dan pengamanan jaringan fisik maupun komunikasi nirkabel (*wireless*).
*   Menjaga data dan komunikasi organisasi tetap aman baik secara lokal (*on-premise*), di *cloud*, atau saat terhubung dari jarak jauh (*remote*).
*   **Contoh Kasus:** Karyawan yang bekerja jarak jauh (*remote*) rentan saat menggunakan koneksi Bluetooth atau Wi-Fi publik yang tidak aman. Tim keamanan dapat membatasi akses ke saluran komunikasi berisiko ini di tingkat organisasi agar karyawan tidak melakukan praktik yang tidak aman.

### 5. Identity and Access Management / IAM (Manajemen Identitas dan Akses)
Domain ini berfokus pada akses dan otorisasi untuk menjaga data tetap aman dengan memastikan pengguna mengikuti kebijakan yang ditetapkan untuk mengontrol dan mengelola aset.
*   **Tujuan Utama:** Menjaga sistem dan data organisasi seaman mungkin dengan memastikan akses pengguna terbatas pada apa yang dibutuhkan karyawan untuk bekerja, yang bertujuan mengurangi risiko keseluruhan.
*   **Contoh Kasus:** Jika semua orang di perusahaan menggunakan *login* administrator yang sama, tidak ada cara untuk melacak siapa yang memiliki akses ke data apa, dan tidak mungkin memisahkan aktivitas pengguna yang valid dari pelaku ancaman saat terjadi pelanggaran.
*   **4 Komponen Utama IAM:**
    *   **Identification (Identifikasi):** Pengguna memverifikasi siapa mereka dengan memberikan nama pengguna, kartu akses, atau data biometrik seperti sidik jari.
    *   **Authentication (Autentikasi):** Proses verifikasi untuk membuktikan identitas seseorang, seperti memasukkan kata sandi atau PIN.
    *   **Authorization (Otorisasi):** Terjadi setelah identitas dikonfirmasi dan terkait dengan tingkat akses yang bergantung pada peran dalam organisasi.
    *   **Accountability (Akuntabilitas):** Pemantauan dan pencatatan tindakan pengguna, seperti upaya *login*, untuk membuktikan sistem dan data digunakan dengan benar.

### 6. Security Assessment and Testing (Penilaian dan Pengujian Keamanan)
Domain ini berfokus pada melakukan pengujian kontrol keamanan, pengumpulan dan analisis data, dan melakukan audit keamanan untuk memantau risiko, ancaman, dan kerentanan.
*   **Evaluasi Kontrol:** Melibatkan pemeriksaan tujuan dan sasaran organisasi, serta mengevaluasi apakah kontrol yang digunakan benar-benar mencapai tujuan tersebut untuk mengidentifikasi cara mitigasi yang lebih baik.
*   **Tindakan Analis:** Analis mungkin menggunakan evaluasi ini dan laporan penilaian keamanan untuk meningkatkan kontrol yang ada atau menerapkan kontrol baru.
*   **Contoh Penerapan:** Penerapan kontrol baru mungkin memerlukan penggunaan otentikasi multi-faktor (MFA) untuk melindungi organisasi dengan lebih baik.

### 7. Security Operations (Operasi Keamanan)
Domain ini difokuskan pada melakukan investigasi dan menerapkan langkah-langkah pencegahan.
*   **Urgensi Tinggi:** Investigasi dimulai setelah insiden keamanan diidentifikasi dan membutuhkan rasa urgensi yang tinggi untuk meminimalkan potensi risiko. Jika ada serangan aktif, mengurangi serangan dan mencegah eskalasi sangat penting untuk melindungi informasi pribadi.
*   **Forensik Digital (*Digital Forensics*):** Setelah ancaman dinetralkan, pengumpulan bukti digital dan fisik untuk penyelidikan forensik digital akan dilakukan guna mengidentifikasi kapan, bagaimana, dan mengapa pelanggaran terjadi.
*   **Tujuan Investigasi:** Membantu tim keamanan menentukan area untuk perbaikan dan tindakan pencegahan di masa depan.

### 8. Software Development Security (Keamanan Pengembangan Perangkat Lunak)
Domain ini berfokus pada penggunaan praktik pengkodean yang aman (*secure coding practices*) sebagai pedoman untuk membuat aplikasi dan layanan yang aman.
*   **SDLC (Software Development Life Cycle):** SDLC adalah proses efisien yang digunakan untuk membangun produk dan fitur perangkat lunak dengan cepat, di mana keamanan harus diintegrasikan sepenuhnya ke dalam produk.
*   **Contoh Integrasi Keamanan:** Melakukan tinjauan desain yang aman selama fase desain, tinjauan kode aman selama fase pengembangan dan pengujian, serta pengujian penetrasi (*penetration testing*) selama fase penerapan dan implementasi.
*   **Manfaat:** Memastikan bahwa keamanan tertanam di setiap langkah untuk menjaga perangkat lunak tetap aman, melindungi data sensitif, dan mengurangi risiko yang tidak perlu.

