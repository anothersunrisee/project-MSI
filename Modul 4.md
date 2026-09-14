_Modul Praktikum MSI - PTF60234_ 

### **KEMENTERIAN PENDIDIKAN TINGGI, SAINS, DAN TEKNOLOGI UNIVERSITAS NEGERI YOGYAKARTA FAKULTAS TEKNIK** 

**PROGRAM STUDI PENDIDIKAN TEKNIK INFORMATIKA - S1** 

**MODUL PRAKTIKUM** 

# **MANAJEMEN SISTEM INFORMASI** 

**PTF60234** 

_Program Studi Pendidikan Teknik Informatika - S1  |  Semester 5  |  2 SKS_ 

Praktik Manajemen Sistem Informasi / PTF60234 

**Mata Kuliah / Kode Dosen Pen** **<mark>g</mark> am** **<mark>p</mark> u** Dr. Ratna Wardani, S.Si., M.T. **Tahun Akademik** 2026 / Semester 5 **Model Pembela** **<mark>j</mark> aran** Project-Based Learning 

_Setiap pertemuan menghasilkan satu artefak proyek yang dibangun secara kumulatif berdasarkan organisasi/kasus yang dipilih kelompok pada Pertemuan 1._ 

Universitas Negeri Yogyakarta - Halaman 1 

_Modul Praktikum MSI - PTF60234_ 

## **<mark>PERTEMUAN 4</mark>** 

**_Perencanaan Proyek TI: Scope, Tujuan, dan Deliverables_** 

|**CPMK**|**Tujuan Praktikum**|
|---|---|
|CPMK 2. Membuat rencana proyek, menetapkan<br>tujuan, menetapkan peran tim, serta merancang strategi<br>implementasi sistem informasi yang sesuai dengan visi<br>dan misi organisasi.|Mahasiswa mampu menyusun ruang lingkup, tujuan,<br>dan deliverables proyek sistem informasi berdasarkan<br>masalah prioritas yang telah ditetapkan pada<br>pertemuan sebelumnya.|



### **Kerangka Aspek Pengelolaan Sistem Informasi** 

Sepanjang praktikum ini, setiap keputusan proyek sistem informasi sebaiknya ditinjau melalui tujuh aspek pengelolaan sistem informasi berikut. Ketujuh aspek ini yang membedakan disiplin Manajemen Sistem Informasi dari manajemen proyek perangkat lunak secara umum, karena menempatkan informasi dan pengambilan keputusan organisasi sebagai inti perhatian, bukan penyerahan perangkat lunak semata. 

|**Aspek**|**Penjelasan**|
|---|---|
|1. Keselarasan Strategis|Sistem informasi yang dibangun harus eksplisit terhubung ke tujuan<br>atau misi organisasi, bukan proyek teknis yang berdiri sendiri tanpa<br>kaitan jelas terhadap arah organisasi.|
|2. Tata Kelola dan Kualitas Informasi|Mencakup akurasi, konsistensi, kepemilikan data, dan akuntabilitas<br>atas informasi, yaitu kejelasan siapa berwenang atas data apa dan<br>siapa bertanggung jawab menjaga kualitasnya.|
|3. Dukungan Pengambilan Keputusan|Setiap artefak proyek dinilai dari seberapa baik ia mendukung<br>pengambilan keputusan di level operasional, manajerial, maupun<br>strategis, sebagaimana dibahas pada Pertemuan 1.|
|4. Kebutuhan Informasi Stakeholder|Bukan sekadar preferensi generik terhadap fitur aplikasi, melainkan<br>data dan laporan spesifik apa yang benar-benar dibutuhkan tiap<br>pihak, sebagaimana dipetakan pada Pertemuan 2.|
|5. Nilai Informasi|Evaluasi proyek, termasuk KPI dan ROI pada Pertemuan 10 dan 11,<br>diukur dari perbaikan kualitas keputusan dan informasi yang<br>dihasilkan, bukan semata-mata efisiensi teknis pengerjaan proyek.|
|6. Integrasi Proses Bisnis|Sistem informasi dinilai dari bagaimana ia terhubung dan terintegrasi<br>dengan alur kerja organisasi lintas fungsi, bukan sekadar fitur<br>aplikasi yang berdiri sendiri.|
|7. Adopsi dan Perilaku Organisasi<br>terhadap Informasi|Perubahan yang perlu dikelola adalah perubahan perilaku pencatatan,<br>pelaporan, dan penggunaan data oleh pengguna, bukan sekadar<br>penerimaan aplikasi baru secara umum.|



