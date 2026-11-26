# agent-workflow-template

Template dokumentasi untuk membantu coding agent tetap fokus, mengikuti batasan proyek, memahami alasan keputusan teknis, dan melanjutkan pekerjaan antar-sesi.

## Mulai

1. Salin struktur dan sesuaikan placeholder dengan proyek Anda.
2. Isi `AGENTS.md` dengan konteks singkat dan jalur baca yang relevan.
3. Tentukan milestone aktif di `docs/roadmap.md` (hanya satu pada satu waktu).
4. Tetapkan aturan proyek di `docs/panduan.md` dan catat keputusan yang sudah disepakati di `docs/arsitektur.md`.
5. Di akhir sesi, tambahkan entri ringkas ke `CHANGELOG-agent.md`.

## Struktur

```text
.
├── AGENTS.md              # Titik masuk agent dan indeks instruksi
├── CHANGELOG-agent.md     # Catatan antar-sesi, append-only
└── docs/
    ├── roadmap.md         # Milestone aktif dan kriteria selesai
    ├── panduan.md         # Aturan wajib, pedoman, dan larangan
    └── arsitektur.md      # Keputusan teknis dan alasannya (ADR)
```

## Prinsip penggunaan

- Baca hanya dokumen yang diperlukan untuk tugas; `AGENTS.md` mengarahkan agent ke dokumen terkait.
- Instruksi langsung dari pengguna mengatur lingkup tugas. Untuk aturan proyek yang saling bertentangan, gunakan urutan pada `AGENTS.md`; tanyakan jika konflik tidak dapat diselesaikan dengan aman.
- Tiap kriteria roadmap harus dapat diverifikasi. Jangan pindah ke milestone lain tanpa persetujuan pengguna.
- Catat keputusan baru sebagai ADR; jangan menghapus riwayat keputusan yang sudah digantikan.
- Changelog hanya ditambahkan pada akhir sesi, dengan format tetap tiga butir.

Template ini tidak mengasumsikan bahasa pemrograman, framework, maupun perintah pengujian tertentu. Ganti contoh dan placeholder agar sesuai dengan repo Anda.
