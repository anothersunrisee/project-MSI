# TUGAS STUDI KASUS - PERTEMUAN 1
## UPS Global Operations dengan DIAD IV: Analisis Kritis dari Perspektif Manajemen Sistem Informasi

**Nama:** Fajar Ahnaf Mahardika - 24050530030
**Kelas:** F1 | **Matkul:** Essentials of Management Information Systems (Teori)
**Referensi Kasus:** Laudon & Laudon, *Essentials of MIS*, Chapter 1, Case 1

---

## BAGIAN A: Analisis Berbasis Bukti

> Setiap baris pada tabel di bawah menggunakan kutipan angka atau frasa yang diambil persis dari teks kasus, bukan parafrase.

| Konsep Bab 1 | Bukti Spesifik dari Kasus | Analisis |
|:---|:---|:---|
| **Aplikasi vs Sistem Informasi vs Sistem Kerja (Empat Lapis, 1.5)** | *"ODS (On-Demand Services)—that enables communication with the driver"*; *"DIAD IV...combining data collection and transmission technologies, digital signature capture"* | Secara konseptual, DIAD IV adalah **aplikasi**: perangkat teknis dengan GPRS, GPS, 128MB RAM, dan Windows CE .NET. Ketika DIAD terhubung dengan ODS, dispatcher, dan 17 data center, barulah ia menjadi bagian dari **sistem informasi**. Dan keseluruhan operasi pengiriman 14 juta paket per hari ke 200 negara adalah **sistem kerja** - di mana manusia, proses, dan teknologi bekerja bersama. Masalahnya, kasus hampir seluruhnya hanya menggambarkan lapis pertama (aplikasi) dan jarang menyentuh dua lapis di atasnya. |
| **Resource - Capability - Value (1.7.1)** | *"A multi-year, multi-billion dollar investment in technology drove the growth of UPS over the last twenty-five years"*; *"70,000 drivers who are wirelessly connected to UPS main databases located in seventeen major data centers"* | **Resource** yang dimiliki UPS meliputi investasi multi-miliar dolar, 17 data center, 70.000 pengemudi, dan DIAD IV. Dari resource itu, terbentuklah **capability** berupa pelacakan paket secara real-time, dispatch on-demand, dan pengurangan 59 juta lembar kertas per tahun. Hasilnya adalah **value** berupa kapasitas pengiriman 14 juta paket per hari ke 200 negara. Yang perlu dicatat: resource tidak otomatis menghasilkan value. Di antaranya ada capability yang menuntut SDM, proses, dan tata kelola yang benar-benar bekerja. |
| **Jenis IS Value yang Tercapai (1.10)** | *"UPS eliminates the use of 59 million sheets of paper per year"*; *"GPS...to provide drivers with more detailed directions...to improve customer service"* | Ada dua jenis value yang bisa diidentifikasi. Pertama, **efisiensi operasional**: eliminasi 59 juta lembar kertas per tahun secara langsung memangkas biaya cetak dan distribusi data. Kedua, **customer value generation**: GPS membuat pengemudi bisa navigasi lebih akurat ke titik pengiriman, yang berarti layanan lebih cepat dan pelanggan lebih puas. |
| **Domain MSI yang Terlihat dalam Kasus (1.12)** | *"dispatchers and center management to access the driver via his/her DIAD throughout the day by sending generalized text messages"*; *"DIAD IV sends delivery information to the UPS data repository as soon as the delivery information is entered"* | Domain yang dibahas adalah **operasional delivery lapangan**, yaitu komunikasi pengemudi-dispatcher dan transmisi data ke repository pusat. Ini hanya menyentuh level operasional dari tiga level keputusan - transaksi harian dan komunikasi lapangan yang bersifat rutin. |
| **Domain MSI yang Tidak Disinggung Sama Sekali (1.12)** | *(justru absennya bukti inilah yang perlu dianalisis)* | Ada empat domain MSI yang tidak hadir dalam narasi kasus. Pertama, **IT Governance**: siapa yang memutuskan investasi multi-miliar ini dan atas kriteria apa. Kedua, **Change Management**: bagaimana 70.000 pengemudi dilatih setiap kali generasi DIAD baru diluncurkan. Ketiga, **Evaluasi IS Value**: KPI atau metrik apa yang digunakan untuk mengukur keberhasilan DIAD. Keempat, **Keamanan informasi**: bagaimana data lokasi GPS dari 70.000 pengemudi diamankan dari potensi penyalahgunaan. |

