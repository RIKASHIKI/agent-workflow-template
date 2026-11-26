# Instruksi untuk Agent

## Ringkasan proyek

> Ganti bagian ini dengan 2–3 kalimat: apa yang dibangun proyek ini, siapa penggunanya, serta stack atau lingkungan utamanya. Jangan mencantumkan asumsi yang belum dikonfirmasi.

## Urutan acuan

Instruksi pengguna dalam percakapan menentukan lingkup tugas dan mengungguli dokumentasi proyek. Untuk aturan proyek yang bertentangan, gunakan urutan berikut: `docs/panduan.md` > `docs/arsitektur.md` > `docs/roadmap.md`. Jika konflik tetap ambigu atau berdampak pada keamanan/data, berhenti dan minta klarifikasi.

## Jalur baca

| Kapan | Baca |
|---|---|
| Awal setiap tugas | Dokumen ini |
| Memilih atau memastikan pekerjaan aktif | `docs/roadmap.md` |
| Sebelum mengubah kode | `docs/panduan.md` |
| Mengubah struktur data, API, atau keputusan teknis | `docs/arsitektur.md` |
| Melanjutkan pekerjaan dari sesi sebelumnya | Entri terbaru di `CHANGELOG-agent.md` |
| Mengakhiri sesi | Tambahkan tiga butir ke `CHANGELOG-agent.md` |

## Cara bekerja

- Kerjakan hanya milestone aktif kecuali pengguna secara eksplisit meminta hal lain.
- Pastikan kriteria selesai dapat diverifikasi; jalankan pemeriksaan yang tersedia dan laporkan hasilnya.
- Jangan mengubah dokumentasi yang tidak relevan. Roadmap diperbarui saat milestone dibuka/ditutup; ADR dicatat saat keputusan dibuat; changelog ditambahkan di akhir sesi.
- Jangan mengarang keputusan, status, hasil pengujian, atau isi placeholder. Jika informasi penting tidak tersedia, tanyakan.
