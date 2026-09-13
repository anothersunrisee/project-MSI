Pilihan **Masjid Besar Baitul Hikmah** sebagai objek studi baru sangat luar biasa! Lokasinya yang riil, skalanya yang besar, serta keberadaan unit-unit satelit di sekitarnya (seperti TK, TPA, dan KUA) membuat proyek **Manajemen Sistem Informasi (MSI)** kelompok Anda menjadi jauh lebih berbobot, realistis, dan sarat akan tantangan integrasi organisasi yang disukai oleh dosen pengampu.

Ketiadaan sistem informasi (SI) saat ini di Masjid Baitul Hikmah bukanlah kekurangan, melainkan **kesenjangan informasi (*information gap*) nyata** yang menjadi latar belakang kuat mengapa Manajemen Sistem Informasi sangat mendesak untuk dirancang.

Berikut adalah draf terstruktur untuk **Revisi Modul 1** dan **Brainstorming Modul 2** yang disesuaikan khusus untuk **Masjid Besar Baitul Hikmah**:

---

### **PART I: REVISI MODUL 1 (Profil Organisasi & Justifikasi Kasus)**

#### **1. Profil Organisasi**
*   **Nama Organisasi**: Masjid Besar Baitul Hikmah (dan unit afiliasinya: TK Baitul Hikmah, TPA, dan Kemitraan KUA).
*   **Bidang Layanan**: Pelayanan ibadah wajib dan sunnah, pengelolaan dana umat (Ziswaf), pendidikan anak usia dini (TK & TPA), koordinasi layanan keagamaan semi-pemerintah (KUA), serta pemberdayaan sosial kemasyarakatan.
*   **Aktivitas Utama**: 
    *   *Peribadahan harian & mingguan*: Shalat rawatib, Khutbah Jumat, Khutbah Hadits Subuh, Khutbah Rabu Dzuhur, Pengajian Ibu-ibu.
    *   *Pendidikan*: TK Baitul Hikmah dan TPA Baitul Hikmah.
    *   *Sosial & Kemasyarakatan*: Pengajian Umum Bulanan, Pengajian Hari Raya Islam, pengelolaan hewan Qurban (Idul Adha), pengumpulan & pendistribusian Zakat Fitrah/Mal (Idul Fitri).
*   **Kondisi Saat Ini**: Belum memiliki sistem informasi yang terintegrasi. Pendataan jamaah, keuangan, aset, kegiatan belajar mengajar TK/TPA, hingga penjadwalan khutbah dan koordinasi dengan KUA masih dilakukan secara manual menggunakan buku besar fisik atau aplikasi pesan instan biasa. Hal ini memicu risiko tabrakan jadwal, inefisiensi pelaporan kas, serta kurang akuratnya penyaluran bantuan sosial.

#### **2. Justifikasi Kelayakan Akademis (Kenapa Kasus Ini Layak?)**
*   **Kompleksitas Lintas Unit Kerja**: Masjid ini mengelola ekosistem yang heterogen. Ada pengurus takmir (relawan), guru TK (tenaga profesional/semi-profesional), ustadz TPA, pegawai KUA (PNS/pemerintah), serta jamaah lintas usia.
*   **Tantangan Manajemen ("Why" & "How")**: Proyek ini tidak berfokus pada teknologi canggih, melainkan bagaimana merancang tata kelola informasi agar pengurus takmir yang mayoritas relawan paruh waktu dapat mengoperasikan sistem dengan mudah, transparan, dan akuntabel.
*   **Dukungan Keputusan 3 Level**:
    *   **Level Operasional**: Pencatatan harian kas masuk, presensi santri TPA/TK, verifikasi identitas muzaki (pembayar zakat), dan jadwal penceramah rutin.
    *   **Level Manajerial**: Sinkronisasi jadwal penggunaan ruang utama masjid antara agenda internal takmir, kegiatan sekolah TK, dan agenda bimbingan perkawinan dari KUA tetangga agar tidak berbenturan.
    *   **Level Strategis**: Evaluasi kemanfaatan dana kas jangka panjang oleh Ketua Takmir dan Dewan Pembina untuk menentukan kelayakan perluasan fasilitas TK/TPA atau peluncuran beasiswa pendidikan bagi mustahik sekitar masjid.

