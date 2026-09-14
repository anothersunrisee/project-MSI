# LAPORAN PRAKTIKUM MINGGUAN
## Manajemen Sistem Informasi — PTF60234
**Universitas Negeri Yogyakarta | Fakultas Teknik | Prodi Pendidikan Teknik Informatika S1**

---

## 1. Identitas Laporan

| Identitas | Isian |
|---|---|
| **Nama Kelompok** | Kelompok 1 — Kelas F1 |
| **Anggota (NIM/Nama)** | 1. Muhammad Riski — 24050530029 |
| | 2. Fajar Ahnaf Mahardika — 24050530030 |
| | 3. Muhadzdzib Terry Al-Fauzan — 24050530052 |
| **Pertemuan ke-** | 3 |
| **Tanggal Pelaksanaan** | 7 September 2026 |
| **Organisasi/Kasus yang Digunakan** | Masjid Besar Baitul Hikmah — SIM-BaitulHikmah |

---

## 2. Tujuan Kegiatan

Mahasiswa mampu mengidentifikasi akar masalah pengelolaan sistem informasi pada organisasi kasus Masjid Besar Baitul Hikmah dan menentukan prioritas solusi menggunakan metode penelusuran terstruktur (*Fishbone Diagram* dan teknik *5-Why*) serta Matriks Prioritas (Dampak vs Upaya) berbasis bukti empiris lapangan yang tervalidasi.

---

## 3. Uraian Pelaksanaan Kegiatan

### 3.1 Identifikasi Masalah Berbasis Triangulasi Bukti Multi-Sumber
Kegiatan praktikum Pertemuan 3 diawali dengan membedah data empiris yang telah dihimpun dari berbagai instrumen lapangan pada Pertemuan 1 dan 2. Sesuai instruksi modul dan penegasan akademis dosen pengampu (Dr. Ratna Wardani, S.Si., M.T.), perancangan sistem informasi tidak boleh berangkat dari asumsi, opini sepihak, atau bias solusi (*solution-first bias*). Sebaliknya, analisis wajib berakar pada pemahaman mendalam atas persoalan tata kelola organisasi nyata. Oleh karena itu, kelompok menerapkan **metode triangulasi data empiris** dengan memadukan empat sumber bukti yang saling mengonfirmasi:
1. **Wawancara Mendalam Narasumber Primer:** Keterangan langsung dari Bpk. Mardiyanto selaku Sekretaris I Takmir Masjid Besar Baitul Hikmah (menjabat aktif sejak 2004) yang menguraikan alur operasional harian, insiden fatal kerusakan perangkat keras sekretariat pada Februari 2026, kondisi pembukuan manual bendahara, mekanisme pendaftaran hewan qurban, serta penentuan mustahik zakat fitrah.
2. **Observasi Partisipatif Internal (*Participant Observation*):** Catatan lapangan langsung dari Fajar Ahnaf Mahardika (anggota tim peneliti sekaligus kader aktif Remaja Masjid / REMAS dan panitia operasional kegiatan Ramadhan serta Idul Adha di Masjid Baitul Hikmah). Observasi ini menyingkap fakta gesekan di tingkat akar rumput: ketiadaan Standard Operating Procedure (SOP) tertulis, alur koordinasi berbelit (harus bertanya dan konfirmasi silang ke figur A, B, C, D), tradisi daur-ulang berkas kepanitiaan lama dari harddisk lokal secara turun-temurun (*hard drive legacy*), serta fenomena *sleeping committee* di mana puluhan nama tercantum di Surat Keputusan (SK) namun pasif dalam eksekusi fisik.
3. **Data Parsial Unit Pendidikan TPA:** Formulir checklist dan konfirmasi daring bersama Bpk. Jefri Nur Ihsan, SE.I. (Ketua II Takmir merangkap Direktur TPA Baitul Hikmah) yang memverifikasi bahwa presensi santri dan ustadz masih tersimpan di lembar kerja Excel lokal pada komputer personal, serta jalur perizinan operasional (IZOP) Kemenag yang masih mengandalkan relasi pesan instan personal staf tanpa kanal institusional formal.
4. **Studi Komparasi Lapangan & Benchmark Digital:** Analisis komparatif terhadap praktik transparansi terbuka berbasis swadaya di Masjid Mujur Al-Amin (Karangnongko) dengan sistem *dual custody* kas kotak infak Jumat dan Papan Takjil Terbuka, serta benchmark kematangan digitalisasi publikasi dan 13 *campaign* donasi daring terintegrasi di Masjid Nurul Ashri Deresan (*masjidnurulashri.com*).

Melalui proses triangulasi multi-sumber tersebut, kelompok mengidentifikasi 4 masalah tata kelola organisasi (3 terverifikasi dan 1 hipotesis kerja) yang dirumuskan secara tegas membedakan antara **masalah organisasi (sebab struktural)** dan **akibat lapangan yang ditimbulkannya**.

### 3.2 Penelusuran Sebab-Akibat Menggunakan *Fishbone Diagram* (Ishikawa, 1976)
Setelah memetakan daftar masalah, kelompok memilih masalah tata kelola paling mendasar yang menjadi ancaman kelangsungan organisasi (*business continuity threat*), yaitu: **Ketiadaan regulasi internal dan SOP pengelolaan serta pencadangan data resmi dari tingkat pembina (Kemenag/KUA) hingga takmir masjid, yang berakibat fatal pada musnahnya 70% data arsip dan administrasi akibat kerusakan PC sekretariat pada Februari 2026**. 

Kelompok menyusun *Fishbone Diagram* (Diagram Tulang Ikan) dengan membaginya ke dalam 6 (enam) kategori penyebab yang disesuaikan dengan konteks organisasi pengelola tempat ibadah non-profit:
1. **Manusia (*People*):** Karakteristik pengurus sepuh, ketergantungan figur tunggal, dan keterbatasan peran generasi muda.
2. **Proses (*Process*):** Ketiadaan SOP pencadangan, alur koordinasi *ad-hoc*, redundansi input data, dan ketiadaan evaluasi pasca-acara.
3. **Teknologi (*Technology*):** Ketergantungan penyimpanan tunggal (*single point of failure*), ketiadaan repositori *cloud*, dan pemanfaatan gawai yang sebatas percakapan instan.
4. **Kebijakan & Tata Kelola (*Policy & Governance*):** Ketiadaan regulasi aset informasi internal, nihilnya SOP audit kas, serta SK formal yang belum memuat rincian akuntabilitas data.
5. **Data & Informasi (*Data*):** Terjadinya isolasi data (*data silo*), tradisi *hard drive legacy*, asimetri informasi kas, dan ketidakterhubungan dengan data kemiskinan pemerintah (DTKS).
6. **Lingkungan Organisasi (*Environment*):** Budaya kesungkanan (*ewuh pakewuh*), asumsi komunal bahwa administrasi bersifat sekunder selama ibadah ritual berjalan, serta jurang komunikasi lintas generasi.

