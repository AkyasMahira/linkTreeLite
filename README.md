# LinkTree Lite

**LinkTree Lite** adalah halaman profil personal sederhana dan ringan yang berfungsi sebagai pusat tautan (landing page) untuk media sosial, portofolio, dan kontak Anda. Project ini didesain sebagai alternatif *open-source* dari layanan seperti Linktree, memberikan Anda kendali penuh atas desain dan data tanpa biaya berlangganan.

## 🚀 Fitur Utama

* **Ringan & Cepat**: Dibangun dengan HTML, CSS, dan JavaScript murni tanpa framework berat, menjamin waktu muat yang instan.
* **Desain Responsif**: Tampilan menyesuaikan dengan sempurna di perangkat mobile (HP), tablet, maupun desktop.
* **Mudah Kustomisasi**: Cukup edit file HTML untuk mengubah tautan dan file CSS untuk mengubah tema warna.
* **Efek Interaktif**: Dilengkapi dengan animasi halus saat kursor diarahkan ke tombol (hover effects) menggunakan CSS dan JavaScript.
* **Privasi Terjaga**: Tidak ada pelacak (tracker) pihak ketiga; data pengunjung adalah milik Anda sepenuhnya.

## 🛠 Teknologi yang Digunakan

Project ini dibangun menggunakan standar web modern:

* **HTML5**: Untuk struktur semantik halaman dan tautan.
* **CSS3**: Untuk styling, layout responsif, dan animasi.
* **JavaScript (Vanilla)**: Untuk interaktivitas elemen (jika ada fitur seperti share button atau validasi sederhana).

## 📂 Susunan Project

Struktur direktori project ini adalah sebagai berikut:

```text
linkTreeLite/
├── img/
│   ├── ava.jpeg        # Foto profil utama
│   ├── logo.png        # Logo atau ikon tambahan
│   └── 3m.jpg          # Gambar pendukung/background
├── index.html          # File utama halaman web
├── script.js           # Logika JavaScript
├── style.css           # Kode gaya/tampilan (styling)
└── README.md           # Dokumentasi project

```

## 📋 Prasyarat Instalasi

Anda tidak memerlukan instalasi software khusus seperti Node.js atau PHP. Cukup pastikan Anda memiliki:

* **Web Browser Modern** (Chrome, Firefox, Safari, atau Edge).
* **Text Editor** (VS Code, Sublime Text, atau Notepad) untuk mengedit konten.

## ⚙️ Cara Penggunaan

### 1. Menjalankan di Komputer Lokal

1. **Clone Repository** (atau download ZIP):
```bash
git clone [https://github.com/akyasmahira/linktreelite.git](https://github.com/akyasmahira/linktreelite.git)

```


2. Buka folder project.
3. Klik dua kali file `index.html` untuk membukanya di browser.

### 2. Mengubah Foto & Tautan

1. Buka `index.html` menggunakan text editor.
2. **Ganti Foto Profil**: Cari tag `<img>` dan ubah `src`-nya ke file foto Anda (simpan foto baru di folder `img/`).
```html
<img src="img/foto-baru.jpg" alt="Foto Profil Saya" class="profile-pic">

```


3. **Ubah Tautan**: Cari elemen `<a>` dan sesuaikan `href` serta teksnya.
```html
<a href="[https://instagram.com/username](https://instagram.com/username)" target="_blank">Instagram</a>

```



### 3. Deploy ke Internet (Gratis)

Cara termudah untuk mengonlinekan project ini adalah menggunakan **GitHub Pages**:

1. Upload kode ini ke repository GitHub Anda.
2. Masuk ke **Settings** > **Pages**.
3. Pada bagian **Source**, pilih branch `main` dan folder `root`.
4. Klik **Save**. Website Anda akan aktif di `https://username.github.io/linktreelite`.

## 🤝 Kontribusi

Kontribusi selalu terbuka! Jika Anda ingin menambahkan fitur baru (misalnya mode gelap/terang) atau memperbaiki bug:

1. Fork repository ini.
2. Buat branch fitur baru (`git checkout -b fitur-keren`).
3. Commit perubahan Anda (`git commit -m 'Menambahkan fitur Dark Mode'`).
4. Push ke branch tersebut (`git push origin fitur-keren`).
5. Buat Pull Request.
