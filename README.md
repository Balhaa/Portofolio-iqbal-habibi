# Portofolio Iqbal Habibi

Portfolio web interaktif dan responsif yang menampilkan proyek-proyek Web Developer dari Universitas Muhammadiyah Purwokerto.

![Portfolio Preview](https://placehold.co/1200x630/0f172a/6366f1?text=Portfolio+-+Iqbal+Habibi)

---

## 🚀 Fitur Utama

- **Desain Modern & Futuristik** — Dark mode dengan aksen neon indigo/cyan/violet, efek glassmorphism, dan animasi space background yang smooth
- **100% Responsive** — Tampilan optimal dari HP kecil hingga monitor ultrawide
- **Auto Metadata Fetching** — Preview proyek otomatis dari URL menggunakan Microlink API
- **Live Demo dalam Iframe** — Preview proyek langsung di modal tanpa keluar halaman
- **Filter & Search Real-time** — Cari proyek berdasarkan nama, kategori, atau teknologi
- **Tech Stack Otomatis** — Skill bars dan tech icons dihitung otomatis dari tags proyek
- **Animasi Luar Angkasa** — Bintang twinkling, nebula melayang, dan meteor yang melesat (CSS-only, no canvas)
- **Single File** — Hanya 1 file `index.html`, langsung jalan di browser tanpa instalasi

---

## 🛠️ Tech Stack

- **HTML5** — Struktur markup
- **Tailwind CSS** (via CDN) — Styling utility-first
- **Vanilla JavaScript** — Interaktivitas tanpa framework
- **AOS Animation** — Scroll reveal effects
- **Microlink API** — Auto-fetch metadata dari URL proyek

---

## 📂 Struktur Proyek

```text
Portofolio-iqbal-habibi/
├── index.html          # Portfolio lengkap dalam 1 file
├── README.md           # Dokumentasi ini
└── .vscode/            # VS Code settings (opsional)
```

---

## 💼 Proyek yang Ditampilkan

| No | Nama Proyek | Kategori | Demo |
|----|-------------|----------|------|
| 1 | Dashboard Okupansi Tempat Tidur | Web App | [Live](https://balhaa.github.io/Dashboard-Okupansi-Tempat-Tidur/) |
| 2 | POS Kasir | Web App | [Live](https://penjualan-sgp.site.je/login.php) |
| 3 | To-Do List App | Web App | [Live](https://to-do-list-amber-phi-46.vercel.app/) |
| 4 | Game Edukasi Kelas 5-6 | Web App | [Live](https://game-edukasi-kelas-5-6.vercel.app/) |
| 5 | Web Pembelajaran SD | Web App | [Live](https://web-pembelajaran-sd.vercel.app/) |
| 6 | Edukasi Pembelajaran | Web App | [Live](https://edukasi-pembelajaran.vercel.app/) |
| 7 | UMKM Gunungsari | Landing Page | [Live](https://umkm-gunungsari-pml.vercel.app/) |
| 8 | Tailweb | Landing Page | [Live](https://tailweb-sepia.vercel.app/) |

---

## 🎨 Cara Menambahkan Proyek Baru

Tambahkan objek baru ke array `projects` di dalam `index.html`:

```javascript
{
  title: "Nama Proyek Baru",
  category: "Web App", // atau "Landing Page", "UI/UX", dll
  demoUrl: "https://url-demo-proyekmu.vercel.app/",
  description: "Deskripsi proyek...", // atau "auto" untuk fetch otomatis
  image: "auto", // atau URL gambar spesifik
  tags: ["React", "Vercel", "Web"],
  githubUrl: "https://github.com/username/repo"
}
```

Semua akan otomatis:
- Muncul di grid proyek
- Di-include dalam filter kategori
- Masuk ke Tech Stack & Skills

---

## 📱 Cara Pasang Foto Profil

1. Simpan foto kamu di folder yang sama (mis: `foto.jpg`)
2. Edit bagian avatar di `index.html`, cari:
```html
<img id="avatar-photo" src="" alt="Iqbal Habibi" class="hidden w-full h-full object-cover object-center" />
```
3. Ganti `src=""` → `src="foto.jpg"`
4. Hapus class `hidden` dari tag `<img>`
5. Tambah class `hidden` pada `<div id="avatar-placeholder">`

---

## 🌐 Deploy ke GitHub Pages

Portfolio ini sudah ready untuk GitHub Pages:

1. Push repo ke GitHub
2. Buka **Settings** → **Pages**
3. Pilih branch **main** → **Save**
4. Portfolio akan online di:
   ```
   https://Balhaa.github.io/Portofolio-iqbal-habibi/
   ```

---

## 📧 Kontak

- **Email:** iqbalhabibi064@email.com
- **GitHub:** [@Balhaa](https://github.com/Balhaa)
- **LinkedIn:** [Iqbal Habibi](https://linkedin.com)
- **Instagram:** @iqbal_habibi

---

## 📝 Lisensi

MIT License — Bebas digunakan dan dimodifikasi dengan menyertakan kredit.

---

Dibuat dengan ❤️ oleh **Iqbal Habibi**  
Mahasiswa Universitas Muhammadiyah Purwokerto