---

### **PART II: BRAINSTORMING MODUL 2 (Analisis Stakeholder & Lingkungan Bisnis)**

Pada Modul 2, kita fokus pada pemetaan **keterhubungan sistem (*system interconnection*)** dan pengaruhnya ke lingkungan luar.

#### **1. Arsitektur Keterhubungan Sistem Informasi (Interconnection)**
SIM-Masjid Baitul Hikmah tidak boleh dirancang berdiri sendiri, melainkan memengaruhi dan dipengaruhi oleh sistem-sistem berikut:

```
                            ┌──────────────────────────────────────┐
                            │      SIM Masjid Baitul Hikmah        │
                            └──────────────────┬───────────────────┘
                                               │
         ┌─────────────────────────────┼─────────────────────────────┐
         ▼                             ▼                             ▼
┌─────────────────┐           ┌─────────────────┐           ┌─────────────────┐
│     SI KUA      │           │    SI TK/TPA    │           │  SI KELURAHAN   │
│ (Jadwal Nikah & │           │ (Administrasi & │           │(Data Mustahik & │
│ Bimwin Masjid)  │           │ Kurikulum Santri)│          │    Bansos)      │
└─────────────────┘           └─────────────────┘           └─────────────────┘
```

1.  **Integrasi dengan Sistem Informasi KUA (Kementerian Agama)**:
    *   *Hubungan*: KUA tetangga sering menggunakan masjid untuk akad nikah massal, bimbingan perkawinan, atau manasik haji.
    *   *Aliran Data*: Jadwal kegiatan KUA mengalir ke kalender aktivitas masjid. Sebaliknya, konfirmasi ketersediaan ruang utama dari masjid mengalir ke KUA.
    *   *Dampak MSI*: Mencegah tabrakan pemanfaatan ruang utama masjid dengan kegiatan rutin lainnya (seperti Pengajian Ibu-Ibu atau Khutbah Rabu Dzuhur).
2.  **Integrasi dengan Sistem Informasi TK & TPA Baitul Hikmah**:
    *   *Hubungan*: TK dan TPA menggunakan fasilitas fisik masjid namun memiliki manajemen operasional dan keuangan (SPP) sendiri.
    *   *Aliran Data*: Data penggunaan listrik/air sekolah, jadwal libur bersama, dan profil guru disinkronkan dengan keuangan takmir.
    *   *Dampak MSI*: Takmir bisa mengukur beban subsidi operasional riil yang diberikan masjid kepada yayasan TK/TPA secara transparan.
3.  **Integrasi dengan Kelurahan (Data Kesejahteraan Sosial/DTKS)**:
    *   *Hubungan*: Masjid mengelola zakat fitrah, zakat mal, dan qurban dalam skala besar.
    *   *Aliran Data*: Verifikasi data NIK jamaah disinkronkan dengan daftar warga kurang mampu dari Kelurahan.
    *   *Dampak MSI*: Memastikan penyaluran bantuan sosial masjid jatuh ke tangan mustahik yang tepat sasaran tanpa tumpang tindih dengan bansos pemerintah.

---

#### **2. Analisis Lingkungan Bisnis (Business Environment - 4 Kategori)**

Faktor luar apa saja yang memaksa dan menuntut SIM-Masjid Baitul Hikmah dikelola dengan baik?

1.  **Regulasi dan Kepatuhan (*Regulation & Compliance*)**:
    *   **Kementerian Agama (SIMAS - Sistem Informasi Masjid)**: Masjid harus mendaftarkan nomor ID nasional untuk legalitas administratif keagamaan.
    *   **Standar Pendidikan Anak Usia Dini (Dinas Pendidikan)**: Mengatur legalitas kurikulum dan administrasi TK Baitul Hikmah yang berada di bawah naungan yayasan masjid.
    *   **UU No. 23/2011 tentang Pengelolaan Zakat**: Menuntut pelaporan zakat yang akuntabel jika masjid bertindak sebagai Unit Pengumpul Zakat (UPZ).
