# VALIDASI AKADEMIK & RASIONALISASI MANAJEMEN SISTEM INFORMASI (MSI)
## Kasus: Sistem Informasi Manajemen Masjid Besar Baitul Hikmah (SIM-BaitulHikmah)
*Disusun untuk: Kelompok 1 — Kelas F1*  
*Anggota: Muhammad Riski (24050530029), Fajar Ahnaf Mahardika (24050530030), Muhadzdzib Terry Al-Fauzan (24050530052)*  
*Mata Kuliah: Praktik Manajemen Sistem Informasi (PTF60234) — Dosen: Dr. Ratna Wardani, S.Si., M.T.*

---

## 1. Perumusan Masalah & Dekonstruksi Pertanyaan Penelitian

### Pertanyaan Inti
> **"Mengapa Masjid Besar Baitul Hikmah membutuhkan intervensi *Manajemen Sistem Informasi (MSI)*, dan mengapa kegagalan tata kelola di lapangan TIDAK BISA diselesaikan hanya dengan sekadar komputerisasi/pembuatan aplikasi?"**

### Dekonstruksi Kritik Dosen (Dr. Ratna Wardani, S.Si., M.T.)
> *"Masalah pencatatan manual itu tidak selalu solusinya computerize. Bisa jadi masalah SDM yang sudah tua itu malah bingung terhadap digitalisasi walaupun tujuannya mempermudah, sehingga malah menimbulkan masalah tambahan."*

Pernyataan tersebut sangat valid secara teoretis dalam literatur MSI: **mengganti buku kertas dengan aplikasi komputer pada organisasi nirlaba yang didominasi SDM lanjut usia justru sering memicu *system abandonment* (penolakan sistem) dan beban kognitif baru.** 

Oleh karena itu, argumen kelayakan proyek ini harus membuktikan bahwa masalah Masjid Baitul Hikmah adalah **masalah manajemen, arsitektur informasi, dan tata kelola (*governance*)**, di mana teknologi hanyalah salah satu komponen pendukung (*enabler*), bukan tujuan akhir.

```
                  ┌────────────────────────────────────────┐
                  │          TANTANGAN UTAMA MSI           │
                  │ (Socio-Technical Systems Perspective)   │
                  └──────────────────┬─────────────────────┘
                                     │
         ┌───────────────────────────┼───────────────────────────┐
         ▼                           ▼                           ▼
┌──────────────────┐       ┌──────────────────┐       ┌──────────────────┐
│ 1. TATA KELOLA & │       │ 2. ASIMETRI &    │       │ 3. PERILAKU SDM  │
│    PENGENDALIAN  │       │    KUALITAS DATA │       │    & ADOPSI      │
│  (Governance)    │       │   (Information)  │       │ (People/Process) │
└──────────────────┘       └──────────────────┘       └──────────────────┘
```

---

## 2. Klasifikasi Klaim, Fakta Lapangan, dan Analisis Bukti

Standar klasifikasi bukti:
* `[VERIFIED]`: Fakta konkret yang telah diverifikasi dari observasi/data lapangan atau literatur baku.
* `[INFERENCE]`: Kesimpulan logis yang ditarik dari hubungan antar-fakta.
* `[ASSUMPTION]`: Premis kerja yang masuk akal namun masih memerlukan konfirmasi empiris.
* `[UNVERIFIED]`: Pernyataan yang belum memiliki data dukung faktual dan wajib divalidasi di lapangan.

### Tabel Pemetaan Masalah Lapangan ke Dimensi MSI