---

## BAGIAN B: Kritik Berbasis Kerangka Konseptual

### B.1 - Kasus Ini Bicara Teknologi, Bukan Manajemen Informasi

Kalau kita baca kasus ini dengan hati-hati, terasa ada yang mengganjal. Hampir separuh teksnya berisi daftar spesifikasi hardware: 128MB RAM, GPRS, CDMA radio, 802.11b, Bluetooth, IrDA, Intel XScale 400MHz, Windows CE .NET. Ini terasa lebih seperti brosur produk daripada studi kasus sistem informasi manajemen.

Dari kerangka empat lapis di Bab 1, kasus ini hanya sungguh-sungguh mendeskripsikan **aplikasi** (DIAD IV sebagai perangkat fisik). Ia sedikit menyinggung **sistem informasi** lewat ODS yang *"enables communication with the driver"*, namun berhenti di situ. Tentang **sistem kerja**, yaitu bagaimana 70.000 manusia, puluhan ribu rute, dan teknologi ini saling berinteraksi setiap hari untuk menghasilkan nilai, hampir tidak ada. Apalagi **strategi bisnis** yang menjadi alasan investasi ini dilakukan sejak 1990.

Yang paling mencolok adalah kalimat ini dari kasus: *"What UPS can do is largely a function of its information technology investments."* Kalimat ini secara implisit menyatakan bahwa kesuksesan UPS adalah soal berapa besar mereka berinvestasi di teknologi. Padahal dalam perspektif MSI, teknologi hanyalah satu dari lima unsur sistem. Ada **input** (data paket), **proses** (ODS dan dispatcher yang mengolah data), **output** (konfirmasi delivery dan laporan operasional), **manpower** (70.000 pengemudi yang menjalankan prosedur), dan baru kemudian **teknologi** (DIAD IV). Kasus menonjolkan yang terakhir seolah keempat unsur lainnya tidak ada.

Kesimpulannya, narasi kasus ini adalah *technology showcase* yang memuaskan sebagai artikel teknologi, tetapi tidak cukup untuk menjelaskan mengapa UPS berhasil dari sudut pandang Manajemen Sistem Informasi.

---

### B.2 - Governance yang Tidak Terlihat di Balik Semua Ini

Bab 1.14 membedakan *governance* dari *management*. Governance menjawab pertanyaan: siapa yang memutuskan bahwa investasi ini perlu dilakukan, dan tujuan apa yang ingin dicapai? Management menjawab: bagaimana keputusan itu dijalankan secara operasional? Kasus ini sepenuhnya bercerita tentang lapisan management: driver scan barcode, dispatcher kirim pesan lewat ODS, center management mengakses driver via DIAD. Tidak ada satu paragraf pun yang menyentuh lapisan governance.

Padahal ada setidaknya dua keputusan governance besar yang pasti ada di balik kasus ini, meski tidak disebutkan.

**Pertama, keputusan untuk membangun DIAD sebagai platform proprietary.** UPS bisa saja membeli solusi handheld dari vendor luar (COTS). Mereka memilih untuk mengembangkan sendiri, dari generasi pertama di 1991 hingga DIAD IV. Keputusan ini bukan keputusan teknis - ini keputusan strategis tingkat board atau CIO yang melibatkan pertimbangan make-or-buy, risiko vendor lock-in, dan komitmen biaya R&D jangka panjang. Tidak satu pun dari ini dibahas dalam kasus.

**Kedua, keputusan menjadikan GPS sebagai fitur utama DIAD IV.** GPS disebut sebagai "revolusi" di kasus. Tapi revolusi ini pasti lahir dari keputusan seseorang di level strategis bahwa akurasi navigasi adalah prioritas yang layak diinvestasikan. Apakah karena kompetitor mulai menggunakannya? Karena permintaan pelanggan korporat besar? Atau karena ada regulasi keselamatan transportasi baru? Kasus sama sekali tidak menjawab, padahal di sinilah sesungguhnya letak analisis IT governance yang paling penting.

