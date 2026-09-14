# AGENTS.md — Panduan Agent: Proyek MSI Kelompok 1 F1

> File ini dibaca otomatis oleh agent setiap kali bekerja di folder ini.
> Tujuannya: memastikan setiap laporan praktikum dibuat secara konsisten,
> akurat sesuai standar Bu Ratna, dan berbasis konteks proyek yang lengkap.

---

## 🔒 ATURAN WAJIB — BACA SELURUH KONTEKS SEBELUM MULAI

Sebelum mengerjakan laporan atau tugas apapun di project ini, agent WAJIB membaca file-file berikut terlebih dahulu:

### File Konteks Inti (AKTIF — Wajib Dibaca)

> ⚠️ File-file lama (`data draft.md`, `migrasi 1/2/3.md`) sudah **diarsipkan** ke `_arsip_lama/` dan TIDAK boleh direferensikan. Gunakan hanya file di bawah ini.

| File | Isi | Status |
|---|---|---|
| `notes kelas.md` | Panduan akademis Bu Ratna — filosofi MSI, 7 aspek, RACI, Power-Interest Grid, 5 unsur sistem | ✅ Aktif |
| `hasil wawancara masjid.md` | **Sumber Data Primer Utama.** Transkrip verbatim + Tabel Temuan Empiris (8 klaster) + Spektrum Masalah Mermaid + Hierarki Regulasi Top-Down | ✅ Aktif |
| `hasil wawancara masjid pembanding dan analisis komparasi.md` | Transkrip harfiah wawancara Masjid Mujur Al-Amin (pembanding empiris lapangan) + analisis komparasi 3 level | ✅ Aktif |
| `validasi akademik dan rasionalisasi msi.md` | Justifikasi akademik MSI vs aplikasi, Task-Technology Fit, Internal Control, TAM, IT Resistance | ✅ Aktif |
| `komparasi benchmark masjid nurul ashri deresan dan tata kelola eksternal.md` | Analisis komparatif desk research Nurul Ashri (website publik) vs Baitul Hikmah — **Perlu diperbarui setelah wawancara Selasa** | 🟡 Aktif (partial) |
| `panduan wawancara lapangan msi.md` | Instrumen wawancara lapangan universal (makro-meso-mikro, TPA, penurunan jamaah/santri) | ✅ Aktif |
| `instrumen wawancara direktur tpa baitul hikmah.md` | Instrumen wawancara khusus Mas Jefri (Direktur TPA) — **DATA PARSIAL SUDAH DIPEROLEH** (checklist + WA 7 Sep 2026), wawancara mendalam belum dilakukan | 🟡 Parsial |
| `instrumen wawancara masjid nurul ashri deresan.md` | Instrumen untuk benchmark Masjid Nurul Ashri Deresan — **Dijadwalkan Selasa** | 🟡 Menunggu |
| `panduan presentasi dan pemahaman msi.md` | Narasi "bahasa bayi" konsep MSI (motor balap vs aturan jalan) | ✅ Aktif |
| `tata kelola informasi bottom-up.md` | Alur tata kelola informasi dari level bawah ke atas | ✅ Aktif |

### ⚠️ FAKTA LAPANGAN YANG SUDAH TERVALIDASI (Anti-Halusinasi)
Berikut adalah fakta *hard* dari transkrip wawancara Bpk. Mardianto (Sekretaris, bukan Ketua Takmir):
- Jabatan narasumber wawancara: **Mardiyanto — Sekretaris I** sejak 2004 (bukan Ketua Takmir)
- **Ketua I:** Nanang Sahid Wahyudi, S.Pd. | **Ketua II:** Jefri Nur Ihsan, SE.I. *(sekaligus merangkap Direktur TPA Baitul Hikmah)*
- **Sekretaris I:** Mardiyanto | **Sekretaris II:** Hafiz Alfarizi
- **Bendahara I:** Hj. Retno Kusumastuti | **Bendahara II:** Dwi Sari Kurnia Putri
- SK resmi: **No. 05/MBBH/VII/2026**, ditetapkan 16 Juli 2026, ditandatangani Ketua I Nanang Sahid Wahyudi, S.Pd.
- **TPA di SK** (Satrio, Fahim, Fajri, Marbot) = **pengajar TPA**, bukan direktur. Direktur TPA = Jefri Nur Ihsan (Ketua II).
- Marbot = merangkap pengajar TPA sekaligus (sesuai keterangan Bpk. Mardianto)
- Insiden kritis: PC rusak **Februari 2026**, data ter-recovery hanya **30%** (70% hilang permanen)
- Laporan keuangan: Bendahara I tidak membuat laporan tertulis selama **~3 tahun berturut-turut** *(pengamatan Sekretaris I, belum dikonfirmasi Bendahara langsung)*
- Penyimpanan dokumen: di **komputer lokal + fisik di rumah pribadi Sekretaris** (bukan Google Drive)
- Rapat takmir: setiap **3 bulan sekali**
- Khatib Jumat: **terjadwal 1 tahun penuh**, ada ustadz badal jika batal
- Pendaftaran Qurban: via **WhatsApp → buku tulis → komputer** (triple entry)
- Mustahik ZIS: ditentukan **tanpa DTKS** kelurahan, berdasar pengamatan warga
- QRIS & rekening bank: **sudah ada** atas nama masjid
- **Data nominal infaq bulanan & volume qurban: BELUM TERVERIFIKASI** (perkiraan user, bukan dari wawancara) — jangan gunakan angka Rp 2-3 jt atau "3 sapi 10 kambing" sebagai fakta
- **[TPA — Data Parsial dari Jefri Nur Ihsan (Ketua II/Direktur TPA), 7 Sep 2026 via WA]**
  - Absensi santri: dicatat via **Excel/Spreadsheet** (bukan manual murni)
  - Laporan ke orang tua: **hanya jika diperlukan** (tidak rutin)
  - IZOP (Izin Operasional TPA): **sudah terbit** dari Kemenag (pernah beroperasi tanpa izin)
  - Bottleneck IZOP: konfirmasi Kemenag harus **japri pribadi staf** (tidak ada jalur formal)
  - BADKO TPA: menjadi **penghubung TPA ↔ Kemenag** untuk proses IZOP
  - Data internal TPA (santri, ustadz, kegiatan): Jefri Nur Ihsan klaim *"sudah ada semua"*
  - **Belum diperoleh:** jumlah santri aktif vs. dulu, kas SPP terpisah atau tidak, buku induk master santri

