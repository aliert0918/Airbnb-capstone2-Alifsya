# Airbnb Listings Bangkok Analysis
Capstone Project 2 - Alifsya Salam Student-ID (JCDSBDGPM-10-001)

Proyek ini menganalisis dataset Airbnb di Bangkok untuk memberikan wawasan strategis bagi host dan manajemen Airbnb dalam mengoptimalkan performa listing, penetapan harga, dan ekspansi pasar.

---

## Latar Belakang

Bangkok merupakan salah satu pasar Airbnb paling dinamis di Asia Tenggara. Sebelum pandemi, Thailand menerima hampir 40 juta wisatawan internasional (2019), menjadikan Bangkok kota yang sangat kompetitif untuk bisnis penyewaan properti.

Dinamika pasar saat ini menunjukkan pergeseran tren, di mana terjadi peningkatan segmen *extended stay* (long-term) yang didorong oleh *digital nomad* dan kebijakan visa jangka panjang. Persaingan antara host baru dan lama sangat ketat, di mana listing yang sukses bukan hanya yang termurah, melainkan yang mampu menyelaraskan:
*   Lokasi Strategis (Akses transportasi & wisata lokal).
*   Harga Kompetitif.
*   Kualitas Fasilitas & Pengalaman Tamu.

Analisis ini diperlukan untuk memahami faktor-faktor apa saja yang menopang industri ini agar host dapat memaksimalkan pendapatan dan Airbnb dapat menjaga standar kualitas.

---

## Pernyataan Masalah

Dengan ribuan listing yang tersebar di wilayah Bangkok yang luas, Airbnb menghadapi tantangan dalam memonitor kualitas dan perkembangan properti. Berikut adalah masalah utama yang diidentifikasi:

1.  **Ketimpangan Distribusi Properti:** Adanya area dengan permintaan tinggi namun kekurangan supply listing, atau sebaliknya (oversupply).
2.  **Kesulitan Penetapan Harga (Pricing):** Host sering kesulitan menentukan harga yang kompetitif—tidak terlalu murah (hilang margin) dan tidak terlalu mahal (hilang okupansi)—tanpa data pasar yang jelas.
3.  **Kualitas & Kredibilitas Listing:** Masih banyaknya listing dengan performa rendah (*Low Performer*) yang dapat menurunkan kepercayaan calon tamu terhadap platform.
4.  **Anomali Data:** Ditemukan listing dengan harga tidak wajar atau minimum stay yang tidak realistis (misal: 1.120 malam) yang perlu dibersihkan.

---

## Tujuan Analisis

Analisis ini bertujuan untuk memberikan solusi berbasis data (data-driven solution) bagi stakeholders terkait:

### 1. Optimasi Kualitas Listing
*   Mengidentifikasi karakteristik dari **Top Performer** vs **Low Performer**.
*   Memberikan rekomendasi bagi host untuk meningkatkan status listing mereka melalui perbaikan fasilitas dan layanan.

### 2. Strategi Penetapan Harga ("Sweet Spot")
*   Menentukan kisaran harga optimal berdasarkan wilayah dan tipe kamar (Entire home, Private room, dll).
*   Menemukan titik temu antara jumlah ulasan tinggi dan ketersediaan (availability) yang sehat.

### 3. Segmentasi Pasar & Wilayah
*   Memetakan wilayah (neighbourhood) berdasarkan karakteristiknya: *Premium*, *Balanced*, *Budget-Friendly*, atau *Emerging*.
*   Mengidentifikasi peluang ekspansi di area yang memiliki permintaan tinggi namun kompetisi masih rendah.

### 4. Rekomendasi Bisnis
*   Memberikan saran strategis untuk **Host** (cara menaikkan okupansi) dan **Manajemen Airbnb** (fokus area marketing dan standar operasional).

---

## Stakeholders

Analisis ini ditujukan untuk mendukung keputusan bagi:
*   **Property Operations Manager:** Memantau kualitas listing.
*   **Brand Marketing Manager:** Meningkatkan brand awareness lewat listing terbaik.
*   **Business Development Lead:** Ekspansi mitra lokal.
*   **Host Partner:** Pemilik properti yang ingin meningkatkan revenue.

---

## Gambaran Data

Dataset mencakup informasi listing Airbnb Bangkok dengan fitur utama:
*   `neighbourhood`: Lokasi wilayah listing.
*   `room_type`: Jenis ruangan (Entire home, Private room, dll).
*   `price`: Harga sewa per malam.
*   `number_of_reviews` & `last_review`: Indikator aktivitas dan popularitas.
*   `availability_365`: Ketersediaan listing dalam setahun.

## Tableau Dashboard Link

* Link Dashboard Tableau: [Dashboards Airbnb Bangkok](https://public.tableau.com/app/profile/alifsya.salam/viz/AirbnbListingsBangkok_17637292382570/Dashboard3)
---
