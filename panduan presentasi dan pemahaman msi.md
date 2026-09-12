# PANDUAN PRESENTASI & PEMAHAMAN MSI KELOMPOK 1 F1
## Kasus: Sistem Informasi Manajemen Masjid Besar Baitul Hikmah (SIM-BaitulHikmah)
*Disusun untuk: Muhammad Riski (24050530029), Fajar Ahnaf Mahardika (24050530030), Muhadzdzib Terry Al-Fauzan (24050530052)*
*Mata Kuliah: Praktik Manajemen Sistem Informasi (PTF60234) — Dosen: Dr. Ratna Wardani, S.Si., M.T.*

---

## 👶 BAGIAN 1: Pemahaman Konsep Inti (Bahasa Bayi & Intuisi MSI)

### 1. Mengapa Bu Ratna Menolak Pola Pikir "Aplikasi-Sentris"?
> **Analogi Motor vs Aturan Jalan (Filosofi Utama Bu Ratna):**
> * Bayangkan kalian berhasil merakit sebuah **sepeda motor balap yang sangat kencang dan keren** (ini analogi dari *Aplikasi / Software*).
> * Tapi motor itu kalian taruh di tengah sawah yang tidak ada jalannya, tidak ada rambu lalu lintasnya (SOP), dan kalian yang naik tidak punya SIM / lisensi resmi (Otoritas). Motor secanggih apa pun tidak akan ada gunanya, malah berisiko bikin celaka!
> * **Anak Rekayasa Perangkat Lunak (RPL):** Bangga karena motornya bisa jalan (fokus ke coding, tombol, dan database).
> * **Anak Manajemen Sistem Informasi (MSI - Kita):** Yang dipikirkan adalah **sistem lalu lintas organisasinya**! Siapa yang berhak menyetir? Jalannya lewat mana? Polisi mana yang mengawasi (BAZNAS/KUA)? Kalau motor mogok, siapa yang bertugas memperbaikinya?

**Kesimpulan:** SIM-BaitulHikmah bukan sekadar proyek bikin website/aplikasi, melainkan **solusi tata kelola agar pengurus masjid tidak salah mengambil keputusan**.

---

### 2. Mengapa Kasus Masjid Baitul Hikmah Sangat Kuat untuk MSI?
Kasus ini memiliki 5 masalah tata kelola riil di lapangan yang sangat relevan dengan teori MSI:
1. **Duit Infaq (Rp 2–3 Juta/Bulan):** Dicatat ganda oleh Bendahara dan Sekretaris di buku kas dan file Word/Excel pribadi masing-masing tanpa sinkronisasi. Akibatnya, tiap akhir bulan saat rekapitulasi, **angkanya sering selisih dan memicu kebingungan**. *(Masalah: Ketiadaan Single Source of Truth).*
2. **Jadwal 15 Khatib Jumat:** Dikoordinasikan hanya lewat chat WhatsApp pribadi. Akibatnya, **kerap terjadi jadwal bentrok (*double booking*) atau khatib batal mendadak**. Saat shalat Jumat takmir panik mencari pengganti, dan saat tarawih Ramadhan terpaksa di-skip lalu marbot disuruh membaca hadits. *(Masalah: Tidak adanya Kalender Penjadwalan Terpadu & Prosedur Kontinjensi).*
3. **Santri TPA (< 30 Santri):** Diajar oleh 3 marbot dan 1 ustadz. Kartu presensi dan pelacak jilid Iqra/Al-Quran masih berupa lembaran kertas manual yang sering tercecer. Padahal, masjid diwajibkan menyetor laporan berkala ke **BADKO TPA Kemantren Gondokusuman**. *(Masalah: Data Silo & Kepatuhan Regulasi Eksternal).*
4. **Kepanitiaan Qurban (3 Sapi, 10 Kambing):** Pembagian kupon daging ke warga 3 RW dicatat manual di lapangan. Sangat rawan salah hitung jatah, duplikasi kupon, dan antrean tidak tertib. *(Masalah: Beban Puncak Musiman / Peak Load tanpa Basis Data NIK/KK).*
5. **Dinamika Manusia (*Change Management*):**
   * Remaja Masjid (REMAS) terdaftar 17 pemuda yang melek gawai, **tetapi hanya aktif musiman saat Idul Fitri dan Idul Adha**.
   * Yang menjaga masjid setiap hari dan merangkap mengajar santri TPA adalah **3–4 Marbot sepuh**.
   * *Artinya:* Sistem harian tidak boleh dibuat rumit seperti dashboard korporat karena operator lapangannya adalah marbot. Namun untuk event qurban dan zakat, 17 pemuda REMAS dapat difungsikan sebagai operator intensif musiman.