### File Laporan yang Sudah Ada (Referensi Konsistensi)
| File | Keterangan |
|---|---|
| `Laporan Modul 1 - Kelompok 1 F1.md` | Laporan Pertemuan 1 (sudah final) |
| `Laporan Modul 2 - Kelompok 1 F1.md` | Laporan Pertemuan 2 (sudah final) |
| `Laporan Modul 3 - Kelompok 1 F1.md` | Laporan Pertemuan 3 (sudah final — Analisis Masalah & Prioritas Solusi) |

### Template Resmi (Struktur Wajib)
| File | Keterangan |
|---|---|
| `Modul 1 template.pdf` | Template resmi Pertemuan 1 dari Bu Ratna |
| `Modul 2 template.pdf` | Template resmi Pertemuan 2 dari Bu Ratna |
| `Modul 3 template.md` | Template Pertemuan 3 (hasil transkripsi PDF Modul 3) — **Target Segera** |

---

## 👤 KONTEKS PROYEK

### Identitas Kelompok
- **Kelompok**: Kelompok 1 — Kelas F1
- **Anggota**:
  1. Muhammad Riski — 24050530029
  2. Fajar Ahnaf Mahardika — 24050530030
  3. Muhadzdzib Terry Al-Fauzan — 24050530052
- **Mata Kuliah**: Praktik Manajemen Sistem Informasi / PTF60234
- **Dosen**: Dr. Ratna Wardani, S.Si., M.T.
- **Tahun Akademik**: 2026 / Semester 5
- **Model Pembelajaran**: Project-Based Learning (artefak kumulatif per pertemuan)

### Objek Studi & Spektrum Komparasi Tiga Tingkat (Tri-Level Spectrum)
- **1. Target Studi Kasus Utama**: **Masjid Besar Baitul Hikmah** (Klitren, Gondokusuman, Yogyakarta) — Masjid Besar tingkat kecamatan/kelurahan, semi-urban, non-profit murni, isu data silo & penurunan jamaah/santri.
- **2. Pembanding Empiris Lapangan (Empirical Baseline)**: **Masjid Mujur Al-Amin** (Karangnongko) — Masjid dusun/lingkungan berbasis partisipasi swadaya RT 1–5, percontohan tata kelola transparan swakelola (Papan Takjil Terbuka & Otonomi TPA).
- **3. Benchmark Mapan Terdekat**: **Masjid Nurul Ashri Deresan** (Yogyakarta) — Masjid Jami' lingkungan yang lebih kecil dari Baitul Hikmah secara tipologi, namun digitalisasi tata kelolanya jauh lebih matang: website Next.js aktif, 13 campaign donasi online real-time, 2.450+ jamaah aktif, program Qurban/Education/Peduli/Kebencanaan terstruktur. **Website: masjidnurulashri.com | IG: @masjidnurulashri**
- *(Catatan historis: Masjid Jogokariyan Yogyakarta sebelumnya digunakan sebagai benchmark nasional level Socio-Enterprise. Diganti ke Nurul Ashri karena lebih relevan secara tipologi lokal dan jarak geografis — wawancara lapangan Selasa)*
- **Unit Afiliasi Target**: TK Baitul Hikmah, TPA Baitul Hikmah, Kemitraan KUA Kecamatan.
- **Fokus Dua Proses Bisnis Inti**:
  1. **Tata Kelola Pendataan Jamaah & Penyaluran ZIS** — verifikasi NIK + sinkronisasi DTKS Kelurahan.
  2. **Tata Kelola Layanan Pendidikan (TPA) & Kemakmuran Ibadah** — monitoring santri + pelaporan ke BADKO.

---

## ❓ PROTOKOL BERTANYA SEBELUM EKSEKUSI

**WAJIB**: Setiap kali diminta membuat laporan baru, agent HARUS bertanya dulu kepada user sebelum mulai menulis. Minimal tanyakan hal-hal berikut yang belum diketahui:

### Pertanyaan Wajib untuk Setiap Laporan Baru
1. **Pertemuan ke berapa?** (untuk menentukan nomor modul dan tanggal)
2. **Tanggal pelaksanaan?** (format: DD Bulan YYYY)
3. **Topik/judul pertemuan ini?** (misalnya: "Analisis Masalah", "WBS", "Gantt Chart", dll.)
4. **Ada artefak/template khusus dari Bu Ratna?** (minta user upload PDF jika ada)
5. **Ada data baru dari lapangan?** (wawancara, observasi baru, data yang belum ada di draft)
6. **Ada perubahan dari pertemuan sebelumnya** yang perlu dikoreksi atau diperbarui?