_Fokus MSI Pertemuan 4: Aspek 1 (Keselarasan Strategis) dan Aspek 3 (Dukungan Pengambilan Keputusan) menjadi penekanan utama, karena ruang lingkup dan tujuan SMART yang disusun diarahkan pada kebutuhan informasi dan pengambilan keputusan organisasi, bukan daftar fitur teknis semata._ 

### **Konsep Dasar** 

Materi ruang lingkup, tujuan SMART, dan deliverables pada pertemuan ini merupakan bagian dari Project Scope Management yang juga diajarkan di mata kuliah Manajemen Proyek Perangkat Lunak. Perbedaannya 

Universitas Negeri Yogyakarta - Halaman 2 

_Modul Praktikum MSI - PTF60234_ 

terletak pada apa yang dibatasi oleh scope tersebut. Pada manajemen proyek generik, scope biasanya berisi daftar fitur perangkat lunak yang akan dibangun. Pada praktikum Manajemen Sistem Informasi, scope yang disusun adalah scope kebutuhan informasi, yaitu data apa yang akan dikelola, keputusan organisasi apa yang akan didukung, dan laporan apa yang akan dihasilkan oleh sistem. Perbedaan penekanan ini penting karena scope yang hanya berisi daftar fitur teknis berisiko menghasilkan aplikasi yang berfungsi tetapi tidak benar-benar menjawab kebutuhan informasi organisasi, sebagaimana dibahas pada Pertemuan 1. 

#### **Scope Kebutuhan Informasi sebagai Batas Intervensi Sistem Informasi** 

Dalam Manajemen Sistem Informasi, scope tidak hanya menjawab sistem atau aplikasi apa yang akan dibuat. Scope terutama menjelaskan bagian dari kebutuhan informasi organisasi yang akan didukung oleh sistem. Karena itu, penetapan scope dimulai dari masalah organisasi dan kebutuhan penggunanya, kemudian diterjemahkan menjadi informasi yang diperlukan, proses yang menghasilkan atau menggunakan informasi tersebut, serta bentuk dukungan sistem informasi yang relevan. 

Pendekatan ini mencegah tim memilih teknologi secara langsung sebelum memahami persoalan yang hendak diselesaikan. Sebuah dashboard, aplikasi, atau basis data bukan tujuan proyek itu sendiri. Teknologi menjadi bagian dari scope apabila kontribusinya dapat dijelaskan dalam mendukung kebutuhan informasi, proses organisasi, atau keputusan yang ingin didukung. 

#### **Alur penetapan scope kebutuhan informasi** 

Masalah organisasi → dampak masalah → keputusan/proses terganggu → kebutuhan informasi → proses informasi → bentuk dukungan sistem informasi → batas scope. 

#### **Dimensi Kebutuhan Informasi** 

Kebutuhan informasi perlu dirumuskan secara operasional agar dapat digunakan untuk menetapkan batasbatas sistem informasi. Rumusan “pengguna membutuhkan data CQI” masih terlalu umum. Tim perlu menjelaskan informasi apa yang dibutuhkan, siapa yang membutuhkan, untuk keputusan atau aktivitas apa, dari mana informasi diperoleh, kapan informasi dibutuhkan, dan dalam bentuk apa informasi digunakan. 

