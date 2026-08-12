# NOSTOS — Perjalanan Pulang Odysseus

Website satu-halaman (scroll-driven) bergaya **futuristic-Hellenic**: museum digital kisah *Nostos* (νόστος) — perjalanan pulang Odysseus dari Troya menuju Ithaca, berdasarkan epik *Odyssey* karya Homer.

## Fitur
- 16 babak narasi sesuai urutan Odyssey (Hero → Troya → Lotophagi → Cyclops → Aeolus → Circe → Nekyia → Sirene → Scylla & Charybdis → Thrinacia → Calypso → Phaeacia → Kepulangan → Mnesteres → Reuni → Penutup)
- Teks Yunani kuno 5 baris pembuka Buku I (public domain) dengan animasi "mengukir", transliterasi, terjemahan glassmorphism, dan tombol pelafalan (Web Speech API)
- Peta pelayaran interaktif (16 waypoint, klik untuk lompat)
- Particle starfield/ombak laut (canvas), kapal parallax, divider meander animasi
- Ilustrasi SVG custom gaya red-figure pottery dengan outline neon
- Audio atmosfer laut via Web Audio API
- Responsif + `prefers-reduced-motion`

## Deploy
Static single-page — cukup push ke GitHub dan import di Vercel (framework: Other).