Dalam penyusunan diagram ini, kelompok secara ketat menegakkan prinsip anti-slop akademis: **tidak mencantumkan ketiadaan aplikasi atau teknologi (seperti: "karena belum ada aplikasi web") sebagai penyebab**. Ketiadaan perangkat lunak adalah kondisi ketiadaan solusi teknis, bukan akar penyebab masalah tata kelola.

### 3.3 Penelusuran Mendalam Menuju Akar Masalah Menggunakan Teknik *5-Why* (Ohno, 1988)
Untuk membawa analisis melampaui gejala permukaan fisik (*surface symptoms*) menuju penyebab sistemik yang paling mendasar, kelompok menerapkan teknik penelusuran kausalitas bertingkat *5-Why*.

Diskusi kritis kelompok menguji premis awal: *Apakah rusaknya PC merupakan akar masalah teknis murni?* Berlandaskan filosofi perkuliahan MSI (Dr. Ratna Wardani), sistem informasi terdiri atas **5 unsur minimal: Input, Proses, Output, Manpower, dan Teknologi**. Kerusakan PC hanyalah peristiwa pemicu (*trigger event*) pada tataran teknologi fisik. Menggunakan analogi dosen: *"Sebuah motor balap (aplikasi/teknologi) tidak bernilai fungsional jika tidak ada jalan raya (infrastruktur), aturan lalu lintas (SOP), dan lisensi pengemudi (otoritas SK Takmir)"*. 

Apabila organisasi takmir memiliki "aturan lalu lintas" tata kelola data yang baik (SOP pencadangan berkala) dan "lisensi" akuntabilitas yang jelas, maka kerusakan satu unit komputer tidak akan memusnahkan riwayat organisasi karena data telah terduplikasi secara aman di repositori cadangan. Dengan demikian, rantai kausalitas *5-Why* dilanjutkan secara logis hingga menyentuh akar terdalam: **Ketiadaan kerangka tata kelola informasi (*information governance framework*) dan regulasi internal organisasi**.

### 3.4 Penilaian Kelayakan Menggunakan Matriks Prioritas (Dampak vs Upaya)
Seluruh masalah dan opsi intervensi yang teridentifikasi diposisikan ke dalam Matriks Prioritas Masalah (Dampak vs Upaya) dalam format kuadran (Mermaid *quadrantChart*). Evaluasi penempatan kuadran mempertimbangkan:
- Keterbatasan horizon waktu praktikum (1 semester akademik).
- Kesiapan dan kapasitas adopsi pengurus takmir senior (*Task-Technology Fit*).
- Tingkat urgensi mitigasi risiko kehilangan data serta pemenuhan akuntabilitas publik di hadapan jamaah, KUA, dan BAZNAS.

### 3.5 Perumusan Pernyataan Masalah Prioritas (*Final Problem Statement*)
Tahap akhir dari praktikum ini adalah menyintesis seluruh hasil analisis menjadi satu kalimat pernyataan masalah prioritas yang padat, presisi, dan berorientasi pada kondisi penyebab sistemik organisasi. Pernyataan ini menjadi fondasi utama penentuan batasan proyek (*Project Scope*) dan *Work Breakdown Structure* (WBS) pada Pertemuan 4.

---

## 4. Hasil/Artefak Praktikum

### 4.1 Lembar Kerja: Dokumen Analisis Masalah Organisasi
Berikut adalah lembar kerja dokumen analisis masalah pengelolaan sistem informasi Masjid Besar Baitul Hikmah yang disusun berdasarkan bukti empiris multi-sumber:

