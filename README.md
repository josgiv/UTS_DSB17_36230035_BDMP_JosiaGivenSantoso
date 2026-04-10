# UTS_DSB17_36230035_BDMP_JosiaGivenSantoso

Repositori ini berisi implementasi proyek Ujian Tengah Semester untuk mata kuliah Big Data Management and Processing (DSB17). Proyek ini berfokus pada simulasi pengelolaan dan pemrosesan Data Lake menggunakan dataset riwayat transaksi.

## Deskripsi Proyek

Secara garis besar, dokumentasi program pada proyek ini mencakup pemrosesan data berikut:

1. Arsitektur Data Lake: Memodelkan aliran data dari fase mentah hingga siap dianalisis melalui konsep arsitektur zona (Transition, RAW, Trusted, dan Refined Zone).
2. Pengujian Kualitas Data: Melakukan pembersihan dan deteksi anomali pada dataset seperti duplikasi rekaman, nilai nominal yang tidak valid atau kosong, serta mendeteksi nilai ekstrem.
3. Pemrosesan Big Data: Memanfaatkan kerangka kerja Apache Spark (PySpark) untuk mengelola partisi data, memastikan toleransi kegagalan proses, dan melakukan agregasi analitik dasar.
4. Tata Kelola dan Keamanan Data: Meliputi penyamaran pelindungan identitas, simulasi akses berbasis peran (RBAC), penelusuran riwayat transformasi (Data Lineage), beserta pelaporan dan pemantauan kondisi metrik analitik.

## Persyaratan Mutlak

Sistem yang digunakan untuk menjalankan lingkungan proyek ini wajib memenuhi persyaratan perangkat lunak di bawah ini:
- Python 3.12
- Java Development Kit (JDK) versi 17