---

## 🧩 BAGIAN 2: Bedah Laporan Modul 1 & Modul 2

### Modul 1: Fondasi Organisasi & Sistem
* **Pertanyaan Kunci:** *"Kenapa masjid ini butuh sistem informasi, dan apa saja komponen pembentuknya?"*
* **Tiga Level Keputusan (Pertanyaan Favorit Dosen):**
  1. **Level Operasional (Pelaksana Lapangan / 3 Marbot & Amil):** Menangani data transaksi harian.  
     *Contoh:* Mencatat perolehan kotak infaq Jumat, mengabsen santri TPA hari ini, dan mencatat pendaftar qurban.
  2. **Level Manajerial (Pengelola Taktis / Bendahara, Sekretaris, Koordinator TPA):** Menangani rekonsiliasi dan pemantauan bulanan.  
     *Contoh:* Merekonsiliasi pembukuan kas infaq bulanan (Rp 2–3 juta) agar tidak selisih, menyusun jadwal 15 khatib agar tidak bentrok, menyiapkan laporan semester ke BADKO TPA.
  3. **Level Strategis (Pimpinan Puncak / Ketua Takmir & Dewan Penasihat):** Menangani evaluasi dan kebijakan jangka panjang.  
     *Contoh:* Mengevaluasi tren saldo kas 1 tahun ke depan, memutuskan kebijakan kuota beasiswa santri dhuafa, dan menyetujui program renovasi aula.
* **Lima Unsur Sistem:**
  * **Input:** Infaq bulanan, NIK mustahik, data santri TPA, jadwal khatib.
  * **Proses:** Rekonsiliasi kas terpusat, plotting kupon per KK/NIK, tracking Iqra, notifikasi jadwal otomatis.
  * **Output:** Laporan keuangan digital tanpa selisih, laporan ke BADKO, kalender ruang/khatib publik.
  * **Manpower:** Bendahara, Sekretaris, 3 Marbot, 1 Ustadz, 17 REMAS.
  * **Teknologi:** WiFi Pemkot Yogyakarta, CCTV masjid, Web terpusat ramah marbot.

### Modul 2: Peta Stakeholder & Lingkungan Bisnis
* **Pertanyaan Kunci:** *"Siapa saja orangnya, dan aturan apa dari luar yang memaksa sistem ini harus ada?"*
* **Power-Interest Grid:**
  * **Manage Closely (Power Tinggi, Interest Tinggi):** Ketua Takmir, Bendahara, Sekretaris, dan Pengelola TPA (3 Marbot & 1 Ustadz).
  * **Keep Satisfied (Power Tinggi, Interest Sedang):** Lembaga luar pemegang otoritas hukum!
    * **KUA Kemantren Gondokusuman:** Menggunakan aula masjid minimal 1x/bulan untuk akad nikah warga.
    * **BAZNAS Kota Yogyakarta:** Mengawasi legalitas UPZ dan audit kepatuhan ZIS.
    * **Kelurahan Klitren (DTKS):** Memegang basis data warga miskin tingkat RW untuk validasi zakat dan kupon qurban.
  * **Keep Informed (Power Rendah, Interest Tinggi):** Jamaah 400 orang, Wali Santri, Muzaki, dan Shahibul Qurban.
  * **Monitor (Power Rendah, Interest Rendah):** Vendor jaringan WiFi Pemkot dan sistem CCTV.
* **Lingkaran Konsentris (Analisis Lingkungan Bisnis):**
  Aplikasi berada di inti terdalam, tetapi bentuk fitur-fiturnya didikte oleh aturan lapisan terluar: UU No. 23/2011 (Zakat), legalitas SIMAS Kemenag (ID `01.4.34.71.03.000032`), tanah BMN (Barang Milik Negara), dan standar BADKO TPA.