### Pertanyaan Tambahan (Kondisional)
- Jika menyangkut keuangan/ZIS: apakah ada angka nyata dari masjid yang bisa digunakan?
- Jika menyangkut stakeholder baru: nama, jabatan, dan peran tata kelola informasinya?
- Jika menyangkut diagram: apakah ada struktur spesifik yang diminta Bu Ratna?

---

## 📋 WAJIB: BUAT IMPLEMENTATION PLAN SEBELUM EKSEKUSI

Setelah bertanya dan mendapatkan jawaban, agent WAJIB membuat **Implementation Plan** terlebih dahulu sebelum menulis laporan. Format plan:

```markdown
## Implementation Plan — Laporan Pertemuan [X]

### Konteks yang Dibaca
- [x] notes kelas.md
- [x] hasil wawancara masjid.md (sumber data primer)
- [x] hasil wawancara masjid pembanding dan analisis komparasi.md
- [x] Laporan Modul sebelumnya (referensi konsistensi)
- [x] Template PDF/MD Modul [X]

### Struktur Laporan yang Akan Dibuat
1. Identitas Laporan
2. Tujuan Kegiatan (dari template)
3. Uraian Pelaksanaan Kegiatan
   - Sub-bagian 1: ...
   - Sub-bagian 2: ...
4. Hasil/Artefak (daftar artefak yang akan dibuat)
   - Artefak 1: ... (format: tabel/diagram Mermaid/dll)
5. Kendala dan Solusi
6. Refleksi Pembelajaran
7. Kesimpulan
8. Referensi

### Diagram Mermaid yang Akan Dibuat
- [ ] Diagram jenis [X] untuk menggambarkan [Y]

### Data yang Akan Digunakan
- Dari notes kelas.md: ...
- Dari migrasi 3.md: ...
- Data baru dari user: ...

### Pertanyaan Terbuka
- [...hal yang masih belum jelas...]
```

Tampilkan plan ini dan **minta persetujuan user** sebelum mulai menulis laporan.

---

## 📐 STANDAR FORMAT LAPORAN

### Struktur 7 Bagian Wajib (dari Template Bu Ratna)
Setiap laporan WAJIB memiliki 7 bagian berikut (rubrik "Sangat Baik" = 7 bagian terisi lengkap dan rapi):

```
1. Identitas Laporan
2. Tujuan Kegiatan
3. Uraian Pelaksanaan Kegiatan
4. Hasil/Artefak Praktikum
5. Kendala dan Solusi
6. Refleksi Pembelajaran
7. Kesimpulan
(+ Referensi)
```

### Identitas Laporan (Selalu Isi dengan Data Ini)
```markdown
| Identitas | Isian |
|---|---|
| **Nama Kelompok** | Kelompok 1 — Kelas F1 |
| **Anggota (NIM/Nama)** | 1. Muhammad Riski — 24050530029 |
| | 2. Fajar Ahnaf Mahardika — 24050530030 |
| | 3. Muhadzdzib Terry Al-Fauzan — 24050530052 |
| **Pertemuan ke-** | [NOMOR] |
| **Tanggal Pelaksanaan** | [TANGGAL] |
| **Organisasi/Kasus yang Digunakan** | Masjid Besar Baitul Hikmah — SIM-BaitulHikmah |
```

---

## 🧭 STANDAR KONTEN — BERBASIS FILOSOFI BU RATNA

Agent wajib memastikan setiap laporan mencerminkan pemahaman MSI yang benar:

### ❌ Yang Harus DIHINDARI
- Berbicara tentang fitur aplikasi semata ("kami membuat modul X dengan fitur Y")
- Mengabaikan aspek manusia, proses, dan tata kelola
- Justifikasi yang hanya teknis tanpa menyebut tujuan strategis organisasi
- Analisis stakeholder yang hanya menyebut "pengguna" tanpa membahas otoritas data
- Diagram yang tidak memakai Mermaid (gunakan selalu Mermaid untuk semua grafik/chart)

### ✅ Yang WAJIB Ada
- Selalu kaitkan dengan **mengapa** (why) sistem dibutuhkan, bukan hanya **apa** (what)
- Sertakan minimal satu referensi ke **tiga level keputusan** (operasional-manajerial-strategis)
- Gunakan terminologi yang tepat: **tata kelola informasi**, **interkoneksi sistem**, **audit trail**, **evidence-based decision making**
- Refleksi harus mengaitkan pengalaman, konsep MSI, dan penerapan ke depan
- Kendala harus spesifik dan solusinya berbasis bukti

### 7 Aspek MSI (Selalu Jadikan Pijakan)
| No | Aspek | Relevansi pada SIM-BaitulHikmah |
|---|---|---|
| 1 | Keselarasan Strategis | Sistem terhubung ke misi masjid sebagai institusi sosial-keagamaan |
| 2 | Tata Kelola & Kualitas Informasi | Siapa berwenang atas data ZIS, jamaah, dan keuangan? |
| 3 | Dukungan Pengambilan Keputusan | 3 level: operasional (kasir), manajerial (bendahara), strategis (ketua takmir) |
| 4 | Kebutuhan Informasi Stakeholder | Setiap pihak butuh data berbeda: muzaki butuh transparansi, BAZNAS butuh pelaporan |
| 5 | Nilai Informasi | Akuntabilitas publik = kepercayaan umat = keberlanjutan masjid |
| 6 | Integrasi Proses Bisnis | Koneksi ke BAZNAS, DTKS Kelurahan, BADKO TPA, KUA |
| 7 | Adopsi & Perilaku Organisasi | Change management untuk pengurus senior yang resistif terhadap digitalisasi |