| Bagian | Isian | Sumber/Metode Perolehan Data *(Minimal 2 Sumber Berbeda yang Saling Menguatkan)* |
|:---|:---|:---|
| **Daftar Masalah Teridentifikasi (Min. 3 Masalah)** | Beberapa aktivitas operasional dan peribadatan pada Masjid Besar Baitul Hikmah yang kami temukan sudah berjalan dengan lancar, seperti ketersediaan perangkat komputer meja di kantor sekretariat, penerimaan infaq via kotak Jumat dan QRIS resmi yang aktif, penyelenggaraan shalat Jumat dan qurban tahunan yang padat jamaah, serta kepengurusan takmir yang memiliki legalitas resmi SK No. 05/MBBH/VII/2026. Namun demikian, telaah mendalam membuktikan bahwa kendala-kendala di lapangan bukanlah masalah teknis yang berdiri sendiri, melainkan merupakan **akibat langsung dari masalah tata kelola organisasi (*organizational governance failure*)**.<br><br>Berdasarkan triangulasi data empiris, kelompok mengidentifikasi 4 masalah tata kelola organisasi (3 terverifikasi dan 1 hipotesis kerja) yang dirumuskan secara sistematis melalui pola **Masalah Organisasi $\rightarrow$ Akibat Lapangan**:<br><br>**1. Ketiadaan Regulasi & SOP Pengelolaan Data Resmi dari Tingkat Pembina (Kemenag/KUA) hingga Takmir, serta Ketiadaan Kontrol Pendataan oleh Sekretariat (Masalah Organisasi — Terverifikasi):**<br>• *Akar Masalah Organisasi:* Secara struktural makro-meso, belum ada transmisi pedoman tata kelola data resmi dari instansi pembina (Kemenag melalui KUA Gondokusuman) kepada takmir masjid. Di tingkat internal takmir, belum ada SOP tertulis yang mewajibkan prosedur pencadangan berkala (*backup policy*), tidak ada pembagian otoritas data digital, serta sekretariat tidak menjalankan kontrol pengamanan arsip. Urusan dokumentasi dipandang sebatas tugas klerikal sukarela tanpa mitigasi risiko kelangsungan organisasi (*business continuity*).<br>• *Akibat Lapangan yang Ditimbulkan:* Pengelolaan arsip surat, inventaris, kepanitiaan, dan database layanan tersimpan terisolasi di satu unit PC sekretariat dan komputer pribadi sekretaris (*single point of failure*). Ketika PC kantor rusak pada Februari 2026, **70% riwayat data organisasi hilang permanen** (hanya 30% yang diselamatkan), melumpuhkan memori institusional masjid.<br><br>**2. Ketiadaan SOP Pengendalian Internal (*Internal Control*) dan Pemisahan Wewenang (*Segregation of Duties*) dalam Tata Kelola Kas Keuangan (Masalah Organisasi — Terverifikasi):**<br>• *Akar Masalah Organisasi:* Organisasi takmir tidak memiliki regulasi internal atau SOP baku yang mengatur mekanisme pembukuan, jadwal pelaporan berkala, supervisi silang kasir/bendahara, maupun audit kas internal oleh Ketua Takmir/Dewan Pengawas. SK Takmir No. 05/MBBH/VII/2026 mencantumkan Bendahara I dan II namun tanpa rincian pemisahan fungsi pencatatan, pemegang fisik kas, dan otorisator pengeluaran.<br>• *Akibat Lapangan yang Ditimbulkan:* Pengelolaan kas masjid tersentralisasi secara tertutup pada buku fisik pribadi Bendahara I tanpa supervisi (*single-person custody*). Akibat ketiadaan kewajiban dan format pelaporan baku, **laporan keuangan tertulis tidak pernah dibuat dan tidak pernah dipublikasikan kepada jamaah selama ±3 tahun berturut-turut**, menciptakan asimetri informasi yang sistemis, menghambat verifikasi kas, dan berisiko menurunkan kepercayaan publik muzaki.<br><br>**3. Ketiadaan Standarisasi Alur Prosedur Kerja (SOP), Kejelasan Peran (*Role Clarity*), dan Alih Pengetahuan (*Knowledge Transfer*) Antar-Generasi (Masalah Organisasi — Terverifikasi):**<br>• *Akar Masalah Organisasi:* Organisasi takmir tidak membukukan proses bisnis layanan ke dalam SOP tertulis, melainkan membiarkan alur kerja berjalan berdasarkan kebiasaan personal tak tertulis (*tacit knowledge*) figur senior. Struktur organisasi formal di SK tidak disertai deskripsi kerja fungsional (*job description*) dan kejelasan akuntabilitas peran.<br>• *Akibat Lapangan yang Ditimbulkan:*<br>a. *Inefisiensi Layanan:* Alur pendaftaran jamaah (mudhohi Qurban dan kegiatan takjil) terjadi secara berulang dan redundan (*triple-entry*: pesan WhatsApp $\rightarrow$ buku tulis fisik $\rightarrow$ diketik ulang ke komputer lokal), memperlambat rekapitulasi dan meningkatkan risiko salah input.<br>b. *Ketergantungan Ekstrem & Kelelahan Pengurus:* Terjadi penumpukan beban operasional pada satu figur (*key-person dependency*) di mana Sekretaris I merangkap 6+ fungsi sekaligus, sementara puluhan nama pengurus lain di SK pasif di lapangan (*sleeping committee*).<br>c. *Disorientasi Regenerasi:* Ketika panitia muda (REMAS) atau pengurus baru hendak membantu, mereka mengalami disorientasi karena tidak ada buku panduan kerja, sehingga koordinasi berjalan *ad-hoc* dan harus selalu konfirmasi silang secara lisan ke figur A, B, C, D.<br><br>**4. Ketiadaan Kerangka Kebijakan Integrasi Data Antar-Lembaga (*Inter-Organizational Data Governance*) antara Takmir dengan Lembaga Kewilayahan (Kelurahan Klitren & KUA Gondokusuman) (Masalah Organisasi — Hipotesis Kerja Parsial):**<br>• *Akar Masalah Organisasi:* Belum tersusunnya payung kemitraan data formal (*data sharing protocol*) antara takmir masjid dengan institusi pembina kewilayahan. Tidak ada kanal pertukaran data resmi untuk verifikasi kemiskinan maupun format rekapitulasi terstandar untuk pelaporan kegiatan keagamaan.<br>• *Akibat Lapangan yang Ditimbulkan:*<br>a. *Penyaluran ZIS Berbasis Amatan Subjektif:* Penyaluran zakat fitrah dan daging qurban berjalan tanpa verifikasi silang data kemiskinan pemerintah (DTKS Kelurahan Klitren), melainkan hanya mengandalkan amatan kasat mata dan usulan lisan RT/RW, berpotensi memicu ketidaktepatan sasaran distribusi (*inclusion/exclusion error*). *(Catatan: data ini masih berstatus hipotesis parsial yang perlu konfirmasi lanjutan).*<br>b. *Pelaporan PHBI Insidental:* Pelaporan penyelenggaraan Idul Fitri dan Idul Adha kepada KUA Gondokusuman (sebagaimana diamanatkan PMA No. 34 Tahun 2016) berjalan secara manual, insidental, dan tidak terdokumentasi dalam sistem informasi terpadu. | **Verifikasi Bukti Riil per Butir Masalah:**<br><br>• **Bukti Masalah 1 (Terverifikasi):**<br>1. *Wawancara Primer:* Keterangan Bpk. Mardiyanto (Sekretaris I) mengonfirmasi ketiadaan SOP pencadangan dari Kemenag/KUA maupun internal takmir; arsip tersimpan di PC kantor dan rumah; saat PC rusak Feb 2026, 70% data hilang total permanen.<br>2. *Observasi Partisipatif:* Catatan kader REMAS (Fajar Ahnaf): kepanitiaan PHBI selalu bingung mencari dokumen lama di harddisk sisa; data TPA Mas Jefri tersimpan di spreadsheet lokal tanpa cadangan cloud.<br><br>• **Bukti Masalah 2 (Terverifikasi):**<br>1. *Wawancara Primer:* Keterangan Sekretaris I — ketiadaan SOP pembukuan dan pengawasan menyebabkan laporan kas tertulis dari Bendahara I tidak pernah dibuat selama ±3 tahun.<br>2. *Observasi & Komparasi:* Tidak ada papan transparansi saldo kas; Masjid Mujur Al-Amin berhasil menerapkan SOP *dual custody* dan papan transparansi swadaya sebagai percontohan.<br><br>• **Bukti Masalah 3 (Terverifikasi):**<br>1. *Wawancara Primer:* Alur triple-entry qurban dikonfirmasi Bpk. Mardiyanto (WA $\rightarrow$ buku $\rightarrow$ PC); rangkap tugas Sekretaris I diakui langsung akibat ketiadaan distribusi tugas formal.<br>2. *Dokumen & Observasi:* SK Takmir No. 05/MBBH/VII/2026 memuat banyak nama pasif (*sleeping committee*); observasi REMAS mengonfirmasi disorientasi operasional karena ketiadaan SOP tertulis.<br><br>• **Bukti Masalah 4 (Hipotesis Parsial — Data Belum Final):**<br>1. *Wawancara Parsial:* Keterangan Sekretaris I tentang penentuan mustahik via lisan RT/RW (belum divalidasi ke Koordinator ZIS & Kelurahan).<br>2. *Regulasi:* PMA No. 34 Tahun 2016 mewajibkan pelaporan PHBI ke KUA, namun belum ada format rekapitulasi terstandar antara KUA dan takmir. |
| **Masalah Terpilih untuk Analisis Akar** | Beberapa upaya perbaikan fisik pasca-kerusakan PC Februari 2026 telah diusahakan pengurus (membawa harddisk ke tempat servis lokal). Namun, persoalan tata kelola paling mendasar yang kami pilih untuk analisis akar masalah adalah: **Ketiadaan Regulasi Internal dan Standar Operasional Prosedur (SOP) Pengelolaan serta Pencadangan Data Resmi dari Tingkat Pembina (Kemenag/KUA) hingga Takmir Masjid (Masalah Organisasi), yang berakibat fatal pada musnahnya 70% riwayat data administrasi dan arsip organisasi saat insiden kerusakan PC sekretariat pada Februari 2026.** | • **Sumber 1:** Transkrip verbatim wawancara Bpk. Mardiyanto (Sekretaris I): *"Komputer sekretariat rusak Februari 2026 kemarin mas, cuma bisa diselamatkan sekitar 30 persen, sisanya hilang total."*<br>• **Sumber 2:** Observasi partisipatif REMAS: Rapat panitia PHBI selalu mengandalkan file sisa di folder lokal harddisk lama dengan update seadanya.<br>• **Sumber 3:** Komparasi tata kelola data cloud tersentralisasi pada benchmark Masjid Nurul Ashri Deresan (*masjidnurulashri.com*). |
| **Hasil Analisis Akar Masalah (Fishbone & 5-Why)** | Penyelidikan kausalitas bertingkat membuktikan bahwa kerusakan fisik PC hanyalah pemicu teknis (*trigger event*). Akar masalah terdalam yang melumpuhkan organisasi adalah **kegagalan tata kelola informasi (*information governance failure*)**: ketiadaan kerangka regulasi dan tidak berjalannya SOP resmi dari tingkat pembina (Kemenag/KUA) menuju Takmir terkait protokol pencadangan berkala (*backup policy*), ketiadaan regulasi pemisahan wewenang (*segregation of duties*) dan audit kas keuangan, ketiadaan deskripsi kerja fungsional di SK Takmir, serta ketiadaan dokumentasi prosedur alur kerja untuk alih pengetahuan antar-generasi (*knowledge transfer*). | • **Sumber 1:** Analisis SK Takmir No. 05/MBBH/VII/2026 (memuat struktur nama namun nihil rincian akuntabilitas data, hak akses, dan tata kelola aset digital).<br>• **Sumber 2:** Wawancara Bpk. Mardiyanto (dokumen fisik tersimpan tersebar di rumah pribadi tanpa standardisasi penyimpanan kantor sekretariat).<br>• **Sumber 3:** Landasan Teori Akademis: Nonaka & Takeuchi (1995) tentang *Knowledge Conversion Failure* (jebakan pengetahuan *tacit*) dan Romney & Steinbart (2018) tentang *Internal Control Deficit*. |
| **Matriks Prioritas (Dampak vs Upaya)** | Memilah solusi berdasarkan kemampuan memotong akar masalah organisasi secara realistis: **Prioritas Utama (Quick Wins)** difokuskan pada (1) Penyusunan Regulasi Internal, SOP, & Protokol Pencadangan Data Hibrid Berbasis Cloud, dan (2) Penerapan SOP Lembar Pencatatan Tunggal (*Single-Entry*) serta Papan Transparansi Terbuka. Sedangkan perancangan SIM terpadu skala penuh ditempatkan sebagai **Proyek Strategis** jangka menengah. | • **Sumber 1:** Telaah kapasitas operasional takmir dan REMAS (wawancara Sekretaris I & observasi panitia muda).<br>• **Sumber 2:** Matriks Dampak vs Upaya (*quadrantChart*) berdasarkan prinsip *Task-Technology Fit* (Goodhue & Thompson, 1995). |
| **Pernyataan Masalah Prioritas Akhir** | Rumusan masalah prioritas akhir yang ditetapkan berorientasi penuh pada akar penyebab tata kelola organisasi: **"Ketiadaan kerangka regulasi internal dan Standar Operasional Prosedur (SOP) resmi dari tingkat pembina (Kemenag/KUA) hingga internal takmir Masjid Besar Baitul Hikmah menyebabkan data administrasi, arsip kepanitiaan, dan catatan keuangan tersimpan secara terisolasi (*data silo*) pada perangkat lokal tanpa prosedur pencadangan berkala (*backup policy*) yang berakibat pada musnahnya 70% riwayat data saat insiden kerusakan PC sekretariat; ketiadaan SOP pembukuan dan pengawasan memicu berhentinya publikasi laporan keuangan tertulis selama ±3 tahun; serta ketiadaan dokumentasi alur kerja memicu inefisiensi *triple-entry* dan disorientasi regenerasi kepengurusan."** | • **Sumber 1:** Sintesis kausalitas 5-Why yang menghubungkan dampak musnahnya riwayat data Feb 2026 dengan ketiadaan kebijakan organisasi.<br>• **Sumber 2:** Keselarasan strategis dengan Standar Manajemen Idarah Masjid Besar Kemenag RI (Keputusan Dirjen Bimas Islam No. DJ.II/802 Tahun 2014). |