| No | Fenomena Lapangan | Klasifikasi Status | Dimensi Masalah MSI (Bukan Masalah Coding) | Analisis Tata Kelola Sistem |
|:---|:---|:---:|:---|:---|
| 1 | Uang alokasi TPA pernah terpakai untuk kepentingan pribadi karena ketiadaan pencatatan terpisah. | `[VERIFIED]` (Pernah terjadi) | **Ketiadaan *Internal Control* & *Segregation of Duties*** | Ini murni masalah **tata kelola wewenang dan pembukuan entitas terpisah (*fund accounting*)**, bukan masalah aplikasi. Tanpa aturan pemisahan kas dan audit berkala, aplikasi kasir secanggih apa pun tetap bisa dimanipulasi atau diabaikan. |
| 2 | Slot donasi takjil Ramadhan kosong di tanggal tertentu, namun jamaah mengira sudah penuh; status hanya diketahui seksi konsumsi. | `[VERIFIED]` (Fakta operasional) | **Asimetri Informasi Publik (*Information Asymmetry*)** | Terjadi *bottleneck* aliran informasi. Keputusan jamaah terhambat karena data tersimpan secara tertutup (*siloed*). Masalah ini diselesaikan dengan **protokol transparansi informasi publik**, yang medianya bisa berupa papan tulis fisik terstruktur maupun media digital. |
| 3 | Ustadz/khatib batal hadir mendadak, santri/jamaah telantar di masjid, tidak ada ustadz badal (pengganti). | `[VERIFIED]` (Fakta operasional) | **Ketiadaan *Contingency Protocol* & SLA Komunikasi** | Kegagalan **proses bisnis mitigasi risiko (*business continuity/contingency planning*)**. Sistem informasi bertugas menetapkan aturan: konfirmasi H-1 jam; jika nihil respon, otomatis mengaktifkan penunjukan ustadz badal lokal (misal marbot/takmir piket). |
| 4 | Kartu santri TPA sering hilang $\rightarrow$ santri dan pengajar lupa capaian jilid Iqra/Al-Quran. | `[VERIFIED]` (Fakta operasional) | **Ketiadaan *Single Source of Truth* (SSOT)** | Menggantungkan data master pada kartu fisik di tangan santri melanggar prinsip *data redundancy & persistence*. Master data progres membaca wajib berada di buku induk registri masjid, sedangkan kartu santri hanyalah salinan (*copy*). |
| 5 | Panitia pemotong hewan qurban tidak terdata $\rightarrow$ terlewat mendapatkan hak jatah daging qurban tambahan. | `[VERIFIED]` (Fakta musiman) | **Kelemahan *Operational Tracking* & Insentif Kerja** | Masalah alur verifikasi lapangan: tidak ada standarisasi pendaftaran dan validasi kehadiran tenaga kerja musiman di hari pelaksanaan. |
| 6 | Hewan qurban tiba di lokasi tanpa ada petugas yang siap menerima; identitas shahibul qurban hanya nama tanpa alamat/kontak. | `[VERIFIED]` (Fakta musiman) | **Kualitas Data Buruk (*Garbage In, Garbage Out*) & Ketiadaan Logistik Terjadwal** | Ketiadaan *data capture standard* saat pendaftaran qurban dibuka (panitia hanya mencatat nama, tanpa nomor WhatsApp aktif dan estimasi jam kirim hewan). |
| 7 | Struktur kepengurusan takmir bersifat informal; peneliti dan warga kesulitan mengetahui pemilik wewenang (*decision maker*). | `[VERIFIED]` (Fakta organisasi) | **Ketiadaan Struktur Tata Kelola (*Organizational Governance*)** | Sistem informasi formal tidak akan pernah berjalan di atas struktur organisasi yang tidak jelas hak akses dan tanggung jawabnya (*RACI matrix tidak terdefinisi*). |
| 8 | TK Baitul Hikmah memiliki sistem informasi sendiri yang terpisah dari masjid. | `[ASSUMPTION]` (Perlu diverifikasi) | **Kebutuhan *Inter-organizational System* vs Otonomi Unit** | Perlu dipastikan apakah TK beroperasi sebagai yayasan mandiri yang hanya meminjam aset masjid, atau subsistem resmi di bawah Takmir. |
| 9 | Marbot sepuh pasti menolak dan gagal menggunakan aplikasi komputer/web. | `[INFERENCE]` (Berdasarkan demografi & kritik dosen) | **Kesenjangan Kapasitas (*Task-Technology Mismatch*)** | Jika antarmuka dan prosedur menuntut literasi digital tinggi, marbot akan mengalami disonansi dan kembali ke cara lisan. Solusi MSI: antarmuka minimalis/hibrid atau delegasi peran bertingkat. |

---

## 3. Landasan Teoretis Akademik: Mengapa Ini Bidang MSI, Bukan RPL?

Berikut adalah 5 teori *peer-reviewed* dalam disiplin *Management Information Systems* yang menjadi fondasi analisis:

```
                           ┌────────────────────────────────────────┐
                           │      TEORI SISTEM SOSIO-TEKNIS         │
                           │      (Laudon & Laudon, 2014)           │
                           └──────────────────┬─────────────────────┘
                                              │
         ┌────────────────────────────────────┼────────────────────────────────────┐
         ▼                                    ▼                                    ▼
┌─────────────────────────┐      ┌─────────────────────────┐      ┌─────────────────────────┐
│ TASK-TECHNOLOGY FIT     │      │ PENGENDALIAN INTERNAL   │      │ TECHNOLOGY ACCEPTANCE   │
│ (Goodhue & Thompson,    │      │ (Romney & Steinbart,    │      │ (Davis, 1989;           │
│  1995)                  │      │  2018; COSO Framework)  │      │  Markus, 1983)          │
└─────────────────────────┘      └─────────────────────────┘      └─────────────────────────┘
```

