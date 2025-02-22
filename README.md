# Supermarket-Sales-Dashboard
Membuat dashboard interaktif untuk memvisualisasikan tren penjualan supermarket berdasarkan produk, lokasi, dan tipe pelanggan. Dashboard ini memudahkan dalam menganalisis kinerja penjualan dengan filters dinamis berdasarkan metode pembayaran, periode, dan produk.


# 📊 **Supermarket Sales Analysis** 

* **Dashboard Interaktif**: [Dashboard Link](https://lookerstudio.google.com/reporting/ddf5d061-66b8-456d-9f42-91248f3e7182) 🔗
* **Dataset**: [Dataset Link](https://docs.google.com/spreadsheets/d/1xc1tU_cZNO8Yi7ziAA8jZjvxHn2-SdXQvWkkCjsRwSY/edit?usp=sharing) 🔗

## 🎯 **Tujuan Proyek**
Proyek ini bertujuan untuk memberikan wawasan yang lebih dalam mengenai **kinerja penjualan supermarket** pada tahun 2019. Dashboard ini menyajikan **analisis penjualan** berdasarkan beberapa dimensi penting, seperti **produk**, **lokasi**, **jenis pelanggan**, dan **metode pembayaran**. Visualisasi ini mempermudah dalam memahami tren penjualan, performa berdasarkan wilayah, serta distribusi jenis pelanggan dan metode pembayaran.

## 🔑 **Fitur Utama**

### 1. **Trendline by Revenue** 📈
Menyajikan **tren penjualan sepanjang waktu** dengan **line chart**. Data dapat difilter berdasarkan **tanggal**, **cabang**, dan **kategori produk**.
- Visualisasi ini memperlihatkan fluktuasi penjualan dengan jelas, lengkap dengan **target penjualan** dan **minimum revenue** .
- Pengguna dapat dengan mudah melihat bagaimana penjualan berkinerja sepanjang periode dan membandingkannya dengan target yang telah ditetapkan.

### 2. **Sales Performance by Product Line, City, and Gender** 🏙️👩‍🦱👨‍🦱
Visualisasi **bar chart** yang memperlihatkan performa penjualan berdasarkan **kota**, **produk**, dan **jenis kelamin** pelanggan.
- **Insight Kota**: Menyajikan kota mana yang memberikan kontribusi terbesar terhadap penjualan.
- **Analisis Gender**: Membandingkan penjualan produk antar segmen pasar berdasarkan **gender** pelanggan.
- **Performa Berdasarkan Produk**: Membantu memahami produk mana yang terlaris di berbagai kota dan kategori pelanggan.

### 3. **Customer Type Distribution by Gender** ♀️♂️
Diagram **bar stacked** yang menunjukkan **distribusi pelanggan** berdasarkan **jenis kelamin** dan **tipe pelanggan** (anggota vs normal).
- Tabel ini memperlihatkan jumlah pelanggan berdasarkan **gender** (pria dan wanita) serta **status keanggotaan** (anggota vs normal).
- Dari diagram ini, kita bisa melihat bahwa pelanggan **wanita** memiliki jumlah **anggota** yang lebih banyak dibandingkan **pria**, tetapi pria lebih banyak berbelanja dalam kategori **pelanggan biasa (non-member)**.

### 4. **Payment Method Distribution** 💳💵📲
Diagram **pie chart** yang menggambarkan **persentase metode pembayaran** yang digunakan oleh pelanggan.
- **Persentase Penggunaan Metode Pembayaran**: Menampilkan proporsi antara penggunaan **ewallet**, **cash**, dan **credit card**.
- **Insight Dominasi Pembayaran**: Mengungkapkan metode pembayaran yang paling banyak digunakan di supermarket, yang sangat berguna untuk strategi pembayaran dan analisis transaksi.

## 🔧 **Fitur Interaktif**

- **Filters:** Pengguna dapat memilih rentang waktu, cabang, dan kategori produk yang ingin dianalisis untuk memperkecil fokus data yang ditampilkan pada dashboard.
- **Metrics Summary:** Pada bagian atas dashboard, terdapat metrik kunci yang menunjukkan:
  - **Revenue**: Total pendapatan yang dihasilkan.
  - **Record Count**: Jumlah transaksi yang terjadi.
  - **Quantity**: Total jumlah produk yang terjual.
- Pengguna dapat dengan mudah mendapatkan **gambaran singkat** mengenai kinerja penjualan sepanjang periode yang dipilih.
  
## 🖥️ **Penggunaan Dashboard**
Dashboard ini dirancang untuk membantu **tim manajemen**, **analisis penjualan**, dan dan **stakeholders** lainnya dalam memahami lebih baik pola-pola dalam data penjualan. Dengan informasi yang ditampilkan, mereka dapat **mengambil keputusan strategis** dalam hal **strategi penjualan**, **kampanye promosi**, dan **perencanaan ke depan** berdasarkan **metode pembayaran**, **jenis pelanggan**, dan **kinerja di berbagai kota**.

## 📝 **Kesimpulan**
Proyek ini menyajikan **dashboard interaktif** yang tidak hanya memperlihatkan data secara visual, tetapi juga memberikan pemahaman mendalam mengenai **perilaku pelanggan** dan **kinerja penjualan supermarket** di tahun 2019. Dengan fitur-fitur yang dapat disesuaikan, dashboard ini memungkinkan pengguna untuk mengeksplorasi berbagai aspek bisnis dan mengambil keputusan berbasis data yang lebih efektif.

## 🛠️ **Tools yang Digunakan:**

- **Google Looker Studio** untuk visualisasi dan dashboard interaktif.
- **Google Colab** untuk **preprocessing data**, termasuk perbaikan **kesalahan penulisan** (typo), penyesuaian **tipe data**, dan pembersihan data lainnya agar dataset lebih konsisten dan siap digunakan dalam analisis lebih lanjut.
- **Google Sheets** untuk pengolahan data dan sumber data utama.
