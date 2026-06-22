# Website JMK (Next.js)

Ini adalah project website **JMK** yang dibangun menggunakan **Next.js** versi terbaru dengan fitur App Router, React 19, TypeScript, dan Tailwind CSS v4.

## 🚀 Fitur Utama

- **Next.js 16 (App Router)** - Routing modern yang cepat, aman, dan mendukung Server Components.
- **React 19** - Memanfaatkan fitur React terbaru untuk performa optimal.
- **Tailwind CSS v4** - Styling utility-first yang super cepat dengan engine compiler terbaru.
- **TypeScript** - Menjamin tipe data yang aman dan meminimalisir bug selama development.

## 🛠️ Persiapan Memulai (Getting Started)

Ikuti langkah-langkah di bawah ini untuk menjalankan project di lingkungan lokal Anda.

### Prasyarat

Pastikan Anda sudah menginstal:
- **Node.js** (Rekomendasi versi LTS terbaru)
- **npm** (Bawaan Node.js) atau **yarn** / **pnpm**

### Instalasi Dependensi

Pertama, klon repositori ini (atau buka foldernya) dan instal semua modul yang dibutuhkan:

```bash
npm install
# atau
yarn install
# atau
pnpm install
```

### Menjalankan Server Development

Jalankan perintah berikut untuk memulai local development server:

```bash
npm run dev
# atau
yarn dev
# atau
pnpm dev
```

Buka [http://localhost:3000](http://localhost:3000) pada browser Anda untuk melihat hasilnya.

### Build untuk Produksi

Untuk membuat build produksi yang dioptimalkan, jalankan:

```bash
npm run build
```

Setelah build selesai, Anda dapat menjalankannya dengan:

```bash
npm run start
```

## 📂 Struktur Folder Proyek

```text
├── app/                  # App Router (Halaman, Layout, & Style Global)
│   ├── favicon.ico       # Favicon website
│   ├── globals.css       # Style CSS Global (Tailwind CSS v4)
│   ├── layout.tsx        # Layout utama (Root Layout)
│   └── page.tsx          # Halaman utama (Home Page)
├── public/               # File statis (Gambar, Font, dll.)
├── next.config.ts        # Konfigurasi Next.js
├── postcss.config.mjs    # Konfigurasi PostCSS
├── package.json          # Metadata project & Dependensi
├── tsconfig.json         # Konfigurasi TypeScript
└── eslint.config.mjs     # Konfigurasi ESLint linting
```

---

Dibuat untuk menyelesaikan matakuliah manajemen proyek TI.