### Tabel Rujukan Literatur Akademis

| Teori / Model | Sumber Primer (Author, Year, DOI) | Klaim Utama Teori | Penerapan Konkret pada Kasus Masjid Baitul Hikmah | Level Bukti |
|:---|:---|:---|:---|:---:|
| **Socio-Technical Systems Theory** | Laudon, K. C., & Laudon, J. P. (2014). *Management Information Systems: Managing the Digital Firm* (13th ed.). Pearson. | Kinerja sistem informasi optimal hanya tercapai jika terjadi penyesuaian bersama (*mutual adjustment*) antara sistem sosial (orang, budaya, struktur organisasi) dan sistem teknis (perangkat, software). | `[VERIFIED]` | Menolak otomasi buta. Jika takmir adalah pensiunan/sepuh, sistem teknis tidak boleh memaksakan database SQL rumit ke tangan mereka, melainkan menata prosedur laporannya terlebih dahulu. |
| **Task-Technology Fit (TTF)** | Goodhue, D. L., & Thompson, R. L. (1995). *Task-technology fit and individual performance*. MIS Quarterly, 19(2), 213–236. DOI: [10.2307/249689](https://doi.org/10.2307/249689) | Teknologi informasi hanya berdampak positif pada kinerja jika kapabilitas teknologi tersebut cocok (*fit*) dengan karakteristik tugas yang harus diselesaikan pengguna. | `[VERIFIED]` | Mencatat uang infaq mingguan tidak membutuhkan sistem ERP berbasis web kompleks. Tugas marbot adalah *data capturing* instan (misal form kertas tanda terima atau bot pesan ringkas), sedangkan tugas manajerial bendahara adalah *reconciliation*. Mismatch teknologi = kegagalan sistem. |
| **Internal Control & Segregation of Duties** | Romney, M. B., & Steinbart, P. J. (2018). *Accounting Information Systems* (14th ed.). Pearson. | Pemisahan fungsi otorisasi transaksi, pencatatan transaksi, dan penyimpanan aset fisik (*custody of assets*) adalah syarat mutlak pencegahan fraud dan penyelewengan dana. | `[VERIFIED]` | **Kasus Dana TPA Dipakai Pribadi:** Terjadi karena satu orang memegang fungsi pencatatan sekaligus penyimpanan uang kas TPA tanpa mekanisme otorisasi takmir. MSI menyelesaikan ini dengan *prosedur pemisahan akun (dual custody)* dan rekonsiliasi bulanan. |
| **Technology Acceptance Model (TAM)** | Davis, F. D. (1989). *Perceived usefulness, perceived ease of use, and user acceptance of information technology*. MIS Quarterly, 13(3), 319–340. DOI: [10.2307/249008](https://doi.org/10.2307/249008) | Niat menggunakan teknologi ditentukan oleh *Perceived Usefulness* (kegunaan yang dirasakan) dan *Perceived Ease of Use* (kemudahan penggunaan). Jika persepsi kerumitan tinggi, adopsi ditolak. | `[VERIFIED]` | Pengurus sepuh akan menolak sistem jika merasa "lebih cepat pakai kertas dan pulpen". Sistem harus memberikan manfaat instan tanpa membuat mereka pusing mengoperasikannya. |
| **Power, Politics, and IT Resistance** | Markus, M. L. (1983). *Power, politics, and MIS implementation*. Communications of the ACM, 26(6), 430–444. DOI: [10.1145/358141.358148](https://doi.org/10.1145/358141.358148) | Resistensi terhadap sistem informasi bukan semata-mata masalah teknis antarmuka, melainkan respons terhadap perubahan relasi kuasa, pembagian wewenang, dan transparansi yang menekan kebiasaan lama. | `[VERIFIED]` | Takmir yang terbiasa mengelola dana secara informal sering kali enggan mencatat secara transparan karena khawatir diaudit atau dipersalahkan. Penerapan MSI memerlukan pendekatan manajerial *change management*. |

---

## 4. Analisis Kontra-Argumen (Menjawab Kritik Dosen)

### Kontra-Argumen 1: "Kenapa tidak cukup dibuatkan SOP manual di atas kertas saja? Kenapa harus ada kata 'Sistem Informasi'?"
* **Bantahan / Analisis Kritis (`[INFERENCE]`):**  
  SOP manual di atas kertas memiliki batasan fisik mendasar:
  1. *Kecepatan Akses & Asimetri Informasi:* Kertas jadwal takjil Ramadhan yang ditempel di dinding masjid hanya bisa dibaca oleh orang yang datang ke masjid. Akibatnya, calon donatur dari rumah tidak tahu jadwal mana yang kosong, menyebabkan *undersupply* takjil di hari-hari tertentu.
  2. *Skalabilitas Musiman (Peak Load Idul Adha):* Mengelola 3 sapi dan 10 kambing untuk 3 RW (ratusan KK) dalam tempo 6 jam pemotongan tidak mungkin ditangani hanya dengan mengandalkan memori manusia dan lembaran kertas yang rawan basah, kotor, dan robek di lapangan jagal.
  3. *Integritas & Retensi Data:* Kartu TPA kertas terbukti hilang berulang kali, merugikan santri.
* **Kesimpulan MSI:** Sistem informasi **tidak harus** berupa aplikasi mobile/web mandiri yang rumit. Sistem Informasi adalah *mekanisme pengumpulan, pemrosesan, penyimpanan, dan diseminasi data*. Sistem tersebut bisa berwujud **SOP + Form Terstandar + Saluran Penyebaran Terjadwal (misal WhatsApp Broadcast otomatis / Layar Monitor Informasi Publik)**.

### Kontra-Argumen 2: "Marbot dan takmir sudah tua, digitalisasi hanya akan menambah beban mereka."
* **Solusi Arsitektur Manajemen: Dual-Tier Operating Model (`[INFERENCE]`):**  
  Data lapangan menunjukkan ada **17 pemuda REMAS** yang melek gawai namun selama ini hanya dimanfaatkan setahun dua kali saat Idul Fitri dan Idul Adha.
  * **Tingkat 1 (Front-line / Lapangan - Marbot Sepuh):** Diberi instrumen fisik yang sangat sederhana (lembar logbook terstandarisasi dengan format ketat, bukan kertas kosong bebas).
  * **Tingkat 2 (Data Entry & Rekonsiliasi - Pemuda REMAS / Sekretaris):** Bertindak sebagai operator konversi data dari logbook fisik ke basis data terpadu masjid secara berkala (mingguan).
  * **Tingkat 3 (Pengambilan Keputusan - Ketua Takmir & Bendahara):** Menerima laporan ringkas (*executive summary*) untuk evaluasi kas dan alokasi qurban/zakat.
  * *Hasil:* Marbot tidak dipaksa menjadi operator komputer, namun integritas data masjid tetap terjamin. Ini adalah inti dari **Manajemen Sistem Informasi**!

---

## 5. Rencana Wawancara Validasi Lapangan (Field Inquiry Protocol)

Pertanyaan terstruktur berikut dirancang khusus dari sudut pandang **tata kelola informasi**, bukan sudut pandang pengembang software:

```
                          ┌───────────────────────────┐
                          │   PROTOKOL WAWANCARA      │
                          │   TATA KELOLA INFORMASI   │
                          └─────────────┬─────────────┘
                                        │
        ┌───────────────────────────────┼───────────────────────────────┐
        ▼                               ▼                               ▼
┌──────────────────┐            ┌──────────────────┐            ┌──────────────────┐
│   BIDANG TPA     │            │  KEUANGAN & ZIS  │            │  KEPANITIAAN     │
│   & PENGAJARAN   │            │   (KONTROL KAS)  │            │  QURBAN/RAMADHAN │
└──────────────────┘            └──────────────────┘            └──────────────────┘
```

### A. Tata Kelola TPA & Pendidikan
1. **Pemisahan Entitas Keuangan:**  
   *"Bagaimana persisnya alur penarikan SPP/iuran santri saat ini? Siapa yang memegang kas fisik, dan apakah ada buku rekening khusus TPA yang terpisah dari rekening kas umum masjid?"*
2. **Master Data Santri & Pengajar:**  
   *"Jika kartu fisik santri hilang, dari buku catatan mana ustadz mengetahui santri tersebut terakhir sampai jilid berapa? Siapa yang bertanggung jawab memegang buku induk tersebut?"*
3. **Prosedur Kontinjensi Ustadz Badal:**  
   *"Jika ustadz utama berhalangan hadir pada pukul 15.30 (jadwal TPA 16.00), apa aturan resmi masjid untuk mencari pengganti? Apakah santri pernah dipulangkan karena tidak ada pengajar?"*

### B. Pengendalian Internal Keuangan & Infaq
1. **Otorisasi Pengeluaran:**  
   *"Berapa batas nominal pengeluaran kas yang boleh diputuskan sendiri oleh Bendahara tanpa persetujuan Ketua Takmir? Bagaimana bukti pengeluarannya diarsipkan?"*
2. **Rekonsiliasi Silang:**  
   *"Apakah pencatatan buku kas oleh Bendahara pernah dicocokkan secara formal dengan catatan Sekretaris? Seberapa sering terjadi perbedaan angka saldo?"*

### C. Kepanitiaan Musiman (Idul Fitri, Takjil, & Idul Adha)
1. **Transparansi Takjil:**  
   *"Bagaimana cara seksi konsumsi memberi tahu jamaah RW 1, 2, dan 3 mengenai tanggal-tanggal takjil yang masih kosong? Mengapa data tersebut tidak dipasang di papan pengumuman masjid?"*
2. **Registrasi Shahibul Qurban:**  
   *"Saat seseorang mendaftar qurban, data apa saja yang wajib dicatat panitia? Mengapa nomor telepon dan alamat sering tidak lengkap tercatat saat hewan tiba?"*
3. **Verifikasi Tenaga Pemotong:**  
   *"Bagaimana panitia memastikan bahwa warga yang ikut memotong daging qurban benar-benar menerima jatah hak dagingnya tanpa ada yang terlewat atau dobel ambil?"*

### D. Struktur Otoritas & Integrasi TK
1. **Hubungan Formal TK Baitul Hikmah:**  
   *"Apakah TK Baitul Hikmah secara struktural berada di bawah Takmir Masjid (melaporkan keuangan dan program kerja ke Takmir), ataukah TK berdiri di bawah yayasan terpisah yang mandiri?"*
2. **Rantai Komando Takmir:**  
   *"Jika mahasiswa/peneliti ingin mengusulkan pembaruan tata kelola pendataan, siapa pejabat takmir yang memiliki wewenang mutlak untuk menyetujui SOP baru tersebut?"*

---

## 6. Pernyataan Ketidakpastian & Batasan (Limitations & Uncertainties)

* `[UNCERTAINTY 1]`: Derajat integrasi TK Baitul Hikmah dengan masjid masih belum dapat ditentukan sampai wawancara dengan pengelola TK dilakukan.
* `[UNCERTAINTY 2]`: Tingkat resistensi takmir sepuh belum terukur secara kuantitatif; hipotesis keengganan menggunakan aplikasi masih didasarkan pada asumsi umum demografi dan masukan dosen.
* `[LIMITATION]`: Proyek ini dibatasi pada perancangan **tata kelola dan arsitektur informasi** (SOP, alur data, peran RACI, dan pemodelan sistem informasi) serta tidak mewajibkan implementasi perangkat lunak siap pakai jika analisis sosio-teknis merekomendasikan solusi manual/hibrid.

---

## 7. Rangkuman Narasi untuk Dosen (Argumen Pembelaan di Depan Bu Ratna)

Gunakan kerangka berpikir berikut saat berdiskusi atau mempresentasikan topik ini kepada Bu Ratna:

> *"Ibu Ratna, kami sangat sepakat dengan arahan Ibu bahwa masalah pencatatan manual tidak serta-merta harus diselesaikan dengan aplikasi komputer, apalagi pengurus masjid mayoritas berusia sepuh sehingga komputerisasi langsung berisiko besar gagal (*task-technology mismatch*).*
> 
> *Justru karena pertimbangan itulah kami memposisikan proyek ini murni sebagai **Manajemen Sistem Informasi (MSI)**, bukan Rekayasa Perangkat Lunak (RPL):*
> 1. *Fokus utama kami adalah **merestrukturisasi tata kelola informasi**, bukan membuat coding aplikasi.*
> 2. *Contoh kasus nyata di lapangan: insiden dana TPA terpakai pribadi bukan terjadi karena tidak ada aplikasi, melainkan karena tidak adanya tata kelola pengendalian internal (*segregation of duties*) antara pemegang kas dan pencatat kas.*
> 3. *Kasus takjil kosong dan kekacauan qurban terjadi karena kegagalan arsitektur aliran data (*information asymmetry* dan buruknya *data capture*).*
> 4. *Rekomendasi MSI kami adalah merancang **Sistem Hibrid**: menata SOP formulir fisik terstandarisasi untuk marbot sepuh di lapangan, dan memberdayakan 17 pemuda REMAS sebagai unit pengelola data berkala, sehingga tidak ada beban kognitif berlebih bagi pengurus senior namun akuntabilitas masjid tetap terjamin."*
