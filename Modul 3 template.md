# MODUL PRAKTIKUM MANAJEMEN SISTEM INFORMASI (PTF60234)
## PERTEMUAN 3: Analisis Masalah Organisasi dan Prioritas Solusi
*Program Studi Pendidikan Teknik Informatika - S1 | Semester 5 | 2 SKS*  
*Fakultas Teknik — Universitas Negeri Yogyakarta*  
*Dosen Pengampu: Dr. Ratna Wardani, S.Si., M.T.*  
*Tahun Akademik: 2026 / Semester 5 | Model Pembelajaran: Project-Based Learning*

---

## 🎯 CPMK & TUJUAN PRAKTIKUM

| Komponen | Deskripsi |
|---|---|
| **CPMK 1** | Memahami permasalahan, kebutuhan pemangku kepentingan, dan sumber daya yang dibutuhkan untuk mengelola sistem informasi di lingkungan organisasi. |
| **Tujuan Praktikum** | Mahasiswa mampu mengidentifikasi akar masalah pengelolaan sistem informasi pada organisasi kasus dan menentukan prioritas solusi. |

---

## 🧭 KERANGKA 7 ASPEK PENGELOLAAN SISTEM INFORMASI

Sepanjang praktikum ini, setiap keputusan proyek sistem informasi sebaiknya ditinjau melalui tujuh aspek pengelolaan sistem informasi berikut. Ketujuh aspek ini yang membedakan disiplin **Manajemen Sistem Informasi** dari manajemen proyek perangkat lunak secara umum, karena menempatkan **informasi dan pengambilan keputusan organisasi sebagai inti perhatian**, bukan penyerahan perangkat lunak semata.

| No | Aspek | Penjelasan |
|:---:|:---|:---|
| **1** | **Keselarasan Strategis** | Sistem informasi yang dibangun harus eksplisit terhubung ke tujuan atau misi organisasi, bukan proyek teknis yang berdiri sendiri tanpa kaitan jelas terhadap arah organisasi. |
| **2** | **Tata Kelola dan Kualitas Informasi** | Mencakup akurasi, konsistensi, kepemilikan data, dan akuntabilitas atas informasi, yaitu kejelasan siapa berwenang atas data apa dan siapa bertanggung jawab menjaga kualitasnya. *(Fokus Utama Pertemuan 3)* |
| **3** | **Dukungan Pengambilan Keputusan** | Setiap artefak proyek dinilai dari seberapa baik ia mendukung pengambilan keputusan di level operasional, manajerial, maupun strategis, sebagaimana dibahas pada Pertemuan 1. |
| **4** | **Kebutuhan Informasi Stakeholder** | Bukan sekadar preferensi generik terhadap fitur aplikasi, melainkan data dan laporan spesifik apa yang benar-benar dibutuhkan tiap pihak, sebagaimana dipetakan pada Pertemuan 2. |
| **5** | **Nilai Informasi** | Evaluasi proyek, termasuk KPI dan ROI pada Pertemuan 10 dan 11, diukur dari perbaikan kualitas keputusan dan informasi yang dihasilkan, bukan semata-mata efisiensi teknis pengerjaan proyek. |
| **6** | **Integrasi Proses Bisnis** | Sistem informasi dinilai dari bagaimana ia terhubung dan terintegrasi dengan alur kerja organisasi lintas fungsi, bukan sekadar fitur aplikasi yang berdiri sendiri. |
| **7** | **Adopsi dan Perilaku Organisasi terhadap Informasi** | Perubahan yang perlu dikelola adalah perubahan perilaku pencatatan, pelaporan, dan penggunaan data oleh pengguna, bukan sekadar penerimaan aplikasi baru secara umum. |

> **Fokus MSI Pertemuan 3:**  
> **Aspek 2 (Tata Kelola dan Kualitas Informasi)** menjadi penekanan utama, karena akar masalah yang ditelusuri adalah **persoalan pengelolaan informasi organisasi**, bukan penyebab keterlambatan proyek.

---

## 💡 KONSEP DASAR