---

## 📊 STANDAR DIAGRAM — WAJIB MERMAID

**SELALU gunakan Mermaid untuk semua elemen visual.** Jangan gunakan tabel ASCII atau teks art untuk diagram.

### 🚨 PROTOKOL AUDIT DAN HARMONISASI MERMAID (ANTI-DIAGRAM USANG)
> **ATURAN WAJIB AGENT:** Setiap kali ada temuan lapangan baru, pembaruan konteks, atau revisi data pada suatu modul, agent **WAJIB menyisir dan mengaudit seluruh diagram Mermaid** di Modul 1, Modul 2, Modul 3, dst., untuk memastikan diagram tidak memakai data usang (*out-of-sync*).
> 
> **Poin Ceklis Harmonisasi Mermaid:**
> 1. **Power-Interest Grid (quadrantChart):** Sumbu X (Interest) & Y (Power). Pastikan kuadran Mermaid benar: Q1 (Kanan Atas = Manage Closely), Q2 (Kiri Atas = Keep Satisfied), Q3 (Kiri Bawah = Monitor), Q4 (Kanan Bawah = Keep Informed). Seluruh stakeholder pada tabel wajib muncul di diagram (termasuk Sie Sosial & ZISWAF, RISMA/REMAS, KUA, Kelurahan DTKS).
> 2. **Interkoneksi Sistem & Ekosistem:** Wajib memuat peran ganda KUA (agenda aula + penerima laporan PHBI Idul Fitri & Qurban sesuai PMA 34/2016 untuk diteruskan ke Kemenag Kota), Kelurahan DTKS sebagai jembatan data silo kemiskinan, BAZNAS (SIMBA), dan BADKO TPA.
> 3. **Tiga Level Keputusan:** Wajib memuat peran nyata pengurus SK 2026: Ketua I & II (Nanang Sahid & Jefri Nur Ihsan), Sekretaris I (Mardiyanto), Bendahara I (Hj. Retno), marbot merangkap pengajar TPA, dan 17 pemuda REMAS (*Dual-Tier*).
> 4. **Eliminasi Angka Fiktif:** DILARANG memuat angka nominal kas (misal Rp 2–3 jt) atau volume hewan qurban di dalam node diagram jika belum diverifikasi langsung oleh bendahara.
> 5. **Fishbone & Matriks Prioritas:** Kategori 6 dimensi harus berbasis tata kelola riil (bebas dari kalimat "karena belum ada aplikasi"), dan matriks prioritas harus membedakan jelas Quick Wins vs Proyek Strategis.

### Contoh Diagram yang Sering Digunakan

#### Power-Interest Grid (quadrantChart)
```mermaid
quadrantChart
    title Power Interest Grid SIM Baitul Hikmah
    x-axis Interest Rendah --> Interest Tinggi
    y-axis Power Rendah --> Power Tinggi
    quadrant-1 Manage Closely
    quadrant-2 Keep Satisfied
    quadrant-3 Monitor
    quadrant-4 Keep Informed
    Ketua Takmir dan Sekretaris: [0.86, 0.90]
    Bendahara I dan II: [0.82, 0.88]
    Sie Sosial dan ZISWAF: [0.75, 0.78]
    Kepala KUA Kecamatan: [0.48, 0.82]
    Kelurahan Klitren DTKS: [0.42, 0.75]
    BAZNAS Kota Yogyakarta: [0.38, 0.72]
    Muzaki dan Shahibul Qurban: [0.82, 0.32]
    Wali Santri dan Jamaah: [0.88, 0.20]
    RISMA Remaja Masjid: [0.70, 0.35]
    BADKO TPA Kemantren: [0.28, 0.45]
    Vendor Jaringan dan CCTV: [0.15, 0.15]
```

#### Interkoneksi Sistem (flowchart)
```mermaid
flowchart TD
    CORE["🕌 SIM Masjid Baitul Hikmah\n(Inti Sistem)"]
    KUA["🏛️ SI KUA\n(Jadwal Nikah & Bimwin)"]
    TKPPA["🏫 SI TK/TPA\n(Adm. & Kurikulum Santri)"]
    KEL["🏘️ SI Kelurahan\n(DTKS / Data Kemiskinan)"]
    BAZNAS["📊 SI BAZNAS\n(SIMBA - Standar Audit Zakat)"]
    CORE -->|Sinkronisasi jadwal ruang| KUA
    CORE -->|Sinkronisasi data santri & SPP| TKPPA
    CORE -->|Verifikasi silang mustahik| KEL
    CORE -->|Laporan penghimpunan & penyaluran ZIS| BAZNAS
```

