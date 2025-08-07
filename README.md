# ECC-NIN_MangroveChain_-Denny-Risnandar-_-Batch-9-
MangroveChain Conservation Analytics

Repositori ini dibuat oleh Kelompok 1 untuk memenuhi soal ujian (Task 2) yang diberikan untuk menguasai sistem manajemen basis data relasional objek / PostgreSQL dan pemrograman Python dalam konteks MANGROVECHAIN CONSERVATION ANALYTICS. Dengan semangat inovasi dan kolaborasi, kami berupaya menghasilkan karya yang tidak hanya memenuhi standar, tetapi juga mencerminkan dedikasi kami untuk mendukung pembangunan sistem inovatif yang menggabungkan teknologi blockchain dengan upaya konservasi mangrove di seluruh Indonesia.

---
### 👥 Kelompok 1

| Nama            | No Absen       | Kelompok |
|-----------------|----------------|----------|
    
---
## 📜 BAB 1 PENDAHULUAN

### 1.1 Latar Belakang
Hutan mangrove merupakan salah satu ekosistem pesisir paling penting di dunia, terutama dalam mitigasi perubahan iklim melalui kemampuan tinggi menyerap karbon (blue carbon). Indonesia memiliki hutan mangrove terluas secara global, sekitar 3,7 juta hektare atau 23% dari total mangrove dunia. Ekosistem ini berperan besar dalam menahan abrasi, melindungi pesisir, mendukung keanekaragaman hayati, dan menjadi penyimpan karbon yang sangat efektif dengan potensi hingga 1.000 ton karbon per hektare.

Namun, keberadaan mangrove menghadapi ancaman serius. Sejak tahun 1980, sekitar 40% hutan mangrove Indonesia telah rusak akibat konversi lahan menjadi tambak, polusi limbah industri, dan tekanan aktivitas manusia seperti penebangan untuk kayu bakar. Di sisi lain, perubahan iklim, termasuk kenaikan permukaan laut, memperburuk kondisi ekosistem ini. Kurangnya kesadaran masyarakat dan keterbatasan pendanaan juga menjadi hambatan besar dalam upaya konservasi.

Sementara itu, pasar karbon global membuka peluang ekonomi melalui perdagangan kredit karbon, di mana setiap 1 kredit mewakili 1 ton CO₂ yang berhasil diserap. Hutan mangrove yang direhabilitasi dapat menghasilkan kredit karbon bernilai ekonomi tinggi, sehingga menjadi insentif bagi upaya konservasi. Namun, pengelolaan data dan transaksi kredit karbon menghadapi tantangan besar, seperti kurangnya transparansi, risiko manipulasi data, double counting, serta biaya validasi yang tinggi.

MangroveChain adalah sistem inovatif yang menggabungkan teknologi blockchain dengan upaya konservasi mangrove di seluruh Indonesia. Analisis ini menyediakan wawasan mendalam tentang 30 proyek konservasi dari Aceh hingga Papua, melacak kepatuhan regulasi, dampak biodiversitas, keterlibatan masyarakat, dan transaksi kredit karbon yang tercatat dalam ledger blockchain yang tidak dapat diubah.

Sistem ini mengintegrasikan 14 dimensi data termasuk pemantauan lingkungan, catatan kepemilikan lahan, sumber pendanaan, dan transaksi smart contract untuk menciptakan pandangan komprehensif tentang efektivitas konservasi. 

Ada 5 analisis yang menjadi dasar latar belakang masalah, diantaranya :

1. **Analisis Efektivitas Regulasi & Dampak Biodiversitas** : 

Tim konservasi menemukan adanya perbedaan yang cukup besar dalam hasil pemantauan biodiversitas pada berbagai proyek konservasi. Sebagai contoh, di Kalimantan Timur, proyek yang telah mendapatkan izin resmi menunjukkan kerapatan pohon hingga 40% lebih tinggi dibandingkan proyek yang izinnya masih menunggu persetujuan. Namun, situasinya berbeda di Jawa, di mana kualitas air tetap buruk meskipun izin proyek sudah disetujui. Analisis ini bertujuan mengungkap pola sistemik bagaimana kerangka regulasi dan struktur kepemilikan lahan mempengaruhi hasil konservasi. 