Pada praktikum Manajemen Sistem Informasi, teknik **Fishbone diagram**, teknik **5-Why**, dan **matriks prioritas** digunakan untuk menelusuri akar masalah dalam pengelolaan informasi organisasi, bukan untuk menelusuri penyebab keterlambatan proyek atau memilih fitur mana yang akan dikerjakan lebih dulu. Objek yang dianalisis pun bukan aktivitas proyek, melainkan persoalan nyata tentang bagaimana organisasi mengelola dan menindaklanjuti informasi.

Salah satu kesalahan yang sering terjadi dalam pengembangan sistem informasi adalah **merancang solusi sebelum masalah benar-benar dipahami**. Gejala yang tampak di permukaan sering dianggap sebagai masalah itu sendiri, padahal gejala hanyalah tanda dari persoalan yang lebih dalam. Laudon dan Laudon (2014) menekankan bahwa keputusan sistem informasi yang efektif selalu berangkat dari pemahaman yang akurat terhadap kebutuhan organisasi, bukan dari asumsi cepat tentang penyebab masalah.

### 1. Fishbone Diagram (Ishikawa, 1976)
Fishbone diagram, atau diagram sebab-akibat, digunakan untuk mengorganisasi berbagai kemungkinan penyebab yang berkontribusi terhadap satu masalah. Diagram ini membantu kelompok melihat masalah secara lebih menyeluruh sebelum menetapkan penyebab tertentu sebagai akar masalah.

Dalam praktikum MSI, kategori penyebab disesuaikan dengan konteks organisasi dan pengelolaan sistem informasi:
1. **Manusia (*People*)**
2. **Proses (*Process*)**
3. **Sistem / Teknologi (*Technology*)**
4. **Kebijakan (*Policy / Governance*)**
5. **Data / Informasi (*Data*)**
6. **Lingkungan Organisasi (*Environment*)**

#### Langkah Penyusunan Fishbone:
1. Rumuskan efek/masalah secara spesifik dan dapat diamati pada kepala diagram.
2. Tentukan kategori penyebab yang sesuai dengan konteks organisasi.
3. Identifikasi kemungkinan penyebab pada setiap kategori berdasarkan data yang tersedia.
4. Kelompokkan penyebab yang saling berhubungan dan hindari menuliskan solusi sebagai penyebab.
5. Tandai penyebab yang masih berupa dugaan dan penyebab yang telah didukung *evidence*.
6. Pilih cabang penyebab yang paling relevan untuk ditelusuri lebih dalam menggunakan 5-Why atau pemeriksaan bukti.

---

### 2. Teknik 5-Why (Ohno, 1988)
Teknik 5-Why digunakan untuk menelusuri hubungan sebab-akibat dengan mengajukan pertanyaan “mengapa?” terhadap jawaban sebelumnya secara berulang. Tujuannya membawa analisis dari **gejala menuju penyebab yang lebih mendasar**.

#### Langkah Penggunaan 5-Why:
1. Tuliskan masalah/gejala yang benar-benar diamati.
2. Ajukan pertanyaan “Mengapa masalah ini terjadi?”
3. Tuliskan jawaban yang spesifik dan dapat diperiksa.
4. Ajukan “Mengapa?” terhadap jawaban tersebut, bukan kembali ke masalah awal.
5. Ulangi hingga ditemukan penyebab yang mendasar dan masih relevan untuk ditangani.
6. Validasi setiap hubungan sebab-akibat dengan bukti yang tersedia.
7. Rumuskan akar masalah sebagai **kondisi penyebab**, bukan sebagai fitur atau solusi.

#### Komparasi Fishbone vs 5-Why:
| Teknik | Fungsi Utama | Hasil yang Diharapkan |
|---|---|---|
| **Fishbone** | Mengelompokkan berbagai kemungkinan penyebab dari beberapa sudut pandang. | Peta kemungkinan penyebab dan cabang yang perlu ditelusuri. |
| **5-Why** | Memperdalam satu rangkaian sebab-akibat secara bertahap. | Rangkaian sebab-akibat menuju penyebab yang lebih mendasar. |
| **Kombinasi** | Fishbone membuka ruang kemungkinan, 5-Why memperdalam cabang yang paling relevan. | Analisis akar masalah yang lebih sistematis dan dapat divalidasi. |