#### Tiga Level Keputusan (flowchart LR)
```mermaid
flowchart LR
    subgraph S["🎯 Strategis (Ketua Takmir & Dewan)"]
        S1["Evaluasi kas jangka panjang\nRencana perluasan TK/TPA\nKebijakan beasiswa mustahik"]
    end
    subgraph M["📋 Manajerial (Bendahara, Sekretaris, Kepala TPA)"]
        M1["Laporan bulanan saldo kas\nPrioritas mustahik\nSinkronisasi jadwal lintas unit"]
    end
    subgraph O["⚙️ Operasional (Amil, Marbot, Ustadz)"]
        O1["Pencatatan kas harian\nPresensi santri TPA/TK\nJadwal penceramah"]
    end
    O -->|Data input| M
    M -->|Ringkasan laporan| S
    S -->|Kebijakan & arahan| M
    M -->|SOP & instruksi| O
```

#### Gantt Chart / Timeline
```mermaid
gantt
    title Timeline Proyek SIM-BaitulHikmah
    dateFormat  YYYY-MM-DD
    section Fase Analisis
    Pertemuan 1 - Profil Organisasi    :done, p1, 2026-08-24, 1d
    Pertemuan 2 - Stakeholder & Lingkungan Bisnis :done, p2, 2026-08-31, 1d
    Pertemuan 3 - Analisis Masalah     :p3, 2026-09-07, 1d
```

#### Lingkaran Konsentris (Ekosistem)
Gunakan flowchart dengan subgraph untuk menggambarkan lapisan konsentris:
```mermaid
flowchart TD
    subgraph L3["🌐 Lingkungan Bisnis Eksternal"]
        subgraph L2["👥 Stakeholder"]
            subgraph L1["🖥️ Inti: SIM-BaitulHikmah"]
                CORE["Basis Data NIK/NIA\nBuku Kas Digital\nData Santri\nSistem Seleksi Mustahik"]
            end
            ST1["Ketua Takmir\nBendahara\nSekretaris"]
            ST2["Pengajar TPA\nMarbot\nAmil Zakat"]
            ST3["Jamaah\nWali Santri\nMuzaki"]
        end
        EXT1["BAZNAS / LAZ"]
        EXT2["KUA & Kemenag"]
        EXT3["Kelurahan / DTKS"]
        EXT4["BADKO TPA"]
    end
```

---

## 🗓️ PANDUAN PER-MODUL: TARGET, ARTEFAK, DAN ANTI-SLOP

### Modul 1 — Profil Organisasi & Identifikasi Sistem (DONE)
- **Tujuan:** Mendeskripsikan organisasi, proses bisnis, dan sistem informasi yang sedang berjalan.
- **Artefak Wajib:** Tabel profil organisasi, diagram proses bisnis (flowchart Mermaid), identifikasi sistem yang ada.
- **Anti-Slop:** Jangan mendeskripsikan fitur yang diinginkan. Fokus pada *apa yang ada sekarang*, bukan *apa yang akan dibuat*.
- **Status:** ✅ Final (perlu revisi kecil: pastikan nama narasumber = Bpk. Mardianto, jabatan = Sekretaris)

### Modul 2 — Peta Stakeholder & Lingkungan Bisnis (DONE)
- **Tujuan:** Mengidentifikasi semua pemangku kepentingan dan kebutuhan informasi masing-masing.
- **Artefak Wajib:** Power-Interest Grid (quadrantChart Mermaid), RACI matrix, peta lingkungan bisnis (lingkaran konsentris).
- **Anti-Slop:** Stakeholder bukan sekadar "pengguna". Setiap entitas harus dijelaskan *otoritas datanya* (berwenang atas data apa?).
- **Status:** ✅ Final (perlu revisi: pastikan konsisten dengan data lapangan)

### Modul 3 — Analisis Masalah & Prioritas Solusi (TARGET SEGERA)
- **Tujuan:** Mengidentifikasi ≥3 masalah utama, menelusuri 1 akar masalah dengan Fishbone+5-Why, membuat matriks prioritas, dan menetapkan pernyataan masalah prioritas.
- **Artefak Wajib:**
  1. **Tabel Masalah Teridentifikasi** (min. 3 masalah) + kolom *Sumber/Metode: wajib ≥2 sumber berbeda*
  2. **Fishbone Diagram** (Mermaid) — kategori: Manusia, Proses, Teknologi, Kebijakan, Data, Lingkungan
  3. **Analisis 5-Why** — untuk 1 akar masalah terpilih
  4. **Matriks Prioritas** (quadrantChart Mermaid: Dampak vs Upaya)
  5. **Pernyataan Masalah Prioritas Akhir** — kalimat kondisi penyebab, bukan solusi
- **Anti-Slop Khusus Modul 3:**
  - ❌ JANGAN menulis "karena belum ada aplikasi" sebagai penyebab — ini adalah solusi, bukan akar masalah
  - ❌ JANGAN membuat Fishbone dari asumsi — setiap cabang HARUS ada *evidence*-nya dari `hasil wawancara masjid.md`
  - ❌ JANGAN menyebut gejala (kehilangan data) sebagai akar masalah — telusuri mengapa itu terjadi
  - ✅ Masalah yang bisa dipilih (sudah tervalidasi dari wawancara):
    * Hilangnya 70% data (PC rusak Feb 2026) → akar: tidak ada kebijakan backup
    * Laporan keuangan macet 3 tahun → akar: tidak ada SOP audit internal & segregation of duties
    * Key-person dependency sekretaris merangkap 6+ fungsi → akar: tidak ada distribusi peran & transfer pengetahuan
    * Data mustahik tanpa DTKS → akar: tidak ada integrasi data antar-lembaga
    * Triple entry pendaftaran Qurban → akar: tidak ada kanal input tunggal yang terstandarisasi
  - ✅ Sumber evidence untuk Lembar Kerja (gunakan minimal 2):
    * Sumber 1: Transkrip wawancara Bpk. Mardianto (hasil wawancara masjid.md)
    * Sumber 2: Komparasi empiris Masjid Mujur Al-Amin (hasil wawancara masjid pembanding...md)
    * Sumber 3 (jika perlu): Regulasi Kemenag DJ.II/802/2014 (standar Masjid Besar)
