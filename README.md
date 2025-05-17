# ☕ Coffee Sales Analytics Dashboard

> **Comprehensive Dashboard & Data Analysis for Coffee Sales**

---

## 📊 Overview

Coffee Sales Analytics Dashboard adalah project analisis data penjualan kopi dari beberapa negara, pelanggan, dan tipe kopi, dengan sumber data nyata dan dashboard interaktif berbasis Excel. Proyek ini tidak hanya menampilkan laporan penjualan, namun juga mengungkap insight bisnis seperti pelanggan terbaik, performa produk, dan distribusi geografis penjualan.

---

## 🗂️ Dataset Structure

Berikut adalah file dan sheet utama:

| File Name                    | Sheet Name        | Description                                      |
|------------------------------|-------------------|--------------------------------------------------|
| `Raw Data.xlsx`              | orders            | Data transaksi penjualan kopi                    |
|                              | customers         | Data detail pelanggan                            |
|                              | products          | Data katalog produk kopi                         |
| `Dashboard Coffee Sales.xlsx` | Dashboard         | Dashboard visualisasi penjualan (Pivot, Chart)   |
|                              | TotalSales        | Rekap penjualan per tahun/bulan/kopi             |
|                              | CountryBarChart   | Penjualan per negara                             |
|                              | Top5Customers     | 5 pelanggan terbaik                              |
|                              | orders/customers/products | Cleaned data untuk analisis/pivot            |

---

## ✨ Fitur Utama

- **Dashboard Interaktif**: Visualisasi penjualan kopi per waktu, negara, dan tipe kopi
- **Analisis Top Customer**: Siapa pelanggan dengan volume terbesar?
- **Distribusi Geografis**: Penjualan per negara (United States, Ireland, United Kingdom)
- **Segmentasi Produk**: Analisis Arabica, Robusta, Liberica, Excelsa
- **Analisis Profit Produk**: Berdasarkan margin dan size
- **Loyalty Card Analytics**: Perbandingan pelanggan loyal vs umum
- **Data Cleaning**: Data telah dibersihkan untuk keperluan analisis lanjutan

---

## 🚀 Quick Start

1. **Clone Repo & Download Files**
   ```sh
   
   git clone https://github.com/habstrakT808/Simple-Excel-Dashboard-for-Coffe-Sales.git

2. **Buka file:**

- `Dashboard Coffee Sales.xlsx` untuk eksplorasi dashboard
- `Raw Data.xlsx` untuk analisis data mentah atau custom

3. **Eksplorasi Dashboard**

- Gunakan filter pada Pivot Table (tahun/bulan/kopi/customer)
- Lihat chart bar penjualan per negara
- Temukan pelanggan & produk terlaris


## 📈 Sample Dashboard Preview

  ![image](https://github.com/user-attachments/assets/21da0e0a-6d58-491f-a8bb-b3ac168d1f5b)

## 📝 Data Fields

### Orders

- Order ID, Order Date, Customer ID, Product ID, Quantity, Customer Name, Email, Country
- Coffee Type, Roast Type, Size, Unit Price, Sales

### Customers

- Customer ID, Name, Email, Phone, Address, Country, Loyalty Card

### Products

- Product ID, Coffee Type, Roast Type, Size, Unit Price, Price per 100g, Profit


## 💡 Business Insights

- **Top 5 Customers**: Don Flintiff, Nealson Cuttler, Terri Farra, Brenn Dundredge, Allis Wilmore
- **Penjualan Terbesar**: United States ($35,639+), Ireland, United Kingdom
- **Produk Favorite**: Arabica, Robusta mendominasi
- **Tren Musiman**: Penjualan puncak di bulan tertentu (lihat dashboard)
- **Loyalty Program**: Pengaruh kartu loyalti terhadap repeat order


## 🛠️ Tools & Teknologi

- **Microsoft Excel** (Pivot Table, Slicer, Chart)
- Data Cleaning & Preparation (manual/Excel)
- [Opsional] Python (untuk advanced analysis)


## 🤝 Kontribusi

Feel free to fork, improve, atau gunakan dataset ini untuk belajar visualisasi dan analitik data retail/FMCG.


## 📜 License

MIT License — bebas digunakan untuk pembelajaran dan riset.

## 👤 Author

- Hafiyan Al Muqaffi Umary

> **Happy Analyzing & Brewing Business Insights! ☕📊**