|**Dimensi**|**Pertanyaan**|**Contoh OBE–CQI **|
|---|---|---|
|Informasi|Informasi apa yang diperlukan?|Status tindak lanjut rekomendasi<br>CQI.|
|Pengguna|Siapa yang menggunakan informasi?|Koordinator program studi.|
|Tujuan penggunaan|Untuk keputusan/aktivitas apa?|Menentukan rekomendasi yang<br>perlu segera ditindaklanjuti.|
|Sumber|Dari mana informasi berasal?|Dokumen/rekomendasi hasil<br>CQI dan pembaruan<br>penanggung jawab.|
|Waktu|Kapan informasi diperlukan?|Secara berkala selama semester.|
|Bentuk|Bagaimana informasi disajikan?|Daftar status, rekap, dan laporan<br>monitoring.|



#### **Scope Proses Informasi** 

Sistem informasi berhubungan dengan aliran informasi dalam suatu organisasi. Oleh karena itu, scope perlu menunjukkan bagian proses informasi yang akan didukung. Tim perlu melihat siapa yang menghasilkan data, siapa yang memperbaruinya, siapa yang memverifikasinya, siapa yang menggunakannya, dan bagaimana informasi tersebut menjadi dasar tindakan atau keputusan. 

Dalam kasus OBE–CQI, persoalan bukan sekadar tidak adanya tampilan dashboard. Persoalan yang perlu dianalisis adalah bagaimana rekomendasi dicatat, ditugaskan, statusnya diperbarui, dipantau, dan 

Universitas Negeri Yogyakarta - Halaman 3 

_Modul Praktikum MSI - PTF60234_ 

dilaporkan. Dengan melihat proses tersebut, tim dapat menentukan bagian mana yang benar-benar perlu didukung oleh sistem informasi dan bagian mana yang tetap menjadi tanggung jawab organisasi. 

|**Tahap proses informasi**|**Pertanyaan MSI**|**Contoh**|
|---|---|---|
|Input|Informasi awal apa yang masuk?|Rekomendasi CQI.|
|Pencatatan|Bagaimana informasi disimpan?|Catatan rekomendasi dan<br>penanggung jawab.|
|Pemutakhiran|Siapa dan bagaimana status<br>diperbarui?|Penanggung jawab memperbarui<br>status.|
|Monitoring|Siapa memantau dan apa yang<br>dilihat?|Koordinator melihat<br>rekomendasi yang belum<br>selesai.|
|Pelaporan|Informasi apa yang perlu diringkas?|Rekap status tindak lanjut per<br>mata kuliah.|
|Keputusan/tindakan|Bagaimana informasi digunakan?|Koordinator menentukan tindak<br>lanjut atau eskalasi.|



#### **Batas Sistem Informasi dan Batas Perangkat Lunak** 

Batas sistem informasi lebih luas daripada batas perangkat lunak. Sistem informasi mencakup keterkaitan antara manusia, proses, data/informasi, teknologi, dan aturan organisasi. Perangkat lunak hanya merupakan salah satu komponen teknologi yang dapat digunakan untuk mendukung sistem tersebut. Karena itu, proyek MSI tidak seharusnya menetapkan scope hanya berdasarkan daftar fitur perangkat lunak. 

Sebagai contoh, “membuat fitur notifikasi” merupakan rumusan teknis. Rumusan MSI yang lebih tepat adalah “menyediakan mekanisme pengingat kepada penanggung jawab ketika rekomendasi belum diperbarui sesuai dengan periode tindak lanjut”. Rumusan kedua menjelaskan kebutuhan informasi dan proses organisasi yang didukung, sedangkan teknologi notifikasi merupakan cara implementasinya. 