- **Tanggal Pelaksanaan:** 7 September 2026
- **Status:** ✅ Selesai (`Laporan Modul 3 - Kelompok 1 F1.md`)

### Modul 4 (dst.) — Project Scope & WBS (Mendatang)
- **Catatan:** Data TPA dari Mas Jefri & Nurul Ashri Deresan menjadi pengayaan untuk Modul 4+.
- **Jangan jadikan data TPA dan Nurul Ashri sebagai blocker Modul 3.**

---

## 📁 KONVENSI PENAMAAN FILE

```
Laporan Modul [N] - Kelompok 1 F1.md
```

Contoh:
- `Laporan Modul 1 - Kelompok 1 F1.md`
- `Laporan Modul 3 - Kelompok 1 F1.md`

---

## 🏛️ TEMUAN RISET & PENGAYAAN KONTEKS TERKINI (SESI VALIDASI AKADEMIK)

### 1. Rasionalisasi MSI vs Komputerisasi Langsung (Jawaban untuk Bu Ratna)
* **Kritik Dosen:** *"Pencatatan manual tidak selalu solusinya computerize. SDM tua malah bingung dan menimbulkan masalah baru."*
* **Landasan Teoretis Peer-Reviewed:**
  * **Task-Technology Fit (Goodhue & Thompson, 1995):** Ketidakcocokan antara teknologi tinggi dan kapabilitas pengguna justru menurunkan kinerja organisasi.
  * **Technology Acceptance Model (Davis, 1989):** Persepsi kerumitan tinggi memicu penolakan dan *system abandonment*.
  * **Internal Control & Segregation of Duties (Romney & Steinbart, 2018):** Insiden penyalahgunaan dana kas TPA bukan karena ketiadaan aplikasi, melainkan ketiadaan pemisahan wewenang pemegang kas fisik dan pencatat buku.
* **Solusi Arsitektur Sosio-Teknis:** **Dual-Tier Operating Model (Sistem Hibrid)**. Marbot sepuh tetap menggunakan lembar logbook fisik terstandarisasi, sementara 17 pemuda REMAS difungsikan sebagai operator rekonsiliasi data digital berkala.

### 2. Hierarki Regulasi & Aturan Bisnis (Makro ke Mikro)
* **Tingkat Makro (Regulasi Pemerintah & Nasional):**
  * Legalitas tanah wakaf berada di bawah **Badan Wakaf Indonesia (BWI)** dan KUA sebagai PPAIW.
  * Izin pendirian rumah ibadah mengacu **SKB 2 Menteri No. 9 & 8 Tahun 2006** (90 calon pengguna & 60 dukungan warga).
  * Pendaftaran resmi di Kementerian Agama RI melalui nomor registrasi **ID SIMAS** (Sistem Informasi Masjid).
  * Standar pembinaan tipologi masjid mengacu Keputusan Dirjen Bimas Islam No. DJ.II/802 Tahun 2014.
  * **KOREKSI SEMANTIK PENTING:** TPA masjid adalah **Taman Pendidikan Al-Qur'an** (di bawah binaan BADKO TPA & Kemenag), BUKAN Tempat Pemrosesan Akhir sampah (KLHK/PUPR).
* **Tingkat Meso (Tata Kelola Organisasi Takmir):**
  * Penentuan takmir: wajib meneliti apakah melalui musyawarah warga berkala (3–5 tahun), penunjukan lisan sesepuh, atau SK resmi Kepala Desa/KUA/DMI.
  * Pembagian bidang mengacu standar Kemenag: Idarah (manajemen), Imarah (ibadah/dakwah), dan Ri'ayah (pemeliharaan fisik).
* **Tingkat Mikro (Operasional Sehari-hari):**
  * Master data jamaah (by-name by-address).
  * Prosedur kontinjensi penunjukan ustadz badal saat khatib Jumat batal mendadak.
  * *Dual custody* (hitung kas berdua dengan saksi & berita acara) saat membuka kotak infak Jumat.
  * Sinkronisasi data mustahik zakat dengan DTKS Kelurahan.