2. **Optimalisasi Pendanaan Berbasis Blockchain.** 

Investor berdampak (impact investors) kini semakin menuntut bukti terverifikasi mengenai efektivitas program dalam mengurangi emisi karbon serta integritas data yang disajikan. Hal ini didorong oleh tingginya risiko penyelewengan dana, kurangnya transparansi, dan sulitnya mengukur dampak secara akurat dalam model pendanaan konvensional. Sebuah konsorsium investor hijau bahkan telah mengalokasikan dana sebesar 15 juta dolar AS untuk proyek konservasi mangrove. Namun, dana ini hanya akan disalurkan jika terdapat jaminan bahwa proyek tersebut memenuhi persyaratan ketat, antara lain :

   - Perlindungan data yang kuat melalui enkripsi blockchain.
     
   - Persetujuan masyarakat yang terdokumentasi
     
   - Bukti efisiensi penyerapan karbon
   

3. **Prediksi Kinerja Proyek Berbasis Keterlibatan Masyarakat**

Keberhasilan suatu proyek pembangunan tidak hanya bergantung pada ketersediaan sumber daya dan perencanaan teknis, tetapi juga pada tingkat keterlibatan masyarakat dalam proses pelaksanaannya. Studi empiris menunjukkan bahwa proyek yang memiliki partisipasi masyarakat tinggi cenderung lebih berkelanjutan dalam jangka panjang. Data historis memperlihatkan bahwa proyek dengan tingkat keterlibatan masyarakat di atas 30% memiliki peluang keberlanjutan hingga 75% lebih tinggi setelah tiga tahun dibandingkan proyek dengan partisipasi rendah.
  
4. **Analisis Risiko Hukum Multi-Dimensi**.

Pengelolaan proyek dengan kompleksitas tinggi sering kali menghadapi tantangan hukum yang dapat mempengaruhi keberlanjutan dan keberhasilan implementasi. Risiko hukum ini muncul dari berbagai faktor, diantaranya :

   - Perizinan yang tertunda, batas lahan yang tidak jelas.
  
   - kepemilikan lahan masyarakat adat yang sulit diverifikasi.
  
   - Kualitas lingkungan yang buruk serta kebutuhan restorasi yang intensif


5. **Analisis Jaringan Blockchain dalam Konservasi**

implementasi teknologi ini memerlukan pemahaman mendalam mengenai pola berbagi data dalam jaringan blockchain.  CTO (Chief Technology Officer) harus mampu menganalisis berbagai tipe data yang terlibat, seperti :

   - Distribusi tipe data (Geografis/Personal/Transaksi) per wilayah : Melihat sebaran berbagai jenis data di setiap wilayah. Misalnya, di satu wilayah lebih banyak data lokasi (geografis), sedangkan di wilayah lain lebih banyak data pribadi atau data transaksi.

   - Korelasi antara level akses dengan volume transaksi karbon : Melihat tingkat keterbukaan data (misalnya data terbuka untuk umum atau hanya untuk pihak tertentu) berpengaruh terhadap jumlah transaksi karbon yang terjadi. Contohnya, apakah jika data lebih terbuka, jumlah transaksi karbon jadi lebih banyak?

   - Pola temporal penerbitan izin vs aktivitas blockchain : Mempelajari bagaimana waktu penerbitan izin (misalnya izin konservasi) berkaitan dengan aktivitas di blockchain. Misalnya, apakah aktivitas blockchain meningkat setiap kali izin baru diterbitkan?

   Hasil analisis awal menunjukkan bahwa proyek dengan data geografis terbuka memiliki volume transaksi 2,5 kali lebih tinggi dibandingkan proyek yang datanya terbatas. Fakta ini menunjukkan pentingnya analisis jaringan blockchain untuk menentukan strategi distribusi data, pengelolaan izin, serta pengembangan arsitektur sistem yang efektif dan berkelanjutan dalam mendukung konservasi.

---
### 📜 1.2 Identifikasi Masalah

Bedasarkan latar belakang masalah yang telah di uraiakan sebelumnya dapat disimpulkan bahwa Rumusan masalah dari penelitian  MangroveChain Conservation Analytics Integrasi Teknologi Blockchain dengan Pelestarian Ekosistem Mangrove di Indonesia ini adalah sebagai berikut: 