---

### 4.2 Diagram Tulang Ikan (*Fishbone Diagram*)
Untuk membuktikan secara ilmiah bahwa insiden hilangnya data dan ketiadaan laporan keuangan merupakan **akibat langsung dari masalah tata kelola organisasi (*organizational governance failure*)**, kelompok memetakan akar-akar penyebab tata kelola ke dalam 6 dimensi utama diagram sebab-akibat (*Fishbone Diagram*). Analisis ini menelusuri bagaimana ketiadaan regulasi, ketiadaan SOP resmi dari instansi pembina (Kemenag/KUA) hingga takmir, serta tidak berjalannya kontrol pendataan internal bermuara pada berbagai akibat fatal di kepala ikan.

> **Catatan Metodologis:** Beberapa faktor pada dimensi **Manusia** (khususnya P5 dan P6) berstatus **hipotesis kerja** berbasis data parsial dari komunikasi informal dengan Jefri Nur Ihsan (Ketua II/Direktur TPA) via WhatsApp 14 September 2026. Bisyarah pengurus takmir sebesar **Rp 150.000/bulan** dikonfirmasi ada, namun tetap tidak mendorong partisipasi aktif — konsisten dengan **Teori Dua Faktor Herzberg (1959)** di mana bisyarah berfungsi sebagai *hygiene factor* (mencegah ketidakpuasan) bukan *motivator* (mendorong kontribusi). Fenomena "saling lempar" dikonfirmasi Mas Jefri juga terjadi di RT/RW sekitar, mengindikasikan erosi modal sosial komunal yang lebih luas (**Social Capital Theory, Putnam 2000**). Kedua faktor ini perlu divalidasi melalui wawancara mendalam lanjutan.