|**Rumusan**|**Orientasi**|**Keterangan**|
|---|---|---|
|Membuat dashboard CQI.|Teknologi/produk|Belum menjelaskan kebutuhan<br>informasi yang didukung.|
|Menampilkan status<br>rekomendasi CQI per mata<br>kuliah untuk monitoring<br>koordinator.|MSI|Menjelaskan informasi,<br>pengguna, dan tujuan<br>penggunaan.|
|Membuat fitur notifikasi.|Teknologi/produk|Belum menjelaskan siapa<br>menerima, kapan, dan untuk<br>proses apa.|
|Mengingatkan penanggung<br>jawab terhadap rekomendasi<br>yang belumdiperbarui.|MSI|Menjelaskan fungsi informasi<br>dalam proses tindak lanjut.|



#### **Menilai Relevansi Scope terhadap Nilai Organisasi** 

Tidak semua kebutuhan informasi harus dimasukkan ke dalam scope. Kebutuhan perlu dinilai berdasarkan relevansinya terhadap masalah prioritas serta nilai yang diharapkan organisasi. Informasi yang menarik tetapi tidak membantu proses atau keputusan utama dapat ditempatkan di luar scope. Prinsip ini membantu 

tim menjaga proyek tetap fokus tanpa membuatnya menjadi proyek pengembangan fitur yang terlalu banyak. 

#### **Pertanyaan penilaian relevansi** 

- Apakah informasi tersebut berkaitan langsung dengan masalah prioritas? 

- Siapa yang membutuhkan informasi tersebut? 

- Keputusan atau proses apa yang menjadi lebih baik jika informasi tersedia? 

Universitas Negeri Yogyakarta - Halaman 4 

_Modul Praktikum MSI - PTF60234_ 

- Apakah informasi tersebut benar-benar diperlukan atau hanya menarik untuk ditampilkan? 

- Apa konsekuensinya jika informasi tersebut tidak disediakan? 

#### **Tujuan SMART dalam Konteks MSI** 

SMART tetap digunakan dalam praktikum ini sebagai alat untuk membuat tujuan intervensi sistem informasi lebih terukur. Fokusnya bukan mengajarkan manajemen proyek, melainkan memastikan bahwa tujuan sistem informasi mencerminkan perubahan atau dukungan yang dibutuhkan oleh organisasi. Tujuan sebaiknya mencakup pengguna, informasi/proses yang didukung, ukuran keberhasilan, serta waktu pencapaian. 

|**Rumusan**|**Penilaian**|
|---|---|
|Membuat dashboard CQI.|Berorientasi produk teknologi; belum<br>menunjukkan kebutuhan organisasi.|
|Meningkatkan penggunaan dashboard.|Belum jelas perubahan, pengguna, ukuran, dan<br>waktunya.|
|Menyediakan mekanisme monitoring yang<br>memungkinkan koordinator mengetahui status<br>minimal 80% rekomendasi CQI dalam satu<br>semester.|Lebih relevan dengan MSI karena<br>menghubungkan informasi, pengguna, fungsi<br>monitoring, ukuran, dan waktu.|



#### **Contoh Penerjemahan Masalah menjadi Scope MSI** 

Contoh berikut menunjukkan bahwa scope tidak langsung ditetapkan sebagai nama aplikasi. Tim terlebih dahulu menelusuri kebutuhan organisasi sampai memperoleh batas intervensi sistem informasi. 

|**Tahap**|**Hasil analisis**|
|---|---|
|Masalah organisasi|Rekomendasi CQI sering tidak ditindaklanjuti.|
|Dampak|Koordinator kesulitan mengetahui rekomendasi mana yang sudah<br>atau belum ditindaklanjuti.|
|Kebutuhan keputusan|Koordinator perlu menentukan rekomendasi yang harus<br>diprioritaskan atau dieskalasi.|
|Kebutuhan informasi|Status rekomendasi, penanggung jawab, tenggat, dan riwayat<br>tindak lanjut.|
|Proses informasi|Pencatatan → penugasan → pembaruan status → monitoring →<br>pelaporan.|
|Scope MSI|Mendukung pencatatan, monitoring, pengingat, dan pelaporan<br>status tindak lanjut CQI.|
|Di luar scope|Mengubah proses penilaian mahasiswa dan membangun ulang<br>sistem akademik pusat.|