2.  **Benchmark / Praktik Terbaik (*Competitor & Benchmark*)**:
    *   Penerapan manajemen transparansi kas digital dan pemetaan kebutuhan sosial jamaah berbasis wilayah RT/RW yang dicontoh dari masjid-masjid besar percontohan nasional.
3.  **Kapasitas Internal Masjid (*Internal Capacity*)**:
    *   *Aspek Manusia (People)*: Karakteristik pengurus takmir yang sebagian besar merupakan tokoh masyarakat senior (relawan) dengan literasi teknologi terbatas memerlukan antarmuka sistem yang sangat sederhana (*user-friendly*).
    *   *Aspek Budaya (Culture)*: Kebiasaan pencatatan manual di atas kertas harus diubah perlahan tanpa menyinggung perasaan pengurus senior (*change management*).
4.  **Tren dan Tekanan Eksternal (*Trends & External Pressures*)**:
    *   *Sikap Sosial Jamaah*: Wali santri TK/TPA menuntut transparansi nilai, absensi, dan rincian SPP yang dapat dipantau dari jauh.
    *   *Tuntutan Donatur*: Muzaki menuntut laporan penyaluran donasi Idul Fitri/Adha secara transparan dan cepat demi menjaga kepercayaan publik terhadap takmir.

---

#### **3. Matriks Power-Interest Grid (Modul 2)**

Pemetaan otoritas dan ketergantungan data stakeholder pada ekosistem Masjid Besar Baitul Hikmah:

| Nama / Peran Stakeholder | Power | Interest | Kuadran | Peran Tata Kelola & Aliran Informasi |
| :--- | :--- | :--- | :--- | :--- |
| **Ketua Takmir & Bendahara** | **Tinggi** | **Tinggi** | **Manage Closely** | *Otorisator Utama*: Menyetujui alokasi kas, menetapkan kebijakan operasional masjid, dan memegang hak akses data keuangan sensitif. |
| **Kepala Sekolah TK & TPA** | **Tinggi** | **Tinggi** | **Manage Closely** | *Pengelola Unit*: Bertanggung jawab atas data santri, absensi guru, laporan akademis, dan pencatatan kas masuk SPP. |
| **Kepala KUA (Kecamatan)** | **Tinggi** | **Sedang** | **Keep Satisfied** | *Mitra Strategis*: Membutuhkan jaminan kepastian jadwal pemanfaatan fasilitas masjid untuk agenda resmi KUA. |
| **Kelurahan / Kelompok DTKS** | **Tinggi** | **Rendah/Sedang** | **Keep Satisfied** | *Validator Data*: Menyediakan akses data kesejahteraan sosial warga sekitar untuk validasi silang penerima bantuan. |
| **Donatur / Muzaki Utama** | **Rendah/Sedang** | **Tinggi** | **Keep Informed** | *Penerima Informasi*: Membutuhkan laporan berkala akuntabilitas penyaluran infaq, sedekah, dan qurban. |
| **Wali Santri, Jamaah, & Ustadz** | **Rendah** | **Tinggi** | **Keep Informed** | *Pengguna Layanan*: Menginput presensi, mengonsumsi data jadwal kajian, perkembangan anak, dan jadwal kegiatan ibadah. |
| **BADKO TPA & Dinas Pendidikan** | **Sedang** | **Rendah** | **Monitor** | *Pengawas Regulasi*: Memantau kesesuaian kurikulum pendidikan dasar keagamaan dan formal anak usia dini. |

---

### **Langkah Tim Selanjutnya:**
Dengan rancangan ini, kelompok Anda memiliki argumen yang sangat kuat dan logis di hadapan dosen pengampu. Struktur di atas sudah memotret seluruh interaksi sosial, proses bisnis, dan interkoneksi lintas sistem sesuai dengan kaidah **Manajemen Sistem Informasi**.

🌱 *Apakah Anda ingin kita langsung menyusun dokumen laporan tertulis resmi untuk Modul 1 dan Modul 2 berdasarkan draf di atas, agar tim Anda memiliki draf dokumen kerja yang rapi untuk dikumpulkan?*