```mermaid
flowchart LR
    subgraph P["1. MANUSIA PEOPLE"]
        P1["Dominasi pengurus sepuh nyaman sistem manual Word-Excel"]
        P2["Ketergantungan ekstrem pada figur Sekretaris I merangkap 6 fungsi"]
        P3["Fenomena sleeping committee nama di SK pasif di lapangan"]
        P4["Kader 17 pemuda REMAS belum dilibatkan dalam tata kelola data"]
        P5["HIPOTESA: Bisyarah Rp150rb per bulan hanya hygiene factor bukan motivator aktif"]
        P6["HIPOTESA: Erosi budaya partisipasi komunal -- saling lempar juga terjadi di RT RW"]
        P_CAT["Simpul Faktor Manusia"]
        P1 --> P_CAT
        P2 --> P_CAT
        P3 --> P_CAT
        P4 --> P_CAT
        P5 --> P_CAT
        P6 --> P_CAT
    end

    subgraph PR["2. PROSES PROCESS"]
        PR1["Takmir dan sekretariat tidak menjalankan SOP pencadangan data berkala"]
        PR2["Alur koordinasi ad-hoc tanpa panduan tertulis tanya A B C D"]
        PR3["Redundansi pendaftaran triple-entry WA buku fisik PC"]
        PR4["Ketiadaan SOP pelaporan terstandar ke KUA sesuai PMA 34 2016"]
        PR_CAT["Simpul Faktor Proses"]
        PR1 --> PR_CAT
        PR2 --> PR_CAT
        PR3 --> PR_CAT
        PR4 --> PR_CAT
    end

    subgraph T["3. TEKNOLOGI TECHNOLOGY"]
        T1["Penyimpanan bertumpu pada 1 PC kantor single point of failure"]
        T2["Ketiadaan repositori cloud terpusat Google Workspace"]
        T3["Pemanfaatan gawai terbatas pesan instan WA personal"]
        T4["Presensi TPA tersimpan di spreadsheet lokal PC pribadi Mas Jefri"]
        T_CAT["Simpul Faktor Teknologi"]
        T1 --> T_CAT
        T2 --> T_CAT
        T3 --> T_CAT
        T4 --> T_CAT
    end

    subgraph POL["4. KEBIJAKAN POLICY DAN GOVERNANCE"]
        POL1["Ketiadaan transmisi pedoman SOP tata kelola informasi dari Kemenag KUA"]
        POL2["Nihil regulasi internal takmir tentang klasifikasi dan retensi aset data"]
        POL3["Ketiadaan SOP audit internal dan pemisahan fungsi keuangan kas"]
        POL4["SK Takmir No 05-MBBH-VII-2026 tidak merinci otoritas dan akuntabilitas data"]
        POL_CAT["Simpul Faktor Kebijakan"]
        POL1 --> POL_CAT
        POL2 --> POL_CAT
        POL3 --> POL_CAT
        POL4 --> POL_CAT
    end

    subgraph D["5. DATA DAN INFORMASI"]
        D1["Data silo terisolasi di harddisk PC dan rumah pribadi"]
        D2["Daur ulang berkas lama turun-temurun hard drive legacy"]
        D3["Asimetri informasi kas fisik tidak dipublikasikan 3 tahun"]
        D4["Data mustahik terisolir dari DTKS Kelurahan Klitren"]
        D_CAT["Simpul Faktor Data"]
        D1 --> D_CAT
        D2 --> D_CAT
        D3 --> D_CAT
        D4 --> D_CAT
    end

    subgraph E["6. LINGKUNGAN ENVIRONMENT"]
        E1["Budaya ewuh pakewuh sungkan menuntut transparansi tertulis"]
        E2["Asumsi komunal selama fisik berjalan administrasi nomor dua"]
        E3["Jurang komunikasi lintas generasi sepuh vs kader muda"]
        E4["Paradoks status Masjid Besar tapi operasional RT"]
        E_CAT["Simpul Faktor Lingkungan"]
        E1 --> E_CAT
        E2 --> E_CAT
        E3 --> E_CAT
        E4 --> E_CAT
    end

    AKIBAT["AKIBAT: Hilangnya 70% Data Administrasi & Arsip Organisasi (Feb 2026) Serta Kerapuhan Regenerasi Akibat Ketiadaan SOP & Tata Kelola Data"]

    P_CAT --> AKIBAT
    PR_CAT --> AKIBAT
    T_CAT --> AKIBAT
    POL_CAT --> AKIBAT
    D_CAT --> AKIBAT
    E_CAT --> AKIBAT
```

---

### 4.3 Analisis Bertingkat *5-Why* (Ohno, 1988)
Untuk membuktikan bahwa akar masalah berada pada ranah tata kelola (*governance*) organisasi dan bukan sekadar insiden teknis komputer, kelompok menyusun rangkaian kausalitas *5-Why* yang menghubungkan gejala/akibat permukaan dengan akar penyebab institusional:

```
[GEJALA UTAMA / AKIBAT LAPANGAN]
70% riwayat data administrasi, surat keluar-masuk, inventaris, dan database layanan 
Masjid Besar Baitul Hikmah hilang permanen saat komputer sekretariat rusak pada Februari 2026.
    │
    ▼
[MENGAPA 1? — Mengapa data hilang permanen saat PC mengalami kerusakan teknis?]
Karena seluruh dokumen digital hanya tersimpan di dalam satu unit hard drive komputer 
lokal di meja sekretariat tanpa ada salinan di tempat penyimpanan lain (Single Point of Failure).
    │
    ▼
[MENGAPA 2? — Mengapa data hanya tersimpan di satu hard drive lokal tanpa salinan cadangan?]
Karena staf sekretariat dan pengurus tidak pernah melakukan pencadangan data (backup) 
secara berkala, baik ke media penyimpanan eksternal maupun ke repositori cloud.
    │
    ▼
[MENGAPA 3? — Mengapa tidak pernah dilakukan pencadangan data secara berkala?]
Karena organisasi takmir tidak memiliki maupun menjalankan Standard Operating Procedure (SOP) 
terkait pencadangan dan pemeliharaan data organisasi secara berkala.
    │
    ▼
[MENGAPA 4? — Mengapa takmir tidak menyusun dan menjalankan SOP pengelolaan data?]
Karena tidak adanya instruksi atau transmisi pedoman tata kelola data resmi dari instansi pembina 
(Kemenag melalui KUA Gondokusuman) kepada takmir, serta pengurus memandang pengelolaan berkas 
sebatas tugas klerikal individual sukarela tanpa perlindungan risiko keberlangsungan organisasi (business continuity).
    │
    ▼
[MENGAPA 5? — AKAR MASALAH ORGANISASI / ROOT CAUSE]
Mengapa tata kelola data tidak menjadi prioritas institusional dari tingkat pembina hingga takmir?
Ketiadaan kerangka tata kelola informasi (information governance framework) dan SOP resmi 
berjenjang dari tingkat pembina (Kemenag/KUA) hingga internal takmir masjid, serta tidak 
dijalankannya kontrol organisasi terkait prosedur pencadangan, hak kepemilikan aset informasi, 
pemisahan tugas, dan dokumentasi alur kerja untuk alih pengetahuan antar-generasi.
```