### 3. Komparasi Benchmark: Masjid Baitul Hikmah vs Masjid Nurul Ashri Deresan
* **Sumber Data Benchmark:** Desk research dari website `masjidnurulashri.com` + Instagram `@masjidnurulashri` (diakses 13 September 2026). **Wawancara lapangan dijadwalkan Selasa** untuk data mendalam.
* **Tipologi:** Baitul Hikmah = Masjid Besar (tingkat kecamatan). Nurul Ashri = Masjid Jami' lingkungan. Paradoks: Nurul Ashri yang lebih *kecil* secara tipologi justru lebih *matang* secara digital.
* **Statistik Nurul Ashri (dari website publik):** 2.450+ jamaah aktif, 48+ program berjalan, 1.250+ penerima manfaat, 25+ relawan, 13 campaign donasi aktif dengan progress bar real-time, total dana terkumpul ~Rp 10.178.000.
* **Program Utama Nurul Ashri:** Nurul Ashri Qurban (online), Nurul Ashri Education (kelas Tahsin & Fiqih via lebihpaham.com), Nurul Ashri Peduli (sosial-kemanusiaan), Bazar Sayur Bakda Subuh (pemberdayaan petani-jamaah), respon kebencanaan (Flores, NTT, Kalimantan).
* **Gap Utama Baitul Hikmah vs Nurul Ashri:**
  * Transparansi: Nurul Ashri = real-time online; Baitul Hikmah = 3 tahun tanpa laporan tertulis
  * Digital: Nurul Ashri = Next.js website aktif; Baitul Hikmah = tidak ada website
  * Backup: Nurul Ashri = cloud; Baitul Hikmah = PC rusak → 70% data hilang
* **Catatan Data Gap:** Data TPA, kas operasional harian, dan struktur takmir Nurul Ashri **belum diperoleh** dari website — perlu wawancara Selasa.

### 4. Investigasi Dinamika Penurunan Partisipasi (Decline Dynamics)
* **Penurunan Jamaah Shalat:** Faktor demografi (lansia wafat, generasi muda merantau), jam kerja modern, serta dominasi lansia pensiunan.
* **Penyusutan Santri TPA:** Dampak kebijakan *Full-Day School* (anak kelelahan jam 16.00), maraknya les bimbel umum di luar, gawai/gadget, dan kejenuhan metode mengajar monoton.
* **Pergeseran Donatur:** Muzaki/shahibul qurban beralih menyalurkan dana ke LAZ luar karena faktor transparansi laporan atau kepraktisan transfer perbankan digital.
* **Krisis Regenerasi:** Pemuda (REMAS) enggan aktif karena merasa tidak diberi ruang suara oleh pengurus senior.

### 5. Komparasi Empiris Tingkat Masjid: Target (Baitul Hikmah) vs Pembanding Lapangan (Mujur Al-Amin)
* **Tata Kelola Takjil Ramadhan:**
  * *Masjid Pembanding (Mujur Al-Amin):* Menggunakan **Papan Terbuka Swakelola (Self-Service 1–30 Ramadhan)** di mana warga menulis mandiri jenis takjil (besar/kecil). Terbukti transparan dan mencegah kekosongan hari.
  * *Target (Baitul Hikmah):* Asimetri informasi tertutup di tangan seksi konsumsi, warga mengira sudah penuh sehingga terjadi kekosongan slot di hari-hari tertentu.
* **Tata Kelola & Kemandirian TPA:**
  * *Masjid Pembanding (Mujur Al-Amin):* Struktur TPA otonom dipimpin "Direktur & Bendahara TPA", kas SPP terpisah secara sukarela (Rp 2k–10k), strategi kirab Muharram berhasil menjaga 80–90 santri aktif.
  * *Target (Baitul Hikmah):* TPA dititipkan pada marbot sepuh, kas pernah tercampur dengan dana pribadi, santri menyusut drastis (< 30 anak).
* **Pengendalian Kas Infak (Internal Control):**
  * *Masjid Pembanding (Mujur Al-Amin):* Kotak infak dibuka rutin 2 minggu sekali dengan **saksi (dual custody)** dan rekap ditempel bulanan di papan pengumuman.
  * *Target (Baitul Hikmah):* Dicatat terpisah di Word/Excel bendahara dan sekretaris tanpa rekonsiliasi formal, memicu selisih hitung di akhir bulan.
* **Mitigasi Khatib/Ustadz Berhalangan:**
  * *Masjid Pembanding (Mujur Al-Amin):* Menyiapkan ustadz badal (cadangan) lokal internal masjid jika ustadz luar/Ahad pagi berhalangan hadir.
  * *Target (Baitul Hikmah):* Belum ada SOP kontinjensi resmi; jika khatib batal mendadak, takmir panik atau marbot dadakan disuruh membaca hadits.

---

## 📚 REFERENSI BAKU

Referensi berikut selalu dimasukkan di setiap laporan (pilih yang relevan):

### Buku Teks & Landasan Teori MSI
- Laudon, K. C., & Laudon, J. P. (2014). *Management information systems: Managing the digital firm* (13th ed.). Pearson Education.
- Sousa, K. J., & Oz, E. (2014). *Management information systems* (7th ed.). Cengage Learning.
- Romney, M. B., & Steinbart, P. J. (2018). *Accounting information systems* (14th ed.). Pearson Education.
- Goodhue, D. L., & Thompson, R. L. (1995). Task-technology fit and individual performance. *MIS Quarterly*, 19(2), 213–236. DOI: 10.2307/249689.
- Davis, F. D. (1989). Perceived usefulness, perceived ease of use, and user acceptance of information technology. *MIS Quarterly*, 13(3), 319–340. DOI: 10.2307/249008.
- Markus, M. L. (1983). Power, politics, and MIS implementation. *Communications of the ACM*, 26(6), 430–444. DOI: 10.1145/358141.358148.