---

### B.3 - 70.000 Manusia yang Tidak Dibicarakan

Perspektif socio-technical di Bab 1.5.1 menjelaskan bahwa sistem informasi selalu berada di persimpangan antara dimensi manusia dan dimensi teknologi. Ketika salah satu berubah, yang lain pasti ikut terpengaruh, dan keduanya harus dirancang bersama-sama. Kasus menyebut 70.000 pengemudi sebagai fakta angka, tanpa satu kalimat pun tentang apa yang sebenarnya terjadi pada mereka setiap kali generasi DIAD baru diluncurkan.

Ada dua tantangan sosio-teknis yang sangat mungkin dihadapi UPS yang tidak disinggung dalam kasus.

**Pertama, resistensi dari pengemudi veteran karena muscle memory yang sudah terbentuk bertahun-tahun.** Seorang pengemudi yang menggunakan DIAD III selama bertahun-tahun tidak hanya tahu cara pakainya - ia sudah tidak perlu berpikir saat menggunakannya. Urutan tombol, cara pegang saat ambil tanda tangan, ritme scan barcode, semuanya sudah jadi refleks. Ketika DIAD IV datang dengan layar warna baru, layout 45 tombol yang mungkin bergeser, dan GPS yang butuh interaksi tambahan, ia harus belajar ulang - di tengah hari kerja yang menuntut kecepatan. Ini bukan masalah teknologi yang rusak. Ini masalah perubahan perilaku manusia, yang hanya bisa diatasi lewat pelatihan yang baik, pendampingan sesama driver, dan waktu adaptasi yang cukup.

**Kedua, ketegangan antara efisiensi organisasi dan kekhawatiran privasi pengemudi.** GPS di DIAD IV memungkinkan UPS melacak posisi setiap pengemudi secara real-time sepanjang jam kerja. Dari sisi manajemen, ini jelas berguna: rute bisa dioptimasi, waktu idle bisa diidentifikasi, pickup mendadak bisa diberikan ke pengemudi yang paling dekat. Tapi dari sisi pengemudi, khususnya yang tergabung dalam serikat pekerja, ini bisa dirasakan sebagai pengawasan yang terlalu masuk ke ranah privasi. Ketegangan ini tidak bisa diselesaikan dengan kebijakan teknis. Butuh negosiasi sosial, kejelasan tentang bagaimana data lokasi digunakan, dan kepercayaan yang dibangun antara manajemen dan pengemudi.

Kedua tantangan ini adalah domain utama MSI: bukan soal apakah teknologinya berjalan, tapi apakah sistem manusia-teknologinya bisa bekerja secara berkelanjutan dan benar-benar diterima oleh orang-orang yang menjalankannya.

---

## BAGIAN C: Transfer ke Organisasi Saya

### Konteks

Sejak 2022, saya aktif sebagai bagian dari Seksi PUBDEKDOK (Publikasi, Dekorasi, Dokumentasi) di REMAS Masjid Besar Baitul Hikmah (MBBH), Klitren, Gondokusuman, Yogyakarta. Tugas saya mencakup desain grafis proposal dan banner untuk kegiatan besar seperti Idul Fitri dan Idul Adha, dokumentasi foto dan video kegiatan bersama Mas Kurniawan (fotografer sekaligus anggota PDD), serta pembuatan akun Instagram dan Gmail resmi masjid dari nol karena keduanya belum ada sebelumnya.

---

### C.1 - Resource, Capability, dan Value di PUBDEKDOK MBBH

Kalau kita terapkan kerangka Resource - Capability - Value ke PUBDEKDOK, gambarannya menjadi cukup jelas mengapa sistem ini tidak berjalan optimal.

**Resource yang ada secara fisik:**
- Smartphone pribadi saya dan Mas Kurniawan sebagai kamera utama dokumentasi
- Kamera milik Mas Kurniawan yang dipinjamkan ke kegiatan (tidak ada kamera resmi milik masjid)
- Canva dan CapCut di perangkat masing-masing untuk desain dan editing
- Flashdisk pribadi saya sebagai penyimpanan utama file pasca-kegiatan
- Google Drive akun pribadi saya sebagai backup, yang sudah mendekati penuh
- Akun Instagram masjid yang saya buat dan kelola sendiri, kini tidak dapat diakses karena HP saya pernah ter-reset dan password-nya hanya ada di satu tempat tanpa backup
- Gmail resmi masjid yang juga saya buat dari nol, dengan status akses yang saat ini tidak jelas karena tidak ada prosedur handover

