# Information Architecture

> **Versi:** 1.0
> **Status:** Draft
> **Terakhir diperbarui:** Juli 2026

---

# Pendahuluan

Dokumen ini menjelaskan struktur informasi (Information Architecture) pada website Hazz Farm.

Tujuan utama Information Architecture adalah memastikan seluruh informasi tersusun secara logis, mudah dipahami, dan memberikan pengalaman navigasi yang sederhana bagi pengguna.

Seluruh struktur halaman, menu, serta hubungan antarhalaman harus mengacu pada dokumen ini.

---

# Tujuan

Information Architecture Hazz Farm dirancang untuk:

* Mempermudah pengguna menemukan informasi.
* Menampilkan identitas perusahaan secara profesional.
* Mendukung pengembangan website dalam jangka panjang.
* Menjadi fondasi bagi penambahan fitur tanpa mengubah struktur utama.
* Mendukung pengalaman pengguna pada desktop maupun mobile.

---

# Struktur Website

```text
/
├── Home
├── Company
│   ├── Tentang Hazz Farm
│   ├── Founder
│   ├── Visi & Misi
│   ├── Filosofi
│   ├── Perjalanan Hazz Farm
│   └── Nilai Perusahaan
│
├── Products
│   ├── Semua Produk
│   ├── Detail Produk
│   └── Kategori Produk
│
├── Technology
│   ├── Smart Farming
│   ├── Internet of Things (IoT)
│   ├── Artificial Intelligence
│   ├── Roadmap
│   └── Waitlist
│
├── Dashboard
│   ├── Monitoring Lahan
│   ├── Cuaca
│   ├── Grafik Sensor
│   └── Statistik
│
├── Insights
│   ├── Artikel
│   ├── Kategori
│   └── Detail Artikel
│
├── Contact
│
├── Privacy Policy
└── Terms of Service
```

---

# Struktur Navigasi

Menu utama website terdiri dari:

* Home
* Company
* Products
* Technology
* Dashboard
* Insights
* Contact

Di sisi kanan navbar:

* Search
* Dark Mode
* AI Assistant
* Hubungi Kami

---

# Hierarki Informasi

Prioritas informasi pada website adalah:

1. Identitas Hazz Farm.
2. Visi dan teknologi.
3. Produk.
4. Dashboard.
5. Artikel.
6. Kontak.

Website harus memberikan kesan bahwa Hazz Farm adalah perusahaan agritech yang memiliki produk pertanian, bukan sekadar toko hasil panen.

---

# Struktur Halaman

## Home

Berfungsi sebagai pintu masuk utama.

Urutan section:

1. Hero
2. Company Overview
3. Featured Products
4. Technology Preview
5. Journey Timeline
6. Dashboard Preview
7. Latest Insights
8. Call to Action
9. Footer

---

## Company

Berisi seluruh informasi mengenai perusahaan.

Struktur:

* Tentang Hazz Farm
* Founder
* Visi
* Misi
* Filosofi
* Nilai Perusahaan
* Timeline Perjalanan

---

## Products

Menampilkan seluruh produk pertanian.

Setiap halaman produk terdiri dari:

* Nama Produk
* Foto
* Deskripsi
* Ketersediaan
* Informasi Budidaya
* Data Sensor (Simulasi)
* FAQ
* Hubungi melalui WhatsApp

---

## Technology

Menjelaskan arah pengembangan teknologi.

Konten:

* Smart Farming
* Internet of Things
* Artificial Intelligence
* Roadmap
* Coming Soon
* Waitlist

---

## Dashboard

Menampilkan data pertanian.

Versi awal:

* Data simulasi.

Versi berikutnya:

* Data IoT secara real-time.

---

## Insights

Media edukasi.

Konten:

* Artikel
* Tutorial
* Teknologi
* Pertanian
* Artificial Intelligence
* Internet of Things

---

## Contact

Media komunikasi.

Berisi:

* Formulir
* WhatsApp
* Email
* Lokasi
* FAQ

---

# Struktur Footer

Footer dibagi menjadi empat kelompok.

## Company

* Tentang
* Visi
* Misi
* Perjalanan

---

## Products

* Semua Produk
* Katalog

---

## Resources

* Insights
* Dokumentasi
* Roadmap

---

## Contact

* WhatsApp
* Email
* Lokasi
* Media Sosial

---

# Hubungan Antarhalaman

Home menjadi pusat navigasi menuju seluruh halaman utama.

Hubungan halaman dirancang sebagai berikut:

```text
Home
│
├── Company
│
├── Products
│   └── Detail Produk
│
├── Technology
│
├── Dashboard
│
├── Insights
│   └── Detail Artikel
│
└── Contact
```

Setiap halaman harus menyediakan navigasi yang jelas menuju halaman lain yang relevan.

---

# Sistem Pencarian

Pencarian dapat menemukan:

* Produk.
* Artikel.
* Halaman.
* FAQ.

Hasil pencarian dikelompokkan berdasarkan kategori agar mudah dipahami.

---

# AI Assistant

AI Assistant dapat diakses dari seluruh halaman.

Fungsi:

* Menjawab pertanyaan.
* Memberikan informasi produk.
* Menjelaskan perusahaan.
* Memberikan rekomendasi artikel.
* Mengarahkan pengguna ke halaman yang sesuai.

---

# Navigasi Mobile

Pada perangkat mobile:

* Menu utama menggunakan drawer.
* Search tetap tersedia.
* AI Assistant tetap dapat diakses.
* Tombol WhatsApp tetap terlihat.

Seluruh pengalaman pengguna harus tetap sederhana dan mudah digunakan.

---

# Prinsip Information Architecture

Seluruh struktur website harus mengikuti prinsip berikut:

* Mudah dipahami.
* Konsisten.
* Skalabel.
* Berorientasi pengguna.
* Berorientasi teknologi.
* Meminimalkan jumlah klik untuk menemukan informasi.

---

# Prinsip Navigasi

Setiap halaman harus mampu menjawab tiga pertanyaan berikut.

1. Di mana saya berada?
2. Ke mana saya dapat pergi?
3. Bagaimana saya kembali ke halaman sebelumnya?

Apabila pengguna dapat menjawab ketiga pertanyaan tersebut tanpa kebingungan, maka struktur navigasi dianggap berhasil.

---

# Arah Pengembangan

Struktur Information Architecture dirancang agar tetap relevan ketika Hazz Farm berkembang menjadi platform agritech.

Fitur seperti Dashboard IoT, Artificial Intelligence, Farm Management, maupun Platform Smart Farming dapat ditambahkan tanpa mengubah struktur utama website.

Dengan pendekatan ini, website Hazz Farm dapat berkembang secara bertahap tanpa kehilangan konsistensi pengalaman pengguna.