### Regulasi & Standar Pemerintah
- Kementerian Agama RI. (2011). *Undang-Undang No. 23 Tahun 2011 tentang Pengelolaan Zakat*. Kemenag RI.
- BAZNAS. (2023). *Sistem Manajemen Informasi BAZNAS (SIMBA)*. Badan Amil Zakat Nasional.
- Kementerian Agama & Kementerian Dalam Negeri RI. (2006). *Peraturan Bersama Menteri Agama dan Menteri Dalam Negeri No. 9 dan 8 Tahun 2006 tentang Pedoman Pelaksanaan Tugas Kepala Daerah/Wakil Kepala Daerah dalam Pemeliharaan Kerukunan Umat Beragama, Pemberdayaan Forum Kerukunan Umat Beragama, dan Pendirian Rumah Ibadat*.
- Direktorat Jenderal Bimbingan Masyarakat Islam. (2014). *Keputusan Direktur Jenderal Bimbingan Masyarakat Islam No. DJ.II/802 Tahun 2014 tentang Standar Pembinaan Manajemen Masjid*. Kemenag RI.

### Studi Empiris Masjid & Benchmark Jogokariyan
- Sabili, F., Romansyah, D., & Hidayat, R. (2023). Akuntabilitas dan transparansi laporan keuangan masjid (Studi kasus Masjid Jogokariyan Yogyakarta). *JAKIS: Jurnal Akuntansi dan Keuangan Islam*, 11(2), 233–249. DOI: 10.35836/jakis.v11i2.626.
- Widyanti, R., & Rahmayanti, D. (2020). Perancangan dan implementasi sistem informasi manajemen kegiatan masjid: Studi kasus Masjid Jogokariyan Yogyakarta. *JSTIE (Jurnal Sarjana Teknik Informatika)*, 1(1), 119–128. DOI: 10.12928/jstie.v1i1.2513.
- Wibowo, A. E., dkk. (2024). Kampung Ramadhan Jogokariyan (KRJ): Peran manajemen masjid dalam pariwisata ramah Muslim dan ekonomi lokal. *AKUA: Jurnal Akuntansi dan Keuangan*, 4(2). DOI: 10.54259/akua.v4i2.4258.
- Arsam, A., Nurmahyati, S., & Amaluddin, A. (2024). Manajemen dakwah takmir Masjid Jogokaryan dalam membangun peradaban Islam di Mantrijeron Yogyakarta. *Tadbir: Jurnal Manajemen Dakwah*, 9(1), 19–40. DOI: 10.15575/tadbir.v9i1.33885.
- Sutono, M. A., & Risyan, R. M. (2023). Digitalisasi sistem informasi manajemen masjid modern. *INFOTECH Journal*, 9(1), 1–10. DOI: 10.31949/infotech.v9i1.4222.

---

## ⚠️ CHECKLIST SEBELUM SUBMIT LAPORAN

Sebelum menyatakan laporan selesai, agent WAJIB memverifikasi:

**Struktur & Format**
- [ ] 7 bagian utama terisi lengkap dan rapi
- [ ] Identitas laporan benar: nama, NIM, **tanggal aktual** (konfirmasi ke user), pertemuan
- [ ] Nama narasumber: **Bpk. Mardianto**, jabatan: **Sekretaris** (bukan Ketua Takmir)
- [ ] Semua diagram menggunakan sintaks Mermaid (bukan ASCII art)
- [ ] Nama file sesuai konvensi: `Laporan Modul [N] - Kelompok 1 F1.md`

**Konten & Kedalaman Akademik**
- [ ] Setiap klaim empiris dikaitkan ke sumber wawancara (bukan asumsi)
- [ ] Tidak ada bahasa "aplikasi-sentris" (bukan "kami membuat fitur X")
- [ ] Minimal satu referensi ke 3 level keputusan (operasional-manajerial-strategis)
- [ ] Refleksi mengaitkan pengalaman + konsep MSI + penerapan ke depan
- [ ] Kendala bersifat spesifik (bukan generik "kami kesulitan")
- [ ] Konten konsisten dengan laporan-laporan pertemuan sebelumnya

**Anti-Halusinasi (Khusus Modul 3+)**
- [ ] Fishbone/5-Why hanya berisi penyebab yang ADA di data lapangan
- [ ] Tidak ada angka/data yang tidak ada di `hasil wawancara masjid.md`
- [ ] Pernyataan masalah prioritas dirumuskan sebagai *kondisi penyebab*, bukan solusi/fitur
- [ ] Setiap baris Lembar Kerja Modul 3 mencantumkan ≥2 sumber yang saling menguatkan

## 🧑‍🔬 CATATAN PENELITI — AWARENESS GAPS

Sebagai peneliti yang jujur, perlu diingat bahwa data saat ini memiliki keterbatasan:

| Gap | Dampak pada Laporan | Status |
|---|---|---|
| Data TPA mendalam (Mas Jefri) belum diperoleh | Analisis proses bisnis TPA hanya dari 1 pernyataan Bpk. Mardianto | 🔴 Pending |
| Data keuangan numerik (nominal kas, ZIS) tidak diperoleh | Evidence keuangan masih kualitatif | 🟡 Partial |
| Nurul Ashri Deresan belum diwawancarai | Spektrum benchmark hanya 2 masjid (bukan 3) | 🟡 Dijadwalkan Selasa |
| Laporan Modul 1 & 2 belum direvisi dengan fakta lapangan | Ada risiko inkonsistensi lintas laporan | 🟡 Perlu segera |

Dalam laporan, JANGAN memalsukan data yang belum ada. Jika ada gap, nyatakan sebagai "data belum tersedia" atau "memerlukan konfirmasi lanjutan".