**Capability yang terbentuk (atau lebih tepatnya: yang mestinya terbentuk):**
- Produksi desain banner dan proposal untuk Idul Fitri dan Idul Adha
- Dokumentasi visual kegiatan besar masjid
- Publikasi kegiatan Ramadhan 2024/2025 lewat Instagram, yang aktif hanya selama satu periode kemudian berhenti

Saya menyebut ini "mestinya terbentuk" karena dalam praktiknya, capability ini tidak pernah benar-benar stabil. File dokumentasi tersebar di flashdisk saya, HP Mas Kurniawan, HP panitia yang hadir saat kegiatan, dan Drive pribadi saya yang ruangnya terbatas. Kalau ada kegiatan yang berlangsung tanpa saya dan Mas Kurniawan, foto-fotonya tersimpan di HP panitia yang ada tanpa kejelasan akan diupload ke mana. Akun Instagram yang seharusnya jadi kanal distribusi utama kini tidak bisa diakses siapapun. Dan tidak ada anggota PDD lain yang bersedia mengambil alih pengelolaan secara mandiri.

**Value yang seharusnya bisa dicapai** - transparansi visual kegiatan kepada jamaah, arsip institusional untuk pelaporan atau penggalangan donasi yang lebih luas - belum pernah terwujud secara konsisten, karena chain dari resource ke capability ke value tidak pernah terhubung dengan baik.

Ini persis analogi yang sering dipakai dalam diskusi MSI: ada kamera yang bagus (*motor balap*), ada niat mendokumentasikan kegiatan (*keinginan melaju*), tapi tidak ada folder bersama sebagai tempat semua file berkumpul (*jalan raya*), tidak ada admin yang ditunjuk resmi dan punya akses yang tidak bergantung pada satu HP saja (*SIM*), dan tidak ada mekanisme apapun untuk mewariskan akses ke pengurus generasi berikutnya (*aturan lalu lintas*). Hasilnya: semua resource yang ada tidak menghasilkan value yang berkelanjutan.

---

### C.2 - Apa yang Bisa dan Tidak Bisa Dipinjam dari UPS

**Prinsip Single Entry, Central Repository bisa diterapkan.**

Di UPS, driver cukup melakukan satu tindakan yaitu scan barcode, dan data langsung masuk ke repository pusat yang bisa diakses oleh seluruh sistem secara real-time. Prinsip ini sebenarnya bisa diadopsi oleh PUBDEKDOK dalam skala yang jauh lebih sederhana: satu folder Google Drive bersama sebagai *single source of truth* untuk semua file dokumentasi dan desain. Siapapun yang memotret atau membuat desain pada hari kegiatan, wajib upload ke folder itu sebelum pulang. Tidak perlu aplikasi baru, tidak perlu biaya apapun. Yang dibutuhkan hanya SOP yang disepakati dan dijalankan secara konsisten - dan ini murni masalah tata kelola, bukan masalah teknologi.

**Prinsip redundansi akses juga perlu diterapkan.**

UPS membangun 17 data center di berbagai lokasi supaya kalau satu bermasalah, operasi tidak terhenti. Ini adalah prinsip redundancy yang dalam konteks PUBDEKDOK perlu diterapkan pada level manusia: akun media sosial dan email masjid harus dipegang oleh minimal dua orang dengan akses penuh. Kehilangan akses Instagram masjid setelah HP saya ter-reset adalah contoh nyata bahwa *single point of access failure* di level manusia sama berbahayanya dengan kegagalan teknis. Ini bukan kegagalan teknisnya - password-nya bisa saja aman kalau ada di dua tempat berbeda. Ini kegagalan governance: tidak ada SOP handover akun, tidak ada admin cadangan, tidak ada protokol jika pemegang akses tidak tersedia.

**Investasi hardware proprietary milik UPS tidak relevan untuk konteks ini.**