1. Efektivitas Regulasi Konservasi MangroveChain & Dampak Biodiversitas.

Pemerintah Indonesia telah banyak mengeluarkan Regulasi yang digunakan sebagai pedoman untuk menyusun Strategi Nasional Pengelolaan Ekosistem Mangrove di Indonesia diantaranya
1. Tecantum dalam UUD 1945 Pasar 33 ayat 3
2. 15 dalam Undang - undang
3. 13 dalam peraturan Pemerintah
4. 3 dalam Keputusan Presiden
5. 1 dalam Perpres 

Peraturan - peraturan ini di buat dalam rangka pelestarian mengrove indoensia. Namun dari sekian banyak pedoman dalam konservasi tersebut dan kaitanya dengan konservai mangrove berbahasis blockchain dapat di simpulkan permasalahan yang terjadi diantaranya :
 1. Status izin proyek konservasi mangrove berpengaruh terhadap peningkatan biodiversitas / Keanekaragaman hayati, misalnya kualitas air dan kerapatan pohon.
 2. Pengelolaan konservasi mangrove yang di miliki oleh negara, swasta, atau masyarakat mempengaruhi keanekaragaman spesies ? (perbedaan pengelolaan). 
 3. Konservasi mangrove dengan batas wilayah lahan yang jelas secara hukum menimbulkan hasil ekologis yang lebih baik ? 

Analisis ini menggunakan penggabungan data status izin dari data / table 010Regulatory_Permits, data kepemilikan lahan dari 011Land_Tenure_Records, dan metrik ekologis dari 012Biodiversity_Monitoring.


2. Optimalisasi Pendanaan Berbasis Blockchain

Konservasi Mangrove ini tidak bisa mengandalkan perananan pemerintah saja dalam hal payung hukum, tetapi perlu adanya Kemitraan dan Pendanaan Berkelanjutan untuk menumbuhkan konservasi mangrove. salah satu upaya ini adalah konservasi mangrove berbasis Blokchain yang dapat menciptakan transparansi, efisiensi, dan kepercayaan dalam pengelolaan keuangan untuk para investor. 

BNI Sekuritas dalam mendukung Koperasi Jaga Wana Segara (Jawara) dalam melakukan upaya konservasi hutan mangrove di Arboretum Mangrove Konservasi Laguna Segara Anakan. PLN Indonesia Power (PLN IP) turut serta melalui program pemberdayaan mitra binaan konservasi mangrove Batu Lumbang di Bali.

Investor membutuhkan bukti terverifikasi tentang dampak lingkungan dan integritas data serta jaminan bahwa dana yang telah di gelontorkan tersebut akan mendukung proyek dengan jaminan Perlindungan data blockchain yang kuat (enkripsi tinggi), Persetujuan masyarakat yang terdokumentasi, serta bukti dari Efisiensi penyerapan karbon.

Sehingga permasalahan terseut dapat disimpulkan ; 
1. Penyerapan CO2 per juta Rupiah yang telah diinvestasikan harus dapat di hitung.
2. Verifikasi kepatuhan tata kelola data blockchain apakah telah sesuai dengan regulasi yang ada, baik secara hukum dan Tekhnologi informasi.
3. Proyek - proyek tersebut harus di Identifikasi sehingga proyek yang di jalankan harus berkinerja terbaik yang memenuhi semua kriteria.

Analisis ini memerlukan penggabungan data kepatuhan blockchain (013Blockchain_Data_Compliance), informasi pendanaan (007Funding_Sources), dan dampak lingkungan (009Environmental_Impact).


3. Prediksi Kinerja Proyek Berbasis Keterlibatan Masyarakat

Keterlibatan masyarakat memiliki peran krusial dalam konservasi mangrove. Masyarakat yang tinggal di sekitar area mangrove memiliki pengetahuan lokal dan ketergantungan ekonomi pada ekosistem ini. Partisipasi mereka, baik dalam bentuk kegiatan konservasi maupun pemanfaatan berkelanjutan, sangat penting untuk keberhasilan jangka panjang program konservasi. Sehingga perlu adanya pemberdayaan dan managemen dalam mengelola lingkungan sekitar. Maka dapat di simpulkan permasalahan yang akan muncul dalam keterilibatan masyarakat diantaranya :

