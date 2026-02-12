# Daftar Informasi Pribadi yang Dikumpulkan

**Terakhir Diperbarui: 5 Januari 2026**

Sesuai dengan GDPR Pasal 13, CCPA, dan hukum dan peraturan terkait lainnya, kami menjelaskan informasi pribadi yang dikumpulkan oleh aplikasi ini:

> **PENTING**: Semua informasi di bawah ini hanya disimpan secara lokal di perangkat Anda dan tidak akan diunggah ke server mana pun.

## 1. Informasi Perangkat (Dibaca secara lokal untuk tampilan)

### 1.1 Informasi Perangkat Dasar
- **Jenis Informasi**: Nama perangkat, model perangkat, versi sistem
- **Tujuan Pengumpulan**: Tampilan di halaman "Info Perangkat"
- **Dasar Hukum**: Pelaksanaan kontrak (menyediakan layanan yang Anda minta)
- **Metode Pengumpulan**: Dibaca melalui API sistem
- **API yang Digunakan**: UIDevice.current
- **Periode Retensi**: Selama penggunaan aplikasi

### 1.2 Pengidentifikasi Perangkat
- **Jenis Informasi**: Pengidentifikasi model (mis., iPhone17,1)
- **Tujuan Pengumpulan**: Mengidentifikasi model perangkat untuk tampilan
- **Dasar Hukum**: Pelaksanaan kontrak
- **Metode Pengumpulan**: Melalui panggilan sistem utsname
- **Catatan**: Bukan pengidentifikasi iklan (IDFA), bukan pengidentifikasi unik perangkat (IDFV)

### 1.3 Informasi Status Perangkat
- **Jenis Informasi**: Level baterai, status baterai, ruang disk, penggunaan memori
- **Tujuan Pengumpulan**: Tampilan di halaman "Info Perangkat"
- **Dasar Hukum**: Pelaksanaan kontrak
- **Metode Pengumpulan**: Dibaca melalui API sistem

## 2. Informasi Jaringan (Dibaca secara lokal untuk diagnostik)

### 2.1 Alamat IP
- **Jenis Informasi**: Alamat IPv4 lokal, alamat IPv6 lokal
- **Tujuan Pengumpulan**: Diagnostik jaringan, tampilan info perangkat
- **Dasar Hukum**: Pelaksanaan kontrak
- **Metode Pengumpulan**: Melalui panggilan sistem getifaddrs

### 2.2 Status Jaringan
- **Jenis Informasi**: Jenis jaringan (WiFi/Seluler/Tidak ada jaringan)
- **Tujuan Pengumpulan**: Menentukan lingkungan jaringan, diagnostik jaringan
- **Dasar Hukum**: Pelaksanaan kontrak
- **Metode Pengumpulan**: Melalui listener NWPathMonitor

### 2.3 Jenis Jaringan Seluler
- **Jenis Informasi**: 2G/3G/4G/5G
- **Tujuan Pengumpulan**: Menampilkan jenis jaringan terperinci
- **Dasar Hukum**: Pelaksanaan kontrak
- **Metode Pengumpulan**: Melalui framework CoreTelephony

## 3. Catatan Riwayat (Disimpan secara lokal)

### 3.1 Riwayat Target Probe
- **Jenis Informasi**: Alamat target Ping/DNS/TCP/UDP/Trace/HTTP
- **Tujuan Pengumpulan**: Nyaman bagi pengguna untuk dengan cepat memilih target umum
- **Dasar Hukum**: Kepentingan yang sah (meningkatkan pengalaman pengguna)
- **Metode Penyimpanan**: Penyimpanan lokal UserDefaults
- **Batas Penyimpanan**: Hingga 10 catatan per kategori
- **Periode Retensi**: Sampai pengguna menghapus atau menghapus instalasi aplikasi

### 3.2 Riwayat Kueri IP
- **Jenis Informasi**: Alamat IP yang dikueri
- **Tujuan Pengumpulan**: Nyaman bagi pengguna untuk melihat riwayat kueri
- **Dasar Hukum**: Kepentingan yang sah
- **Metode Penyimpanan**: Penyimpanan lokal UserDefaults

### 3.3 Riwayat Uji Koneksi/Diagnosis Cepat
- **Jenis Informasi**: Alamat target uji
- **Tujuan Pengumpulan**: Nyaman bagi pengguna untuk mengulangi tes
- **Dasar Hukum**: Kepentingan yang sah
- **Metode Penyimpanan**: Penyimpanan lokal UserDefaults

## 4. Pengidentifikasi Pengguna (Dibuat secara lokal)

### 4.1 ID Tamu
- **Jenis Informasi**: String yang dibuat secara acak
- **Tujuan Pengumpulan**: Identifikasi pengguna lokal
- **Dasar Hukum**: Pelaksanaan kontrak
- **Metode Penyimpanan**: Penyimpanan lokal UserDefaults
- **Catatan**: Dibuat sepenuhnya secara acak, tidak terkait dengan informasi identitas pribadi apa pun

## 5. Permintaan Jaringan (Diperlukan untuk fungsionalitas) - Transfer Data Internasional

### 5.1 Layanan Kueri IP NetEase
- **URL Layanan**: mail.163.com
- **Penyedia**: NetEase, Inc. (Tiongkok)
- **Data Terkirim**: Permintaan jaringan (secara otomatis membawa IP publik)
- **Data Diterima**: Alamat IP publik, negara, provinsi, kota, ISP
- **Tujuan**: Mendapatkan IP publik dan informasi geolokasi perangkat saat ini
- **Dasar Hukum**: Pelaksanaan kontrak

### 5.2 Layanan Kueri IP Bilibili
- **URL Layanan**: api.live.bilibili.com
- **Penyedia**: Bilibili Inc. (Tiongkok)
- **Data Terkirim**: Alamat IP untuk dikueri
- **Data Diterima**: Negara, provinsi, kota, ISP, koordinat
- **Tujuan**: Mengkueri lokasi geografis IP yang ditentukan
- **Dasar Hukum**: Pelaksanaan kontrak

### 5.3 Layanan Kueri ASN ipinfo.io
- **URL Layanan**: api.ipinfo.io
- **Penyedia**: IPinfo Inc. (AS)
- **Data Terkirim**: Alamat IP untuk dikueri
- **Data Diterima**: Nomor AS, nama AS, negara
- **Tujuan**: Mengkueri nomor AS (Nomor Sistem Otonom) IP
- **Dasar Hukum**: Pelaksanaan kontrak
- **Catatan Transfer Internasional**: Data dapat ditransfer ke AS; layanan mematuhi GDPR

## 6. Cara Menghapus Informasi

- **Riwayat**: Hapus secara manual di setiap halaman fitur
- **Semua Data**: Hapus instalasi aplikasi untuk menghapus semua data lokal
- **Jalankan Hak Data**: Hubungi zjccc5889@gmail.com