---

## 🎙️ BAGIAN 3: Naskah / Skrip Presentasi (Dibagi 3 Pembicara)

*Estimasi Durasi: 4 – 5 Menit. Format ringkas, percaya diri, dan berbobot akademis.*

### 🗣️ Pembicara 1: Latar Belakang & Profil Organisasi (Riski)
> *"Assalamu’alaikum Warahmatullahi Wabarakatuh. Selamat pagi Bu Ratna dan teman-teman semua. Kami dari Kelompok 1 F1 akan memaparkan progres praktikum Manajemen Sistem Informasi kami dengan judul SIM-BaitulHikmah.*
>
> *Sebagai refleksi awal, kami sempat mengajukan kasus UNYParkir. Namun berdasar evaluasi dan arahan Bu Ratna, kami menyadari bahwa MSI membutuhkan keterbukaan data empiris yang nyata. Karena sistem internal UNY sangat tertutup bagi mahasiswa, kami memigrasikan kasus ke Masjid Besar Baitul Hikmah di Kemantren Gondokusuman.*
>
> *Masjid ini terdaftar resmi di SIMAS Kemenag RI dengan ID `01.4.34.71.03.000032`, berdiri sejak tahun 1970 di atas tanah Barang Milik Negara (BMN), dan melayani sekitar 400 jamaah di 3 RW. Masjid mengelola infaq rutin Rp 2–3 juta per bulan, menyelenggarakan pendidikan TPA, serta kepanitiaan qurban tahunan 3 sapi dan 10 kambing. Sayangnya, seluruh tata kelola informasi saat ini masih terfragmentasi dan manual menggunakan buku catatan fisik, Word/Excel pribadi, serta koordinasi informal via WhatsApp."*

### 🗣️ Pembicara 2: Modul 1 — Tata Kelola Informasi & 3 Level Keputusan (Fajar)
> *"Melanjutkan dari Riski, pada Modul 1 kami membedah mengapa SIM-BaitulHikmah ini dibutuhkan melalui perspektif tata kelola informasi, bukan sekadar membangun perangkat lunak.*
>
> *Masalah nyata yang kami temukan adalah ketiadaan 'single source of truth'. Uang kas infaq Rp 2–3 juta dipegang oleh dua orang sekaligus—Bendahara dan Sekretaris—di file spreadsheet laptop masing-masing tanpa sinkronisasi, sehingga kerap memicu selisih perhitungan saat rekapitulasi bulanan.*
>
> *Sistem yang kami rancang menghubungkan tiga level keputusan secara vertikal:
> Pertama, level Operasional: 3 marbot menginput presensi santri TPA dan kotak infaq harian.
> Kedua, level Manajerial: Bendahara dan Sekretaris merekonsiliasi laporan kas bulanan yang sinkron, menyusun jadwal 15 khatib agar tidak terjadi bentrok atau pembatalan mendadak, serta menyiapkan kupon qurban.
> Ketiga, level Strategis: Ketua Takmir dapat mengevaluasi tren kas dan mengambil kebijakan program beasiswa santri dhuafa berbasis bukti (*evidence-based decision making*)."*

### 🗣️ Pembicara 3: Modul 2 — Stakeholder & Lingkungan Bisnis (Terry)
> *"Pada Modul 2, kami memetakan para pemangku kepentingan dan lingkungan bisnis yang melingkupi masjid. Masjid bukanlah organisasi yang terisolasi, melainkan dipengaruhi kuat oleh ekosistem eksternal.*
>
> *Dalam pemetaan Power-Interest Grid, kami menempatkan KUA Kemantren Gondokusuman pada posisi Keep Satisfied karena KUA menggunakan aula masjid minimal sebulan sekali untuk akad nikah warga, sehingga kepastian jadwal ruang bersifat otoritatif. Begitu pula BAZNAS dan Kelurahan Klitren untuk verifikasi silang data mustahik zakat dan kupon qurban per KK.*
>
> *Salah satu temuan empiris terpenting kami dalam aspek perilaku organisasi (*change management*) adalah karakteristik 17 pemuda Remaja Masjid (REMAS). Di atas kertas mereka terdaftar 17 orang, namun fakta lapangan membuktikan mereka hanya aktif musiman—yaitu saat Idul Fitri dan Idul Adha. Sementara operasional harian dijalankan oleh 3 marbot sepuh.*
>
> *Oleh karena itu, sistem harian kami rancang dengan antarmuka yang sangat sederhana agar marbot tidak mengalami resistansi teknologi, sementara 17 pemuda REMAS kami posisikan sebagai operator intensif musiman saat kepanitiaan qurban dan zakat fitrah. Sekian presentasi dari kelompok kami, terima kasih."*