1. Frekuensi kegiatan masyarakat (Lokakarya/Konsultasi/Pelatihan) pada proyek konservasi tersebut. semakain sering maka akan semakin baik, pemahaman masyarakat akan meningkat.
2. Distribusi manfaat ekonomi kepada masyarakat local harus merata dan tersampaikan kepada seluruh masyarakat.
3. Tingkat partisipasi relatif terhadap ukuran komunitas.
4. Kaitan antara kegiatan yang melibatkan masyarakat dan peningkatan biodiversitas sekitar mangrove.

Analisis ini memerlukan penggabungan data keterlibatan masyarakat (014Community_Engagement), anggota masyarakat (004Community_Members), dan catatan konservasi (001Mangrove_Conservation_Records).

4. Analisis Risiko Hukum Multi-Dimensi

Setiap proyek harus melalui proses mengevaluasi potensi risiko hukum yang berasal dari berbagai sumber atau aspek dalam suatu kegiatan atau organisasi. Ini melibatkan identifikasi, analisis, dan penilaian risiko hukum yang mungkin muncul dari berbagai peraturan, kontrak, perikatan, dan tindakan yang terkait dengan kegiatan tersebut. 

Beberapa tempat konservasi memiliki Kasus kepemilikan lahan missal di kawasan hutan mangrove di Kabupaten Maros, Sulawesi Selatan, ditemukan sejumlah sertifikat hak milik (SHM) atas lahan mangrove seluas 6 hectare, dan beberapa kasus lainnya terkait konservasi mangrove.

Proyek konservasi berbasis blokchain harus dapat terhindar dari aspek risiko hukum di kemudian hari. Sehingga permasalah yang timbul dapat di simpulkan :
1. Belum adanya Sistem scoring dengan bobot berbeda untuk setiap kriteria risiko pada setiap proyek konservasi. dengan adanya scoring tersebut memudahkan para pemangku kepentingan dalam pengelolaan dan pengambilan keputusan.
2. Klasifikasi setiap proyek menjadi risiko rendah, sedang, tinggi.
3. Belum adanya Analisis geospasial untuk pola sebaran risiko setiap proyek yang dapat memudahkan lam mengambil keputusan yang lebih baik berdasarkan informasi geografis. 

Analisis ini memerlukan penggabungan data izin (010Regulatory_Permits), kepemilikan lahan (011Land_Tenure_Records), biodiversitas (012Biodiversity_Monitoring), dan aktivitas (006Conservation_Activities)

5. Analisis Jaringan Blockchain dalam Konservasi

Penerapan teknologi blockchain untuk meningkatkan transparansi, keamanan, dan efisiensi dalam upaya pelestarian lingkungan dan sumber daya alam. Blockchain dapat digunakan untuk melacak asal-usul produk, memantau aktivitas konservasi, dan mengelola data terkait lingkungan secara lebih efektif. 

Terkait manfaat yang banyak tersebut, tekhnologi baru ini perlu adaptasi dan penerimaan pada setiap proyek yang ada. Isu lainnya adalah jaringan blockchain harus mampu menangani volume data yang besar dan terus meningkat seiring dengan bertambahnya pengguna dan transaksi. masalah keakuratan dan integritas data, terutama dalam konteks konservasi yang membutuhkan data yang valid dan tidak dapat diubah untuk melacak asal-usul dan keberlanjutan sumber daya. Penyimpanan data dalam bentuk terenkripsi, namun tetap ada kekhawatiran tentang potensi penyalahgunaan data atau pelanggaran privasi. kompleksitas analisis data blockchain itu sendiri, yang membutuhkan keahlian khusus dan alat analisis yang tepat. 

Sehingga permasalahan ini dapat di simpulkan diantaranya :
1. Perlu dilakukan Analisis jaringan hubungan antara node data
2. Pola Penyampaian informasi kepada para stakeholder3.
3. Optimasi desain smart contract

Analisis ini memerlukan penggabungan data blockchain (013Blockchain_Data_Compliance), transaksi (002Blockchain_Transactions), dan izin (010Regulatory_Permits)