Setelah masalah prioritas ditetapkan, tim proyek perlu menerjemahkannya menjadi rencana kerja yang batasnya jelas. Ruang lingkup atau scope menetapkan apa yang akan dikerjakan dan, sama pentingnya, apa yang tidak akan dikerjakan dalam proyek. Laudon dan Laudon (2014) mengingatkan bahwa proyek sistem informasi yang gagal sering kali bukan karena teknologi yang dipilih salah, melainkan karena ruang lingkup proyek tidak pernah didefinisikan dengan jelas sejak awal. Tanpa batasan yang jelas, proyek rentan mengalami scope creep, yaitu bertambahnya cakupan pekerjaan secara bertahap tanpa perencanaan ulang yang memadai, sehingga waktu dan sumber daya yang terbatas menjadi tidak mencukupi. 

Tujuan proyek yang baik dirumuskan menggunakan kriteria SMART, yaitu specific (spesifik), measurable (terukur), achievable (dapat dicapai), relevant (relevan dengan masalah yang ditangani), dan time-bound (memiliki batas waktu). Pada kasus OBE-CQI, tujuan yang kurang spesifik, seperti meningkatkan penggunaan dashboard CQI, sulit diukur keberhasilannya. Tujuan yang lebih SMART misalnya, menyediakan fitur pengingat dan pelaporan tindak lanjut CQI yang dapat digunakan koordinator program 

Universitas Negeri Yogyakarta - Halaman 5 



<!-- Start of picture text -->
Masalah Tujuan Proyek Ruang Lingkup Deliverables<br>Prioritas (SMART) (In/Out-Scope) Utama<br>(Pertemuan 3)<br><!-- End of picture text -->

_Modul Praktikum MSI - PTF60234_ 

paling konkret dari keseluruhan alur ini, yaitu hasil nyata yang dapat diperiksa dan diserahkan pada akhir proyek. 

Panah yang menghubungkan setiap kotak menunjukkan bahwa alur ini bersifat satu arah namun tetap dapat ditinjau ulang: apabila pada tahap perumusan deliverables tim menyadari bahwa suatu target tidak realistis untuk dicapai, tim perlu kembali meninjau rumusan tujuan atau ruang lingkup pada kotak sebelumnya, bukan langsung mengubah deliverables secara sepihak. Alur inilah yang akan dipraktikkan secara berurutan pada bagian Langkah Kerja berikut, dengan Langkah Kerja 1 mengisi kotak kedua, Langkah Kerja 2 mengisi kotak ketiga, dan Langkah Kerja 3 mengisi kotak keempat. 

### **Alat dan Bahan** 

Template Project Scope Statement, dan hasil Dokumen Analisis Masalah dari Pertemuan 3. 

### **Langkah Kerja** 

1. **Merumuskan tujuan proyek (20 menit).** Berdasarkan pernyataan masalah prioritas pada Pertemuan 3, kelompok merumuskan tujuan proyek menggunakan kriteria SMART. 

2. **Menetapkan ruang lingkup (20 menit).** Kelompok menuliskan fungsi atau fitur sistem informasi yang termasuk dalam ruang lingkup proyek (in-scope) dan yang secara eksplisit tidak termasuk (out-of-scope), agar batasan pekerjaan jelas sejak awal. 

3. **Menyusun daftar deliverables (15 menit).** Kelompok menetapkan hasil-hasil nyata yang akan diserahkan pada akhir proyek beserta kriteria penerimaan masing-masing. 

4. **Mengidentifikasi asumsi dan batasan (10 menit).** Kelompok mendaftar asumsi yang diambil serta batasan yang memengaruhi proyek, misalnya keterbatasan waktu satu semester atau ketiadaan akses ke data organisasi yang sebenarnya. 

Universitas Negeri Yogyakarta - Halaman 7 

_Modul Praktikum MSI - PTF60234_ 

