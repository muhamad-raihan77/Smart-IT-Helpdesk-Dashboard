# Smart IT Helpdesk Dashboard

Sistem manajemen tiket IT perusahaan berbasis web — satu file HTML, tanpa framework atau library eksternal.

🔗 **Live Demo:** `https://<username>.github.io/<repository-name>/`

---

## Fitur

| # | Fitur | Keterangan |
|---|-------|------------|
| 1 | Sidebar navigasi | Dashboard, Tiket, Pengaturan |
| 2 | Header & profil admin | Avatar, badge notifikasi dinamis |
| 3 | Ringkasan statistik | Total, Terbuka, Dalam Proses, Selesai |
| 4 | Tabel laporan tiket | 10 data simulasi, semua kolom lengkap |
| 5 | Form tambah tiket | 7 field, validasi, ID auto-generate |
| 6 | Pencarian & filter | Real-time by ID/judul/pelapor + filter status & prioritas |
| 7 | Ubah status tiket | Dropdown inline per baris, badge notif ikut update |

## Teknologi

- **HTML5** — struktur semantik
- **CSS3** — custom properties, grid, flexbox, animasi
- **Vanilla JavaScript** — tanpa framework, tanpa library

## Struktur File

```
├── index.html       ← satu-satunya file (HTML + CSS + JS terinline)
└── README.md
```

## Cara Menjalankan Secara Lokal

Cukup buka file `index.html` di browser — tidak perlu server lokal.

```bash
# Atau gunakan Live Server / http-server
npx http-server .
```

## Deploy ke GitHub Pages

### Otomatis (GitHub Actions — Disarankan)

1. Push repository ini ke GitHub
2. Buka **Settings → Pages**
3. Di bagian *Source*, pilih **GitHub Actions**
4. Workflow di `.github/workflows/deploy.yml` akan berjalan otomatis setiap push ke branch `main`
5. Setelah selesai, akses di: `https://<username>.github.io/<repo-name>/`

### Manual

1. Buka **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / folder `/` (root)
4. Klik **Save**

---

## Screenshot

> Dashboard

![Dashboard](https://via.placeholder.com/800x450/0d1b3e/ffffff?text=Smart+IT+Helpdesk+Dashboard)

---

## Lisensi

MIT License — bebas digunakan dan dimodifikasi.