---

### 4.4 Matriks Prioritas Masalah (Dampak vs Upaya)
Mempertimbangkan keterbatasan waktu 1 semester, kapasitas pengurus sepuh, dan keterlibatan kader muda REMAS, seluruh inisiatif pemecahan masalah diposisikan ke dalam matriks kuadran berikut:

```mermaid
quadrantChart
    title Matriks Prioritas Masalah dan Solusi
    x-axis Low Effort --> High Effort
    y-axis Low Impact --> High Impact
    quadrant-1 Proyek Strategis
    quadrant-2 Quick Wins Prioritas
    quadrant-3 Kerjakan Jika Sempat
    quadrant-4 Hindari atau Tunda
    Protokol Backup Cloud dan SOP: [0.28, 0.88]
    Standardisasi Form Input Tunggal: [0.22, 0.78]
    Pengembangan SIM BaitulHikmah: [0.76, 0.86]
    Restrukturisasi Dual Tier REMAS: [0.72, 0.74]
    Digitalisasi Arsip Kertas Lama: [0.36, 0.30]
    Template Broadcast WA Jamaah: [0.18, 0.36]
    Server Fisik Mandiri On Premise: [0.84, 0.18]
```

#### Rasionalisasi Penempatan Kuadran:
1. **Kuadran 2: Prioritas Utama / Quick Wins (Dampak Tinggi, Upaya Rendah):**
   - **Penerapan Protokol Pencadangan Data Hibrid Berbasis Cloud:** Memanfaatkan platform penyimpanan cloud non-profit terpusat (misalnya Google Workspace for Nonprofits) yang disinkronisasikan otomatis dengan folder kerja sekretariat dan TPA. Upaya teknisnya rendah (tidak butuh koding rumit), namun langsung meniadakan risiko hilangnya riwayat organisasi secara permanen.
   - **Standardisasi Formulir Pendaftaran Tunggal (*Single Entry*) & Papan Transparansi Terbuka:** Mengadopsi praktik baik Masjid Mujur Al-Amin, yaitu menghentikan rantai *triple-entry* dengan menyediakan satu lembar/formulir terstandarisasi untuk pendaftaran qurban dan takjil, serta mempublikasikan saldo kas Jumat di papan fisik masjid.
2. **Kuadran 1: Proyek Strategis (Dampak Tinggi, Upaya Tinggi):**
   - **Rancang Bangun SIM-BaitulHikmah Terpadu:** Sistem informasi manajemen berbasis web yang mengintegrasikan master data jamaah ber-NIK, modul pencatatan buku kas digital transparan, modul TPA, serta kroscek kriteria mustahik zakat dengan DTKS Kelurahan. Inisiatif ini berdampak jangka panjang sangat besar namun membutuhkan waktu perancangan dan pengujian multi-fase.
   - **Restrukturisasi Operasional Generasi Ganda (*Dual-Tier Operating Model*):** Menata ulang pembagian peran: para sesepuh berfokus pada pengawasan, nilai syariah, dan otorisasi kebijakan, sedangkan kader pemuda REMAS diberi mandat operasional digital.
3. **Kuadran 3: Kerjakan Jika Sempat (Dampak Rendah, Upaya Rendah):**
   - Digitalisasi tumpukan surat kertas lama yang sudah lewat masa retensi 5 tahun dan pembuatan template pesan siaran WhatsApp broadcast untuk jadwal pengajian.
4. **Kuadran 4: Hindari / Tunda (Dampak Rendah, Upaya Tinggi):**
   - **Pengadaan Server Fisik Mandiri (*On-Premise Server*) di Kantor Sekretariat:** Pembelian perangkat server fisik berbiaya mahal membutuhkan perawatan teknis khusus, konsumsi listrik konstan, serta risiko fisik yang sama (kebanjiran, korsleting listrik, atau kerusakan komponen) tanpa memberikan keunggulan dibanding arsitektur cloud.

---

### 4.5 Pernyataan Masalah Prioritas Akhir (*Final Problem Statement*)
Berdasarkan sintesis triangulasi data, diagram sebab-akibat, dan matriks prioritas, kelompok menetapkan rumusan masalah prioritas akhir yang merangkum hubungan kausalitas **Masalah Organisasi $\rightarrow$ Akibat Lapangan** sebagai berikut:

> **"Ketiadaan kerangka regulasi internal dan Standar Operasional Prosedur (SOP) resmi dari tingkat pembina (Kemenag/KUA) hingga internal takmir Masjid Besar Baitul Hikmah menyebabkan data administrasi, arsip kepanitiaan, dan catatan keuangan tersimpan secara terisolasi (*data silo*) pada perangkat lokal tanpa prosedur pencadangan berkala (*backup policy*) yang berakibat pada musnahnya 70% riwayat data saat insiden kerusakan PC sekretariat; ketiadaan SOP pembukuan dan pengawasan memicu berhentinya publikasi laporan keuangan tertulis selama ±3 tahun; serta ketiadaan dokumentasi alur kerja memicu inefisiensi *triple-entry* dan disorientasi regenerasi kepengurusan."**

---

## 5. Kendala dan Solusi

### 5.1 Kendala 1: Memisahkan Gejala Permukaan (*Symptoms*) dari Akar Masalah (*Root Causes*)
* **Deskripsi Kendala:** Pada diskusi awal, anggota kelompok cenderung menganggap "PC sekretariat rusak pada Februari 2026" dan "anak-anak muda tidak aktif di takmir" sebagai akar masalah utama. Muncul kecenderungan mahasiswa untuk langsung menyimpulkan bahwa solusinya adalah "membeli laptop baru" atau "membuatkan website canggih".
* **Solusi Metodologis:** Kelompok menerapkan teknik *5-Why* secara disiplin dengan uji kausalitas kontra-faktual: *"Apakah jika PC diganti dengan perangkat baru yang canggih, risiko kehilangan riwayat data di masa depan otomatis hilang?"* Jawabannya adalah tidak, karena tanpa kebijakan pencadangan berkala (*backup policy*) dan SOP tertulis, perangkat baru pun akan mengalami nasib yang sama saat terjadi lonjakan listrik atau kerusakan teknis. Dengan metode ini, fokus analisis berhasil dialihkan dari kegagalan instrumen fisik ke kelemahan tata kelola (*governance*) organisasi.

