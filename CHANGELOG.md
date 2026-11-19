# Changelog — Sandikodev Course

Semua perubahan penting pada konten kedua course dicatat di sini.

---

## [Unreleased] — Pekerjaan yang Sedang Berlangsung

### Aureliajs
- [ ] Proyek progresif bertahap (Todo app dari Bab 04–08)
- [ ] Diagram komunikasi komponen di Bab 06
- [ ] Export PDF via Pandoc/mdBook

### Evolusi Web
- [ ] Tambah ilustrasi/diagram untuk bab yang kompleks (Bab 09, Bab 25)
- [ ] Export PDF via Pandoc/mdBook

---

## 2026-11-19 — Penyempurnaan Repo Course

### Course Parent (`sandikodev/course`)
- **Update** submodule pointer ke commit terbaru untuk kedua submodule
- **Tulis ulang** README parent dengan navigasi lengkap dua course, jalur baca, cara clone

### Aureliajs (`sandikodev/course-aureliajs`)
- **Tambah** `ARTIKEL-ISLANDS.md` — bonus material: Aurelia 2 sebagai host untuk 6 framework sekaligus
- **Update** `README.md` — tambah referensi ke artikel bonus
- **Fix** inkonsistensi teks navigasi "Bab 05: Binding" → "Bab 05: Binding Lengkap"

---

## 2026-11-18 — Evolusi Web Selesai + Perbaikan Aureliajs

### Evolusi Web (Baru) (`sandikodev/course-evolusi-web`)
- **Selesai** semua 26 bab dalam 5 pilar
- **Pilar 1** (Bab 01–04): Pra-SPA, SPA pertama, React VDOM, Fragmentasi
- **Pilar 2** (Bab 05–08): JavaScript, TypeScript, Browser Platform, Runtime Wars
- **Pilar 3** (Bab 09–14): Empat Klaster, VDOM, Signals, Compiler, Resumability, SSR/Islands
- **Pilar 4** (Bab 15–21): Meta-frameworks, JAMstack, MACH, Edge, BFF, Micro-FE, Monolith
- **Pilar 5** (Bab 22–26): Sinyal ekosistem, Arsitektur defensible, Spesialisasi, Peta, Selanjutnya
- **Tambah** MANIFEST.md (8 keyakinan dasar)
- **Tambah** FRAMEWORK_POSITIONING.md (4 klaster, Vue, signals, ekosistem Indonesia)
- **Setup** repo GitHub + submodule di course parent

### Aureliajs
- **Perbaikan konten** (commit 890f36f):
  - Bab 03: ganti section Vue panjang dengan bridging paragraph ringkas
  - Bab 02: update judul section → "React, Vue, dan Aurelia: Tiga Cara"
  - Bab 05, 06, 07: diagram ASCII lifecycle hooks dan binding modes
  - Bab 05b, 07b, 09b: tambah link balik ke bab induk

---

## 2026-11-18 — Scope Evolusi Web Diperluas

### Evolusi Web
- **Revisi** scope dari "course frontend" ke "teori arsitektur web dari browser ke infrastruktur"
- **Update** judul resmi: `Evolusi Web: Dari Browser ke Infrastruktur`
- **Perluas** dari 3 pilar/19 bab ke 5 pilar/26 bab
- **Tambah** Keyakinan 8 di MANIFEST.md

---

## 2026-11-18 — Aureliajs + Evolusi Web Setup Awal

### Aureliajs
- **Perbaikan prioritas tinggi** (semua dari audit):
  - Bab 09, 09b, 10, 11: tambah latihan dengan solusi
  - Bab 10: tambah konteks job export dan implikasi bahasa Inggris
  - Bab 03: tambah catatan Vue rivalry misconception
  - README: update mencakup semua bab baru (05b, 07b, 09b)
- **Tambah** FRAMEWORK_POSITIONING.md (pertama)
- **Tambah** bab baru: 05b (Forms), 07b (Testing), 09b (Deploy)
- **Perdalam** bab existing: 05 (value converters), 06 (custom attrs), 07 (HTTP client), 08 (nested routing)

### Evolusi Web
- **Setup** awal repo
- **Selesai** MASTER_PLAN, MANIFEST, README, Bab 01

---

## 2026-11-16 sampai 2026-11-17 — Aureliajs Course Selesai

### Aureliajs
- **Selesai** 11 bab original (Bab 01–11)
- **Setup** struktur monorepo `/home/dev/bukudigital/aureliajs/`
- **Tambah** MASTER_PLAN.md (dokumen kunci lintas sesi)
- **Setup** git + push ke GitHub `sandikodev/course-aureliajs`
- **Setup** parent repo `sandikodev/course` dengan aureliajs sebagai submodule pertama

---

*Format: `[versi] — tanggal — deskripsi`*  
*Konvensi: **Tambah**, **Update**, **Fix**, **Hapus**, **Setup**, **Selesai***