#### Catatan Penting dalam Analisis Akar Masalah:
- ❌ Jangan menyamakan gejala dengan akar masalah.
- ❌ Jangan menuliskan solusi sebagai penyebab (misal: "karena belum ada aplikasi web").
- ❌ Jangan menggunakan penilaian pribadi tanpa *evidence* sebagai fakta.
- ⚠️ Satu masalah dapat memiliki lebih dari satu jalur penyebab; jangan memaksakan satu jalur jika data menunjukkan hal berbeda.
- ✅ Akar masalah harus dirumuskan dalam bentuk **kondisi penyebab**.

---

### 3. Matriks Prioritas Masalah (Dampak vs Upaya)

Setelah akar masalah teridentifikasi, tim proyek menghadapi keterbatasan waktu dan sumber daya (1 semester). Matriks prioritas membantu memilih masalah yang memberikan **manfaat besar dengan upaya yang realistis**:

```mermaid
quadrantChart
    title Matriks Prioritas Masalah (Dampak vs Upaya)
    x-axis Rendah Upaya --> Tinggi Upaya
    y-axis Rendah Dampak --> Tinggi Dampak
    quadrant-1 Proyek Strategis (Dampak Tinggi, Upaya Tinggi)
    quadrant-2 Prioritas Utama (Dampak Tinggi, Upaya Rendah)
    quadrant-3 Kerjakan Jika Sempat (Dampak Rendah, Upaya Rendah)
    quadrant-4 Hindari / Tunda (Dampak Rendah, Upaya Tinggi)
```

- **Prioritas Utama (Quick Wins):** Dampak Tinggi, Upaya Rendah ➔ **Fokus Utama Proyek**.
- **Proyek Strategis:** Dampak Tinggi, Upaya Tinggi ➔ Dipertimbangkan bertahap.
- **Kerjakan Jika Sempat:** Dampak Rendah, Upaya Rendah ➔ Opsional.
- **Hindari/Tunda:** Dampak Rendah, Upaya Tinggi ➔ Jangan dijadikan fokus proyek.

---

## 🛠️ LANGKAH KERJA PRAKTIKUM

1. **Identifikasi Masalah Utama (15 menit):** Mendaftar **minimal tiga masalah utama** terkait pengelolaan informasi pada organisasi kasus berdasarkan Lembar Profil (Modul 1) dan Peta Stakeholder (Modul 2).
2. **Analisis Akar Masalah (25 menit):** Memilih satu masalah paling signifikan, menelusuri akar masalahnya menggunakan Fishbone atau 5-Why hingga diperoleh penyebab mendasar.
3. **Penilaian Prioritas (15 menit):** Seluruh masalah dinilai menggunakan Matriks Prioritas (Dampak vs Upaya).
4. **Penetapan Masalah Prioritas (10 menit):** Menetapkan satu masalah dengan prioritas tertinggi yang akan diselesaikan sepanjang semester dalam bentuk **pernyataan masalah yang ringkas dan jelas**.

---

## 📋 LEMBAR KERJA: DOKUMEN ANALISIS MASALAH (ARTEFAK UTAMA)

> **ATURAN MUTLAK:**  
> Setiap isian **WAJIB** disertai penjelasan pada kolom *"Sumber/Metode Perolehan Data"* dengan **minimal 2 sumber berbeda yang saling menguatkan** (misalnya wawancara dikonfirmasi dengan observasi langsung atau dokumen resmi). Jawaban tanpa sumber atau hanya asumsi **tidak akan dinilai**.

| Bagian | Isian | Sumber/Metode Perolehan Data *(Minimal 2 Sumber Berbeda)* |
|---|---|---|
| **Daftar Masalah Teridentifikasi (Min. 3)** | 1. __________________<br>2. __________________<br>3. __________________ | __________________ |
| **Masalah Terpilih untuk Analisis Akar** | __________________ | __________________ |
| **Hasil Analisis Akar Masalah (Fishbone/5-Why)** | __________________ | __________________ |
| **Matriks Prioritas (Dampak vs Upaya)** | __________________ | __________________ |
| **Pernyataan Masalah Prioritas Akhir** | __________________ | __________________ |

---

## 📊 ASESMEN & RUBRIK PENILAIAN