### 5.2 Kendala 2: Jebakan Solusi-Sentris (*Technology Solution Bias*) & Analogi Ekosistem MSI
* **Deskripsi Kendala:** Terdapat bias keilmuan di kalangan mahasiswa teknik informatika untuk langsung merancang arsitektur perangkat lunak yang rumit (misalnya usulan modul payment gateway otomatis atau presensi biometrik santri TPA) sebelum membedah proses bisnis nyata di lapangan.
* **Solusi Metodologis:** Berlandaskan pedoman akademis dosen pengampu (Dr. Ratna Wardani) mengenai analogi ekosistem kendaraan: *"Aplikasi hanyalah motor balap; ia tidak memiliki nilai fungsional jika tidak ada jalan raya (infrastruktur), aturan lalu lintas (SOP), dan SIM (lisensi/otoritas formal SK)"*. Mengacu pada teori *Task-Technology Fit* (Goodhue & Thompson, 1995), kelompok menyaring setiap ide fitur dengan memeriksa profil pengguna akhir: jika marbot sepuh dan sekretaris senior terbiasa dengan catatan fisik dan Excel dasar, memaksakan sistem yang rumit tanpa menyiapkan SOP dan pendampingan justru akan memicu penolakan sistem (*system rejection*). Solusinya adalah mendahulukan pembenahan tata kelola dan SOP kerja.

### 5.3 Kendala 3: Asimetri Informasi dan Batasan Akses Data Keuangan Bendahara
* **Deskripsi Kendala:** Hingga penyusunan laporan ini, kelompok belum dapat mengakses dan mengaudit buku kas fisik Bendahara I (Hj. Retno Kusumastuti) secara langsung karena kesibukan personal beliau. Kelompok hanya memegang keterangan sekunder dari Sekretaris I serta amatan jamaah bahwa tidak pernah ada laporan keuangan tertulis selama ~3 tahun terakhir.
* **Solusi Metodologis:** Menjunjung tinggi integritas akademik anti-halusinasi, kelompok tidak mengarang angka nominal saldo atau arus kas bulanan. Status pembukuan kas secara eksplisit dicatat sebagai *"temuan lapangan yang terkonfirmasi dari keterangan sekretaris dan amatan publik jamaah, namun belum terverifikasi oleh buku kas bendahara langsung"*. Kelompok kemudian melakukan triangulasi dengan data observasi kepanitiaan Idul Adha/Ramadhan dan mengomparasikannya dengan praktik tata kelola kas terpisah dan *dual custody* di Masjid Mujur Al-Amin (Karangnongko).

### 5.4 Kendala 4: Fragmentasi dan Isolasi Data Antar-Lembaga (*Data Silo* DTKS Kelurahan & Supervisi KUA)
* **Deskripsi Kendala:** Penentuan mustahik zakat dan pembagian daging qurban selama ini terisolir dari basis data kemiskinan pemerintah, sementara koordinasi pelaporan PHBI ke KUA Gondokusuman (PMA No. 34 Tahun 2016) masih berjalan manual dan insidental pasca-acara.
* **Solusi Metodologis:** Kelompok tidak berasumsi bahwa sistem masjid dapat langsung menembus API database dinas sosial/kelurahan secara otomatis. Sebagai langkah realistis (*feasible*), kelompok merekomendasikan standardisasi formulir pendataan mustahik internal berbasis Nomor Induk Kependudukan (NIK) dan verifikasi faktual berjenjang bersama pengurus RT/RW, yang secara berkala disandingkan (*data matching*) dengan data DTKS Kelurahan, serta merancang format rekapitulasi data qurban yang sesuai dengan standar formulir supervisi KUA.

---

## 6. Refleksi Pembelajaran

### 6.1 Beda Mendasar Gejala vs Akar Masalah dalam Perspektif MSI
Praktikum Pertemuan 3 ini memberikan transformasi paradigma yang sangat fundamental bagi kelompok: membedakan rekayasa perangkat lunak teknis dari disiplin **Manajemen Sistem Informasi (MSI)**. Dalam MSI, sebuah sistem tidak pernah beroperasi di ruang hampa teknologi. Insiden musnahnya 70% data arsip di Masjid Besar Baitul Hikmah membuktikan secara nyata bahwa **teknologi hanyalah instrumen penyimpan data, sedangkan penentu utama integritas dan keberlanjutan informasi adalah manusia (*manpower*), alur kerja (*process*), dan kebijakan organisasi (*governance*)**.

Mengidentifikasi gejala permukaan (seperti PC rusak, kepanitiaan bingung, atau ketiadaan laporan kas) sangat mudah diamati secara kasat mata. Namun, menemukan akar masalah menuntut keberanian membongkar kelemahan kultural dan struktural organisasi:
- Budaya kesungkanan (*ewuh pakewuh*) yang membuat pengurus sungkan menuntut akuntabilitas laporan tertulis kepada sesepuh.
- Jebakan pengetahuan tak tertulis (*tacit knowledge trap* — Nonaka & Takeuchi, 1995), di mana seluruh tata cara pengelolaan masjid hanya tersimpan di ingatan personal figur senior tanpa pernah dibukukan menjadi Standar Operasional Prosedur (SOP) tertulis.
- Anggapan komunal bahwa *"yang terpenting shalat jamaah dan pengajian berjalan lancar, urusan administrasi dan data nomor dua"*, yang mengabaikan fakta bahwa tanpa tata kelola data yang baik, keberlangsungan organisasi berada di ujung tanduk saat terjadi suksesi kepemimpinan.

### 6.2 Integrasi dengan Kerangka 7 Aspek Pengelolaan Sistem Informasi
Temuan dan analisis pada Modul 3 ini terhubung erat dengan kerangka 7 Aspek MSI yang diajarkan dalam perkuliahan:
1. **Aspek 1 — Keselarasan Strategis:** Tata kelola informasi harus selaras dengan misi masjid sebagai institusi sosial-keagamaan yang dipercaya umat. Ketidakteraturan data dan ketiadaan laporan tertulis berisiko mengikis *trust* jamaah dan muzaki, yang secara langsung melemahkan keberlangsungan misi peribadatan dan sosial masjid.
2. **Aspek 2 — Tata Kelola dan Kualitas Informasi *(Fokus Utama Modul 3):*** Kerapuhan informasi di Baitul Hikmah bukan karena ketiadaan teknologi, melainkan ketiadaan regulasi internal: siapa pemilik data (*data owner*), siapa yang berwenang memperbarui, kapan jadwal wajib pencadangan, dan di mana data disimpan. Ketiadaan *single source of truth* memicu data tercecer di rumah pribadi dan folder lokal tanpa perlindungan.
3. **Aspek 3 — Dukungan Pengambilan Keputusan:** Informasi yang tidak akurat melumpuhkan tiga level keputusan organisasi:
   - *Level Operasional:* Marbot dan panitia kesulitan mencatat pendaftaran qurban karena alur *triple-entry* yang lambat dan rawan salah rekap.
   - *Level Manajerial:* Sekretaris dan ketua takmir tidak dapat mengevaluasi tren infaq dan pertumbuhan santri TPA karena data tersimpan di berkas fisik pribadi yang tidak teragregasi.
   - *Level Strategis:* Rapat takmir 3 bulanan tidak dapat merumuskan program pemberdayaan jamaah jangka panjang karena ketiadaan *evidence-based decision making* yang valid.