### **Lembar Kerja: Project Scope Statement** 

|**Bagian**|**Isian**|
|---|---|
|Tujuan Proyek (SMART)<br>__________|____________|
|In-Scope<br>__________|____________|
|Out-of-Scope<br>__________|____________|
|Daftar Deliverables dan Kriteria<br>Penerimaan<br>__________|____________|
|Asumsi<br>__________|____________|
|Batasan (Constraints)<br>__________|____________|



### **Contoh Kertas Kerja Terisi (Ilustrasi Berbasis Kasus OBE-CQI)** 

|**Bagian**|**Isian**|
|---|---|
|Tujuan Proyek (SMART)|Menyediakan fitur pengingat dan pelaporan tindak lanjut CQI yang<br>dapat digunakan koordinator program studi untuk memantau status<br>tindak lanjut minimal 80 persen rekomendasi dalam satu semester<br>akademik|
|In-Scope|Fitur pencatatan status tindak lanjut rekomendasi CQI, notifikasi<br>pengingat berkala kepada dosen dan koordinator, laporan ringkas status<br>tindak lanjut per mata kuliah|
|Out-of-Scope|Perubahan pada mekanisme penilaian mahasiswa, integrasi dengan<br>sistem akademik pusat, pengembangan modul CPL-CPMK baru|
|Daftar Deliverables dan Kriteria<br>Penerimaan|Prototipe fitur pelaporan tindak lanjut (dapat mencatat minimal 3 status:<br>belum, sedang, selesai ditindaklanjuti); dokumen alur notifikasi<br>pengingat; laporan uji coba prototipe oleh minimal 2 pengguna simulasi|
|Asumsi|Data ketercapaian CPMK yang digunakan sebagai simulasi dianggap<br>valid dan representatif|
|Batasan (Constraints)|Proyek dikerjakan dalam satu semester dengan sumber daya terbatas<br>pada anggota kelompok; tidak ada akses ke data mahasiswa yang<br>sesungguhnya|



Universitas Negeri Yogyakarta - Halaman 8 

_Modul Praktikum MSI - PTF60234_ 

### **Asesmen** 

Teknik penilaian pada pertemuan ini mencakup Kehadiran/Keaktifan dan Proyek, dengan kontribusi terhadap CPMK 2 sebesar total 12,5% pada Komponen Penilaian RPS, yang terdiri atas 2,5% Kehadiran dan 10,0% Team Based Project. 

|**Teknik Penilaian**|**Deskripsi**|
|---|---|
|Kehadiran/Keaktifan|Dinilai dari partisipasi mahasiswa selama proses perumusan tujuan dan<br>diskusi penetapan ruang lingkup.|
|Proyek|Project Scope Statement yang telah diisi lengkap, termasuk tujuan SMART,<br>batasan scope, deliverables, asumsi, dan batasan proyek.|



### **Rubrik Penilaian Artefak/Lembar Kerja** 

|**Aspek**|**Kurang**|**Cukup**|**Baik**|**Sangat Baik**|
|---|---|---|---|---|
|Kejelasan Tujuan<br>(SMART)|Tidak memenuhi<br>kriteria SMART|Sebagian kriteria<br>SMART<br>terpenuhi|SMART secara<br>umum terpenuhi|SMART lengkap<br>dan terukur jelas|
|Kejelasan Batasan Scope|Tidak ada batasan<br>yang jelas|Batasan ambigu|Batasan cukup<br>jelas|Batasan jelas dan<br>konsisten dengan<br>tujuan|
|Kelengkapan Deliverables|Tidak lengkap|Sebagian<br>deliverables<br>teridentifikasi|Deliverables<br>utama<br>teridentifikasi|Deliverables<br>lengkap dengan<br>kriteria<br>penerimaan|



### **Rubrik Penilaian Laporan Praktikum (Baku - Seluruh Pertemuan)** 