### 1. Rubrik Penilaian Artefak / Lembar Kerja
| Aspek | Kurang | Cukup | Baik | Sangat Baik |
|---|---|---|---|---|
| **Ketepatan Identifikasi Masalah** | Masalah tidak relevan atau hanya gejala | Sebagian masalah relevan | Relevan dan berbasis observasi | Relevan dan berbasis evidence kuat |
| **Kedalaman Analisis Akar Masalah** | Tidak dilakukan analisis akar | Analisis dangkal, berhenti pada gejala | Analisis cukup mendalam | Analisis mendalam hingga akar masalah |
| **Ketepatan Prioritas Solusi** | Prioritas tidak beralasan | Prioritas beralasan lemah | Prioritas logis | Prioritas logis dan strategis |
| **Kualitas dan Keragaman Sumber Data** | Tidak ada sumber, hanya asumsi | Sumber dicantumkan tapi < 2 atau tidak jelas | Minimal 2 sumber berbeda, cukup jelas | Minimal 2 sumber berbeda yang saling menguatkan (wawancara dikonfirmasi dokumen) |

### 2. Rubrik Penilaian Laporan Praktikum (Baku 7 Bagian)
| Aspek | Kurang | Cukup | Baik | Sangat Baik |
|---|---|---|---|---|
| **Kelengkapan Struktur Laporan** | < 4 dari 7 bagian terisi | 5–6 bagian terisi | 7 bagian terisi lengkap | 7 bagian terisi lengkap dan rapi |
| **Kualitas Uraian Pelaksanaan Kegiatan** | Uraian minim, hanya salin langkah | Deskriptif, kurang alasan keputusan | Menjelaskan proses & alasan keputusan cukup jelas | Menjelaskan proses, alasan, dan pertimbangan secara rinci |
| **Ketepatan Analisis Kendala dan Solusi** | Kendala tidak diidentifikasi | Kendala tanpa solusi jelas | Kendala & solusi cukup relevan | Kendala & solusi relevan dan menunjukkan pemecahan masalah aktif |
| **Kedalaman Refleksi Pembelajaran** | Tidak ada refleksi / sekadar mengulang | Refleksi ada namun dangkal | Mengaitkan pengalaman dengan konsep | Mendalam: mengaitkan pengalaman, konsep, dan penerapan ke depan |

---

## 📑 FORMAT LAPORAN MINGGUAN: PERTEMUAN 3 (STRUKTUR 7 BAGIAN)

```markdown
1. Identitas Laporan
   - Nama Kelompok: Kelompok 1 — Kelas F1
   - Anggota (NIM/Nama): 
     1. Muhammad Riski — 24050530029
     2. Fajar Ahnaf Mahardika — 24050530030
     3. Muhadzdzib Terry Al-Fauzan — 24050530052
   - Pertemuan ke-: 3
   - Tanggal Pelaksanaan: [Tanggal Praktikum]
   - Organisasi/Kasus: Masjid Besar Baitul Hikmah — SIM-BaitulHikmah

2. Tujuan Kegiatan
   (Sesuai modul: Mahasiswa mampu mengidentifikasi akar masalah pengelolaan sistem informasi pada organisasi kasus dan menentukan prioritas solusi.)

3. Uraian Pelaksanaan Kegiatan
   (Jelaskan proses identifikasi minimal 3 masalah utama, cara menelusuri akar masalah dengan Fishbone/5-Why, dan pertimbangan penentuan prioritas pada matriks.)

4. Hasil/Artefak Praktikum
   (Lampiran Dokumen Analisis Masalah yang terisi lengkap dengan bukti minimal 2 sumber berbeda.)

5. Kendala dan Solusi
   (Tantangan membedakan gejala vs akar masalah dan bagaimana menyelesaikannya secara metodologis.)

6. Refleksi Pembelajaran
   (Pelajaran mengenai beda gejala vs akar masalah dan bagaimana hal ini mengubah pemahaman terhadap sistem informasi masjid.)

7. Kesimpulan
   (Ringkasan pernyataan masalah prioritas akhir dan kesiapan menyusun Project Scope pada Pertemuan 4.)

Referensi
- Laudon, K. C., & Laudon, J. P. (2014). Management information systems: Managing the digital firm (13th ed.). Pearson Education.
- Ishikawa, K. (1976). Guide to quality control. Asian Productivity Organization.
- Ohno, T. (1988). Toyota production system: Beyond large-scale production. Productivity Press.
```