UPS mengembangkan DIAD IV dengan spesifikasi yang mendekati kelas militer: tahan suhu ekstrem, tahan jatuh keras, OS kustom, konektivitas multi-protokol. Ini masuk akal untuk organisasi yang menggerakkan 14 juta paket per hari dengan revenue miliaran dolar. PUBDEKDOK MBBH adalah seksi sukarela nirlaba tanpa anggaran teknologi, yang dijalankan oleh pemuda REMAS di luar jam kerja dan kuliah. Solusi apapun yang butuh pembelian perangkat atau lisensi berbayar sudah otomatis tidak kontekstual. Yang tepat adalah solusi *zero-cost, zero-hardware-dependency*: Google Drive free tier, WhatsApp yang sudah semua orang pakai, dan Canva Free yang sudah familiar digunakan.

**Sistem ODS real-time UPS juga tidak relevan.**

UPS mengoperasikan komunikasi nirkabel real-time antara dispatcher dan 70.000 pengemudi lintas negara dengan SLA yang ketat. Ini tidak ada hubungannya dengan PUBDEKDOK yang beranggotakan kurang dari lima orang aktif di satu lingkungan masjid. Masalah koordinasi kami bukan soal platform komunikasi - WhatsApp sudah lebih dari cukup. Masalahnya adalah tidak ada SOP yang mengatur kapan panitia perlu menghubungi PUBDEKDOK, berapa hari sebelum kegiatan, dan dalam format permintaan seperti apa. Akibatnya permintaan desain dan dokumentasi sering datang mendadak. Ini masalah tata kelola proses, bukan masalah platform teknologi.

---

### Ringkasan Bagian C

| Dimensi | Kondisi PUBDEKDOK MBBH | Konsep MSI yang Relevan |
|:---|:---|:---|
| **Resource** | Semua perangkat (HP, kamera, flashdisk, Drive, akun IG dan Gmail) adalah milik pribadi anggota, bukan aset institusional masjid | *Resource* ada, tapi tidak dimiliki organisasi secara formal |
| **Capability** | Desain dan dokumentasi bisa dibuat, tapi bergantung penuh pada satu orang (key-person dependency terhadap Fajar) | Capability tidak stabil karena tidak ada SDM cadangan dan tidak ada SOP produksi |
| **Value** | Publikasi aktif hanya satu periode (Ramadhan 2024/2025), arsip tidak terpusat, akun IG kini tidak bisa diakses | Value tidak terbentuk secara berkelanjutan karena chain resource ke capability ke value terputus |
| **Penyimpanan** | File tersebar di flashdisk Fajar, HP Mas Kurniawan, HP panitia, dan Drive pribadi yang hampir penuh - tidak ada single source of truth | Ketiadaan *central repository* = tidak ada Single Source of Truth (SSOT) |
| **Akses Akun** | Instagram masjid tidak dapat diakses setelah HP Fajar ter-reset; password hanya tersimpan di satu lokasi | Single point of access failure = kegagalan *governance*, bukan kegagalan teknis |
| **Koordinasi** | Permintaan desain dan dokumentasi sering datang mendadak, tidak ada lead time yang disepakati | Ketiadaan SOP proses = masalah tata kelola, bukan masalah platform komunikasi |
| **Praktik UPS yang relevan** | Prinsip *single entry, central repository* dan redundansi akses (min. 2 admin per akun) | Dapat diadopsi dengan Google Drive shared folder dan dual admin - biaya nol |
| **Praktik UPS yang tidak relevan** | Hardware proprietary multi-miliar (DIAD IV) dan sistem ODS real-time global | Konteks tidak sebanding: UPS = korporasi global, PUBDEKDOK = seksi sukarela nirlaba |

---

## Catatan

Seluruh contoh dan detail di Bagian C berasal dari pengalaman langsung sebagai anggota PUBDEKDOK MBBH sejak 2022, termasuk kehilangan akses Instagram masjid, kondisi penyimpanan file yang tersebar di banyak perangkat pribadi, pembuatan Gmail dan akun Instagram masjid dari nol tanpa prosedur handover, dan ketiadaan anggota lain yang bersedia melanjutkan pengelolaan konten secara mandiri.
