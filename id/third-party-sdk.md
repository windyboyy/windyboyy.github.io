# Daftar SDK Pihak Ketiga

**Terakhir Diperbarui: 5 Januari 2026**

Aplikasi ini mengintegrasikan SDK berikut:

## 1. SDK Sistem Apple

### 1.1 Foundation
- **Penyedia**: Apple Inc.
- **Fungsi**: Dukungan framework dasar, menyediakan tipe data dan koleksi dasar
- **Informasi Dikumpulkan**: Tidak ada

### 1.2 SwiftUI
- **Penyedia**: Apple Inc.
- **Fungsi**: Framework antarmuka pengguna, membangun antarmuka aplikasi
- **Informasi Dikumpulkan**: Tidak ada

### 1.3 UIKit
- **Penyedia**: Apple Inc.
- **Fungsi**: Dukungan komponen UI, mendapatkan informasi perangkat
- **Informasi Dikumpulkan**: Nama perangkat, versi sistem, status baterai

### 1.4 Network
- **Penyedia**: Apple Inc.
- **Fungsi**: Dukungan komunikasi jaringan, koneksi TCP/UDP, pemantauan status jaringan
- **Informasi Dikumpulkan**: Status koneksi jaringan

### 1.5 CoreTelephony
- **Penyedia**: Apple Inc.
- **Fungsi**: Mendapatkan informasi jaringan seluler
- **Informasi Dikumpulkan**: Jenis jaringan seluler (2G/3G/4G/5G)

### 1.6 NetworkExtension
- **Penyedia**: Apple Inc.
- **Fungsi**: Dukungan ekstensi jaringan (dicadangkan untuk fitur capture paket)
- **Informasi Dikumpulkan**: Tidak ada

### 1.7 Security
- **Penyedia**: Apple Inc.
- **Fungsi**: Dukungan framework keamanan
- **Informasi Dikumpulkan**: Tidak ada

### 1.8 Darwin
- **Penyedia**: Apple Inc.
- **Fungsi**: Panggilan sistem tingkat rendah, digunakan untuk Ping, Traceroute, dll.
- **Informasi Dikumpulkan**: Tidak ada

### 1.9 dnssd
- **Penyedia**: Apple Inc.
- **Fungsi**: Penemuan layanan DNS, digunakan untuk fitur kueri DNS
- **Informasi Dikumpulkan**: Tidak ada

## 2. SDK Komersial Pihak Ketiga

Aplikasi ini saat ini tidak mengintegrasikan SDK komersial pihak ketiga apa pun, termasuk namun tidak terbatas pada:
- Tidak ada SDK iklan
- Tidak ada SDK analitik
- Tidak ada SDK berbagi sosial
- Tidak ada SDK notifikasi push
- Tidak ada SDK pembayaran

## 3. Layanan Jaringan Pihak Ketiga

### 3.1 Layanan Kueri IP NetEase
- **URL Layanan**: mail.163.com
- **Penyedia**: NetEase, Inc.
- **Fungsi**: Mendapatkan alamat IP publik dan geolokasi perangkat saat ini
- **Data Terkirim**: Permintaan jaringan (secara otomatis membawa IP publik)
- **Data Dikembalikan**: Alamat IP publik, negara, provinsi, kota, ISP

### 3.2 Layanan Kueri IP Bilibili
- **URL Layanan**: api.live.bilibili.com
- **Penyedia**: Bilibili Inc.
- **Fungsi**: Mengkueri lokasi geografis IP yang ditentukan
- **Data Terkirim**: Alamat IP untuk dikueri
- **Data Dikembalikan**: Negara, provinsi, kota, ISP, koordinat

### 3.3 Layanan Kueri ASN ipinfo.io
- **URL Layanan**: api.ipinfo.io
- **Penyedia**: IPinfo Inc. (AS)
- **Fungsi**: Mengkueri nomor AS (Nomor Sistem Otonom) IP
- **Data Terkirim**: Alamat IP untuk dikueri
- **Data Dikembalikan**: Nomor AS, nama AS, negara

## 4. Catatan

1. Aplikasi ini hanya menggunakan SDK sistem resmi Apple untuk memastikan keamanan dan keandalan.
2. Jika SDK pihak ketiga baru diintegrasikan di masa depan, kami akan memperbarui daftar ini dan memberi tahu Anda segera.
3. Semua penggunaan SDK mengikuti prinsip kebutuhan minimum.
