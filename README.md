# Feny AI — Praktikum 2 PABWE 2026

Website multi-halaman untuk perusahaan jasa AI fiktif ** Feny  AI**, dibangun sesuai spesifikasi
Praktikum 2 (CSS, Bootstrap 5, Tailwind CSS 4).

## Struktur

```
├── index.html              # Landing page — HTML + CSS murni
├── blog.html                # Daftar blog — Bootstrap 5 + Bootstrap Icons
├── blog-detail.html         # Detail artikel blog — Bootstrap 5 + Bootstrap Icons
├── cv.html                  # Curriculum Vitae — Tailwind CSS 4
├── assets/
│   ├── css/
│   │   └── style.css        # External CSS untuk index.html
│   └── img/                 # (opsional — belum dipakai, semua visual dibuat CSS/SVG)
└── README.md
```

## Teknologi per halaman

| Halaman | Teknologi | Catatan |
|---|---|---|
| `index.html` | HTML5 + CSS murni | Tanpa framework, CSS variables, Flexbox/Grid, media query |
| `blog.html` | Bootstrap 5.3 + Bootstrap Icons | Grid card, badge, navbar, pagination |
| `blog-detail.html` | Bootstrap 5.3 + Bootstrap Icons | Blockquote, alert, artikel terkait, form komentar |
| `cv.html` | Tailwind CSS 4 (Play CDN) | `@theme` untuk token warna brand, utility responsive |

## Brand

**Feny AI** — nama diambil dari kata *arunika* (cahaya fajar), merepresentasikan tema
"insight yang menyingsing" untuk visual perusahaan (gradasi warna gelap → amber → rose).

## Cara menjalankan

Buka `index.html` langsung di browser, atau jalankan live server lokal (mis. ekstensi
"Live Server" di VSCode) agar navigasi antar halaman berjalan mulus.
