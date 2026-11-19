# Course — Sandikodev

> Kumpulan course teknis dalam Bahasa Indonesia untuk developer mid/senior yang ingin naik level — bukan hanya belajar cara pakai teknologi, tapi memahami *mengapa* ekosistem bergerak seperti yang ia bergerak.

---

## Daftar Course

| Course | Sasaran Pembaca | Format | Bab | Status |
|--------|----------------|--------|-----|--------|
| **[Aurelia 2: Framework yang Berbeda](./aureliajs/)** | Pemula – Mid yang mau niche Upwork | Tutorial teknis + latihan | 15 bab | ✅ Draft selesai |
| **[Evolusi Web: Dari Browser ke Infrastruktur](./evolusi-web/)** | Mid/Senior yang mau naik level | Esai teknis + refleksi | 26 bab | ✅ Draft selesai |

---

## Course 1 — Aurelia 2: Framework yang Berbeda

**Lokasi:** [`./aureliajs/`](./aureliajs/)  
**Repo:** [`sandikodev/course-aureliajs`](https://github.com/sandikodev/course-aureliajs)

### Tentang

Tutorial teknis tentang Aurelia 2 dalam Bahasa Indonesia — framework frontend yang dirancang sebagai penyempurnaan Angular, dengan Direct-DOM yang tidak butuh Virtual DOM dan Zero Zone.js.

Course ini untuk developer yang ingin:
- Memahami Aurelia 2 dari perspektif seseorang yang sudah paham Angular/React
- Masuk ke niche freelance yang kompetisinya sangat rendah (15–30 job Upwork, hampir nol kompetitor qualified)
- Memiliki portfolio proyek nyata (Aurelia Ops Dashboard) sebagai bukti kerja

### Struktur (15 Bab)

```
Fondasi Konseptual
  Bab 01  Kenapa Aurelia? Sejarah Rob Eisenberg vs Google 2014
  Bab 02  Mental model: class-based vs re-render (React, Vue, Aurelia)
  Bab 03  Untuk ex-Angular: persamaan dan perbedaan

Teknis Dasar
  Bab 04  Setup project (npx makes aurelia, TypeScript stage-3 decorators)
  Bab 05  Binding lengkap: .bind, value converters, containerless
  Bab 05b Forms & Validation (@aurelia/validation)
  Bab 06  Komponen: @bindable, custom attributes, HTML-only, EventAggregator
  Bab 07  Dependency Injection: resolve(), HTTP client, service pattern
  Bab 07b Testing: Vitest + createFixture, mocks, routing tests

Teknis Lanjut
  Bab 08  Routing: @route, nested, guard, pola boot auth
  Bab 09  Studi kasus: multi-tenant SaaS dari Aurelia Ops
  Bab 09b Production Build & Deploy

Karier
  Bab 10  Upwork strategy: positioning, proposal, job export
  Bab 11  Portfolio builder: fork, modifikasi, deploy Aurelia Ops
```

### Referensi Kode

Semua contoh diambil dari **[Aurelia Ops](https://github.com/sandikodev/aureliajs)** — SaaS admin dashboard production-ready dengan Aurelia 2 (RC.2), Hono, Drizzle ORM, PostgreSQL, dan Stripe.

---

## Course 2 — Evolusi Web: Dari Browser ke Infrastruktur

**Lokasi:** [`./evolusi-web/`](./evolusi-web/)  
**Repo:** [`sandikodev/course-evolusi-web`](https://github.com/sandikodev/course-evolusi-web)

### Tentang

**Bukan untuk pemula.** Esai teknis terstruktur untuk developer mid/senior yang sudah deploy ke production dan ingin memahami *mengapa* ekosistem web bergerak seperti yang ia bergerak — dari browser sampai infrastruktur.

Setelah membaca, kamu bisa:
- Memetakan trade-off di setiap lapisan stack (bukan hanya cara pakainya)
- Membaca sinyal ekosistem — bedakan hype dari traction nyata
- Merekomendasikan arsitektur dengan argumen yang defensible
- Tidak panik setiap kali framework baru muncul

### Struktur (26 Bab, 5 Pilar)

```
Pilar 1 — Sejarah & Konteks (Bab 01–04)
  Pra-SPA → jQuery → SPA pertama (AngularJS/Backbone/Ember)
  → React & VDOM → Fragmentasi ekosistem

Pilar 2 — Substrate & Platform (Bab 05–08)
  JavaScript (10 hari, type coercion, V8) → TypeScript (type erasure, Zod)
  → Browser sebagai platform (Web APIs, CSS modern, Wasm)
  → Runtime Wars (Node/Deno/Bun/Workers, WinterCG)

Pilar 3 — Paradigma & Rendering (Bab 09–14)
  Empat klaster paradigma → VDOM → Signals (konvergensi diam-diam)
  → Compiler-first Svelte → Resumability Qwik
  → SSR/Islands/Streaming/RSC

Pilar 4 — Fullstack & Stack Philosophy (Bab 15–21)
  Meta-frameworks → JAMstack → MACH & Composable Architecture
  → Edge-First → BFF → Micro-frontends → Monolith yang terhormat

Pilar 5 — Navigasi & Sintesis (Bab 22–26)
  Cara baca sinyal ekosistem → Arsitektur defensible
  → Spesialisasi vs generalisasi → Peta menyeluruh 6 dimensi
  → Selanjutnya (AI-native, WebAssembly, signals TC39)
```

### Companion Document

[`FRAMEWORK_POSITIONING.md`](./evolusi-web/FRAMEWORK_POSITIONING.md) — referensi cepat untuk empat klaster paradigma, posisi Vue, konvergensi signals, dan aturan perbandingan yang valid.

---

## Cara Clone

### Clone semua (dengan submodule)

```bash
git clone --recurse-submodules git@github.com:sandikodev/course.git
```

### Clone tanpa submodule, lalu init

```bash
git clone git@github.com:sandikodev/course.git
cd course
git submodule update --init --recursive
```

### Update ke konten terbaru

```bash
git submodule update --remote --merge
```

---

## Jalur Baca yang Disarankan

**Kalau kamu junior/mid yang ingin masuk niche Aurelia:**
→ Baca Course 1 (Aurelia 2) dari awal

**Kalau kamu mid/senior yang ingin naik level memahami ekosistem:**
→ Baca Course 2 (Evolusi Web) dari awal

**Kalau kamu sudah familiar dengan Angular dan mau niche Upwork:**
→ Bab 03 → Bab 05 → Bab 07 → Bab 09 → Bab 10 (Course 1)

**Kalau kamu mau memahami mengapa Vue bukan rival React secara teknis:**
→ [`FRAMEWORK_POSITIONING.md`](./evolusi-web/FRAMEWORK_POSITIONING.md) → Bab 09 (Course 2)

**Kalau kamu mau tahu stack apa yang cocok untuk use case kamu:**
→ Bab 25 (Course 2) — Peta Menyeluruh

---

## Produk Digital

Kedua course tersedia sebagai produk digital (PDF + starter kit):  
👉 **[lynk.id/sandikodev](https://lynk.id/sandikodev)**

---

## Penulis

**Sandikodev** — TypeScript/web engineer  
TikTok & Facebook: @sandikodev

---

*Semua konten di repo ini ditulis dalam Bahasa Indonesia.*