4. **Aspek 4 — Kebutuhan Informasi Stakeholder:** Setiap pemangku kepentingan memiliki kebutuhan informasi yang berbeda namun saling terkait. Muzaki dan shahibul qurban membutuhkan bukti transparansi penyaluran dana. Wali santri membutuhkan laporan perkembangan anak berkala. BAZNAS membutuhkan laporan penghimpunan ZIS terstandar. KUA membutuhkan rekapitulasi kegiatan PHBI. Saat ini, **tidak ada satu pun kebutuhan informasi tersebut yang terpenuhi secara sistematis** karena tidak ada sistem pengolahan data yang terintegrasi dan terdistribusi sesuai kebutuhan masing-masing stakeholder.
5. **Aspek 5 — Nilai Informasi:** Insiden hilangnya 70% data pada Februari 2026 membuktikan secara konkret bahwa **informasi memiliki nilai ekonomis dan sosial yang nyata** — bukan sekadar tumpukan berkas. Riwayat kepanitiaan yang hilang berarti panitia berikutnya harus memulai dari nol tanpa *lessons learned*. Data mustahik yang hilang berarti proses seleksi zakat dan qurban berulang menjadi tidak konsisten. Nilai informasi yang tidak diakui inilah yang memungkinkan budaya *"data sebagai urusan klerikal pribadi"* terus bertahan.
6. **Aspek 6 — Integrasi Proses Bisnis:** Kegagalan integrasi antar-unit (Masjid, TPA, Panitia PHBI, KUA, Kelurahan DTKS, dan BAZNAS) menciptakan fenomena *Silo Informasi*. Sesuai arahan dosen, ini adalah bentuk *Governance Failure* yang menghambat peran masjid di tengah ekosistem masyarakat.
7. **Aspek 7 — Adopsi dan Perilaku Organisasi:** Menjawab tantangan jurang generasi, kelompok merumuskan solusi sosio-teknis berupa **Dual-Tier Operating Model (Model Operasional Generasi Ganda)**:
   - *Tier 1 (Strategic & Oversight):* Para sesepuh takmir tetap memegang otoritas moral, fatwa syariah, dan persetujuan kebijakan strategis (*steering committee*).
   - *Tier 2 (Operational & Execution):* Generasi muda REMAS diberdayakan secara resmi melalui SK Takmir sebagai operator data digital, pengelola repositori cloud, perancang publikasi visual, dan penyusun lembar transparansi kas mingguan.

Melalui pendekatan ini, digitalisasi tidak menyingkirkan para sesepuh, melainkan memuliakan peran mereka sekaligus membuka jalan regenerasi kepengurusan yang berkelanjutan sesuai siklus peningkatan mutu berkelanjutan (*Continuous Quality Improvement* / PDCA).

---

## 7. Kesimpulan

1. Berdasarkan triangulasi data multi-sumber (wawancara mendalam Sekretaris I Bpk. Mardiyanto, observasi partisipatif kader REMAS Fajar Ahnaf, data parsial TPA Mas Jefri, dan studi komparasi lapangan), kelompok berhasil mengidentifikasi **4 masalah tata kelola organisasi (3 terverifikasi dan 1 hipotesis kerja)** yang dirumuskan secara terstruktur melalui pola **Masalah Organisasi $\rightarrow$ Akibat Lapangan**.
2. Penelusuran kausalitas mendalam dengan *Fishbone Diagram* (6 dimensi) dan teknik *5-Why* membuktikan bahwa insiden musnahnya 70% data arsip pada Februari 2026 berakar pada **ketiadaan kerangka tata kelola informasi (*information governance framework*) dan ketiadaan/tidak berjalannya SOP resmi berjenjang dari tingkat pembina (Kemenag/KUA) hingga internal takmir**, bukan semata kerusakan fisik perangkat komputer.
3. Ketiadaan dokumentasi Standar Operasional Prosedur (SOP) tertulis, ketergantungan ekstrem pada satu figur senior, dan kebiasaan daur-ulang berkas kepanitiaan lama secara turun-temurun (*hard drive legacy*) terbukti menjadi faktor struktural yang memicu disorientasi kepengurusan baru dan menghambat regenerasi pemuda.
4. Evaluasi Matriks Prioritas Masalah (Dampak vs Upaya) menetapkan bahwa intervensi jangka pendek yang paling mendesak (*Quick Wins*) adalah: penyusunan regulasi internal, SOP, dan protokol pencadangan data hibrid berbasis cloud serta penyederhanaan alur pendaftaran layanan menjadi satu pintu (*single-entry*). Sedangkan rancang bangun sistem informasi terpadu (SIM-BaitulHikmah) diposisikan sebagai proyek strategis jangka menengah.
5. Rumusan masalah prioritas akhir yang telah ditetapkan berfokus penuh pada kondisi penyebab tata kelola organisasi, memberikan landasan yang kokoh bagi kelompok untuk melangkah ke **Pertemuan 4: Penyusunan Batasan Proyek (*Project Scope*) dan *Work Breakdown Structure* (WBS)**.

---

## Referensi

- Davis, F. D. (1989). Perceived usefulness, perceived ease of use, and user acceptance of information technology. *MIS Quarterly*, 13(3), 319–340.
- Goodhue, D. L., & Thompson, R. L. (1995). Task-technology fit and individual performance. *MIS Quarterly*, 19(2), 213–236.
- Herzberg, F. (1959). *The motivation to work*. New York: John Wiley & Sons.
- Ishikawa, K. (1976). *Guide to quality control*. Asian Productivity Organization.
- Kementerian Agama Republik Indonesia. (2014). *Keputusan Direktur Jenderal Bimbingan Masyarakat Islam Nomor DJ.II/802 Tahun 2014 tentang Standar Pembinaan Manajemen Masjid*. Jakarta: Kemenag RI.
- Kementerian Agama Republik Indonesia. (2016). *Peraturan Menteri Agama (PMA) Nomor 34 Tahun 2016 tentang Organisasi dan Tata Kerja Kantor Urusan Agama*. Jakarta: Kemenag RI.
- Laudon, K. C., & Laudon, J. P. (2014). *Management information systems: Managing the digital firm* (13th ed.). Boston: Pearson Education.
- Nonaka, I., & Takeuchi, H. (1995). *The knowledge-creating company: How Japanese companies create the dynamics of innovation*. Oxford: Oxford University Press.
- Ohno, T. (1988). *Toyota production system: Beyond large-scale production*. New York: Productivity Press.
- Putnam, R. D. (2000). *Bowling alone: The collapse and revival of American community*. New York: Simon & Schuster.
- Romney, M. B., & Steinbart, P. J. (2018). *Accounting information systems* (14th ed.). New York: Pearson.