---

## 🎯 BAGIAN 4: Cheat Sheet Tanya-Jawab Kritis (Q&A Dosen)

Berikut adalah jawaban taktis jika Bu Ratna menguji pemahaman kalian:

#### ❓ Pertanyaan 1: "Apa bedanya proyek SIM Masjid kalian ini dengan tugas akhir mahasiswa Informatika biasa yang membuat Web Masjid?"
* **Kunci Jawaban:**
  > *"Bedanya sangat mendasar, Bu. Proyek pemrograman/RPL berfokus pada **produk teknis**: bahasa pemrograman apa yang dipakai, bagaimana skema database-nya, dan apa saja fitur CRUD-nya. Sedangkan di MSI, fokus kami adalah pada **Tata Kelola Informasi (Information Governance) dan Pengambilan Keputusan**.*
  >
  > *Kami menganalisis siapa yang memiliki otoritas atas data kas, bagaimana menyinkronkan data santri TPA agar memenuhi standar pelaporan BADKO, bagaimana mencegah bentrok jadwal 15 khatib Jumat, dan bagaimana strategi adopsi sistem bagi marbot senior agar teknologi tidak mangkrak."*

#### ❓ Pertanyaan 2: "Masjid Baitul Hikmah kan kasnya cuma Rp 2–3 juta per bulan, santri di bawah 30. Kenapa harus repot dibuatkan SIM? Pakai Excel saja kan cukup?"
* **Kunci Jawaban:**
  > *"Justru fakta lapangan kami membuktikan bahwa penggunaan Excel saat ini menimbulkan kegagalan tata kelola, Bu. Data kas dipegang oleh dua orang (Bendahara dan Sekretaris) di laptop masing-masing tanpa mekanisme sinkronisasi, sehingga setiap akhir bulan kerap terjadi selisih rekapitulasi kas.*
  >
  > *Selain itu, Excel tidak bisa menyelesaikan masalah operasional seperti koordinasi 15 khatib Jumat yang sering bentrok via WhatsApp, atau kartu presensi santri TPA yang tercecer. Nilai informasi dari SIM bukan diukur dari besarnya nominal rupiah, melainkan dari **akuntabilitas publik dan pencegahan disinformasi** di hadapan jamaah dan lembaga pembina seperti BAZNAS dan Kemenag."*

#### ❓ Pertanyaan 3: "Kenapa 17 anggota REMAS tidak kalian jadikan pengelola utama sistem harian?"
* **Kunci Jawaban:**
  > *"Ini merupakan temuan empiris kami terkait kapasitas internal dan perilaku organisasi, Bu. Secara administratif di SIMAS Kemenag memang tercatat 17 anggota REMAS, tetapi fakta sosiologis lapangan menunjukkan mereka adalah mahasiswa dan pekerja yang keaktifannya **musiman**, hanya hadir saat momentum Idul Fitri dan Idul Adha.*
  >
  > *Jika kami memaksakan operasional harian bergantung pada REMAS, sistem pasti akan terhenti. Karena itu, arsitektur operasional harian kami rancang ramah pengguna bagi 3 marbot dan pengurus inti, sementara 17 pemuda REMAS kami posisikan sebagai operator musiman saat menangani beban puncak kepanitiaan qurban dan zakat fitrah."*

---
*Dokumen ini menjadi pegangan internal Kelompok 1 Kelas F1 untuk persiapan presentasi dan responsi Praktik Manajemen Sistem Informasi.*