|**Aspek**|**Kurang**|**Cukup**|**Baik**|**Sangat Baik**|
|---|---|---|---|---|
|Kelengkapan Struktur<br>Laporan|Kurang dari 4 dari<br>7 bagian terisi|5-6 bagian terisi|7 bagian terisi<br>lengkap|7 bagian terisi<br>lengkap dan rapi|
|Kualitas Uraian<br>Pelaksanaan Kegiatan|Uraian minim,<br>hanya menyalin<br>langkah kerja|Uraian deskriptif,<br>kurang<br>menjelaskan<br>alasan keputusan|Menjelaskan<br>proses dan alasan<br>keputusan dengan<br>cukup jelas|Menjelaskan<br>proses, alasan,<br>dan pertimbangan<br>keputusan secara<br>rinci|
|Ketepatan Analisis Kendala<br>dan Solusi|Kendala tidak<br>diidentifikasi|Kendala<br>disebutkan tanpa<br>solusi jelas|Kendala dan<br>solusi cukup<br>relevan|Kendala dan<br>solusi relevan<br>serta<br>menunjukkan<br>pemecahan<br>masalah aktif|
|Kedalaman Refleksi<br>Pembelajaran|Tidak ada refleksi<br>atau sekadar<br>mengulang materi|Refleksi ada<br>namun dangkal|Refleksi<br>mengaitkan<br>pengalaman<br>dengan konsep|Refleksi<br>mendalam,<br>mengaitkan<br>pengalaman,<br>konsep, dan<br>penerapan ke<br>depan|



Universitas Negeri Yogyakarta - Halaman 9 

_Modul Praktikum MSI - PTF60234_ 

**Tindak Lanjut** 

Project Scope Statement ini menjadi dasar penyusunan struktur tim dan pembagian peran pada Pertemuan 5. 

Universitas Negeri Yogyakarta - Halaman 10 

_Modul Praktikum MSI - PTF60234_ 

### **Format Laporan Praktikum Mingguan: Pertemuan 4** 

|**Identitas Laporan**|**Isian**|
|---|---|
|Nama Kelompok|______|
|Anggota (NIM/Nama)|______|
|Pertemuan ke-|4|
|Tanggal Pelaksanaan|______|
|Organisasi/Kasus yang Digunakan|______|



#### **2. Tujuan Kegiatan** 

Mahasiswa mampu menyusun ruang lingkup, tujuan, dan deliverables proyek sistem informasi berdasarkan masalah prioritas yang telah ditetapkan pada pertemuan sebelumnya. 

#### **3. Uraian Pelaksanaan Kegiatan** 

_(Diisi mahasiswa: jelaskan bagaimana kelompok merumuskan tujuan proyek hingga memenuhi kriteria SMART, pertimbangan yang digunakan saat menetapkan batas in-scope dan out-of-scope, serta alasan penetapan setiap deliverable.)_ 

#### **4. Hasil/Artefak Praktikum** 

_(Project Scope Statement terisi lengkap: dilampirkan.)_ 

#### **5. Kendala dan Solusi** 

_(Diisi mahasiswa: contoh: kesulitan membatasi scope agar tidak terlalu luas untuk dikerjakan dalam satu semester, diselesaikan dengan mengacu kembali pada pernyataan masalah prioritas Pertemuan 3.)_ 

#### **6. Refleksi Pembelajaran** 

_(Diisi mahasiswa: apa yang dipelajari kelompok tentang pentingnya membatasi ruang lingkup proyek sejak awal, dan risiko yang mungkin muncul bila batasan tidak jelas.)_ 

#### **7. Kesimpulan** 

_(Diisi mahasiswa: ringkasan Project Scope Statement dan kesiapan melanjutkan ke penyusunan struktur tim pada Pertemuan 5.)_ 

### **Referensi** 

Laudon, K. C., & Laudon, J. P. (2014). Management information systems: Managing the digital firm (13th ed.). Pearson Education. 

Universitas Negeri Yogyakarta - Halaman 11 

