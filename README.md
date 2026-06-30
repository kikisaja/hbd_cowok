# 🎂 Website Ucapan Ulang Tahun Interaktif (Andi's Birthday)

Sebuah proyek website statis sederhana dan interaktif yang dibuat khusus untuk memberikan ucapan selamat ulang tahun kepada **Andi**. Website ini dirancang dengan tampilan modern berbasis *Glassmorphism* dan dilengkapi dengan fitur kejutan efek emoticon serta nama **Kiki** yang terbang di latar belakang.

---

## 🚀 Fitur Utama
* **Desain Modern (Glassmorphism):** Tampilan kartu ucapan transparan efek kaca yang estetis dengan perpaduan warna maskulin (*deep blue* & *cyan*).
* **Efek Kartu 3D Flip:** Kartu ucapan dapat diklik untuk membalikkan posisi (buka/tutup) dengan animasi 3D yang halus.
* **Kejutan Interaktif:** Ketika tombol "Buka Kejutan" diklik, latar belakang akan otomatis dibanjiri oleh kombinasi emoticon pesta dan nama **Kiki** yang terbang ke atas.
* **Efisien & Aman:** Kode dioptimalkan untuk performa yang ringan dan bebas dari kebocoran memori (*memory leak avoidance*) dengan menghapus elemen DOM secara otomatis setelah animasi selesai.

---

## 🛠️ Teknologi yang Digunakan
Proyek ini dibuat murni menggunakan teknologi web dasar tanpa bantuan *framework* atau *library* pihak ketiga:
* **HTML5:** Untuk menyusun struktur semantik komponen kartu ucapan.
* **CSS3:** Untuk mengatur tata letak (*Flexbox*), variabel warna (`:root`), efek kaca (*backdrop-filter*), serta animasi 3D (*perspective* & *keyframes*).
* **JavaScript (Vanilla JS):** Untuk logika interaktif pembalikan kartu, deteksi kontainer otomatis, dan memproduksi partikel terbang secara dinamis.

---

## 📂 Struktur File
Proyek ini dipisahkan secara disiplin ke dalam 3 file utama sesuai dengan aturan penulisan kode yang baik:
```text
├── index.html      # Struktur utama halaman dan konten teks ucapan
├── style.css       # Mengatur keindahan visual, warna, dan animasi background
└── script.js       # Logika interaktif kartu dan generator efek terbang Kiki
