# 🗓️ Pertemuan Kelima - Aplikasi CRUD dengan Java Swing dan JDBC PostgreSQL

## 📚 Topik Utama

Aplikasi CRUD dengan Java Swing dan JDBC PostgreSQL

## 📑 Daftar Isi

- [Java Swing Tiket](https://github.com/fauziaeka/TugasPBO_TM05/blob/main/FrameTiket.java)
- [Tiket DB](https://github.com/fauziaeka/TugasPBO_TM05/blob/main/TiketDB.java)
- Kesimpulan

# 🖥️ CRUD dengan Java Swing dan JDBC

Java Swing adalah sebuah toolkit atau pustaka untuk membangun antarmuka pengguna grafis (GUI) di dalam aplikasi Java.

## 🛠️ Komponen 
Java Swing memiliki berbagai komponen utama yang digunakan untuk membangun antarmuka pengguna grafis (GUI). Berikut adalah beberapa komponen yang digunakan dalam aplikasi Swing 'Data Tiket':

1. **JFrame** : Jendela utama aplikasi. Berfungsi untuk menyediakan area yang menempatkan komponen GUI seperti tombol, label, dan panel. 

2. **JPanel** : Tempat untuk mengelompokkan komponen GUI. Berfungsi untuk membantu dalam pengelolaan tata letak dan organisasi komponen. 

3. **JButton** : Tombol yang dapat diklik. Berfungsi untuk mengaktifkan tindakan tertentu ketika diklik. 

4. **JLabel** : Label teks untuk menampilkan informasi. Berfungsi untuk menampilkan teks statis atau ikon. 

5. **JTextField** : Kolom input teks untuk input data. Pada bagian ini memungkinkan kita memasukkan satu baris teks saja. 

6. **JList** : Daftar yang menampilkan sejumlah item. Bagian ini memungkinkan kita memilih satu atau beberapa item dari daftar. 

---

# 🗃️ Tiket DB

Class ini digunakan untuk mengonversi hasil dari query SQL (dalam bentuk ResultSet) menjadi model tabel yang dapat digunakan oleh komponen GUI di Java Swing, yaitu JTable.  

## 🚀 Langkah-langkah:  

1. Buat class baru pada NetBeans dengan nama 'PBO_PertemuanKelima'. 

2. Sambungkan PostgreSQL 'PBO_PertemuanKeempat' dan NetBeans 'PBO_PertemuanKelima' agar data yang telah kita sambungkan sebelumnya dapat terbaca oleh sistem. Selain itu, hal ini juga memungkinkan program dapat berjalan dengan baik.  

3. Masukkan codingan untuk menu Insert, Update, Delete, dan Exit.   

4. Tahapan eksekusi:  
   - Masukkan data yang ingin ditambahkan kemudian tekan button Insert untuk menambahkan data. 
   - Masukkan Id data yang ingin diubah, masukkan data yang baru kemudian tekan button Update untuk memperbarui data.  
   - Masukkan data yang ingin dihapus kemudian tekan button Delete.  
   - Tekan button Exit untuk keluar dari halaman.  

## 🔧 Fungsi Tombol : 

➕ **INSERT (Menambahkan Data)**
  
  Button ini berfungsi untuk menambahkan data pada 'Data Tiket'. Sebagai pengguna, kita diminta untuk mengisi informasi mengenai Id tiket, nama event, tanggal, harga, jumlah, dan lokasi event. Setelah dimasukkan, kita bisa menekan button Insert. Jika berhasil, akan muncul pesan 'Data Berhasil disimpan'. 

🔄 **UPDATE (Memperbarui Data)**
  
  Button ini berfungsi untuk memperbarui data pada 'Data Tiket'. Pertama-tama masukkan Id tiket yang ingin diubah, kemudian masukkan informasi mengenai Id tiket, nama event, tanggal, harga, jumlah, dan lokasi event baru. Jika berhasil, sistem akan mencetak pemberitahuan bahwa 'Data berhasil diupdate'. 

❌ **DELETE (Menghapus Data)**
   
  Button ini berfungsi untuk menghapus data pada 'Data Tiket'. Pengguna bisa memasukkan data yang ingin dihapus atau bisa juga dengan mengeklik data yang ingin dihapus pada kolom list. Kemudian akan muncul pesan konfirmasi apakah pengguna ingin menghapus data atau tidak. Jika 'iya' data otomatis akan dihapus dan jika 'tidak' maka data akan batal dihapus. 

🚪 **EXIT (Keluar)**
  
  Saat ingin keluar dari halaman antarmuka, kita bisa menekan button Exit. Sistem otomatis akan keluar dari halaman yang menampilkan antarmuka dengan kembali ke halaman awal.  

---

## 🎯 Kesimpulan

Aplikasi CRUD dengan Java Swing dan JDBC PostgreSQL merupakan salah satu contoh aplikasi Java yang cukup efisien. 
Java Swing memuat antarmuka yang memudahkan pengguna untuk melakukan semua operasi dasar pada data. 
JDBC juga memungkinkan kita untuk berinteraksi dengan database secara langsung sehingga kita memiliki kontrol penuh atas query dan pemrosesan data yang dilakukan.
