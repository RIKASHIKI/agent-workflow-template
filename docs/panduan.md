# Panduan Proyek

Ganti contoh dalam tanda kurung siku dengan aturan yang disepakati untuk proyek ini. Hapus aturan yang tidak relevan. Jika belum ada aturan, tandai sebagai belum ditetapkan daripada menganggap contoh sebagai fakta.

## WAJIB

Aturan keras yang berlaku untuk semua perubahan dan dapat diperiksa. Pertahankan daftar ringkas (sekitar 10 aturan atau kurang).

1. [Contoh: Semua akses database harus melalui lapisan repository, jika proyek memang menggunakannya.]
2. [Contoh: Jangan menyimpan secret atau kredensial di repository.]
3. [Tambahkan aturan proyek yang dapat diverifikasi.]

## PEDOMAN

Preferensi yang boleh dikesampingkan dengan alasan singkat dalam perubahan atau ringkasan kerja.

- [Contoh: Utamakan fungsi kecil dan mudah diuji bila sesuai dengan desain proyek.]
- [Tambahkan preferensi proyek.]

## LARANGAN

Tindakan yang tidak boleh dilakukan tanpa persetujuan eksplisit pengguna.

- [Contoh: Jangan mengubah atau menghapus migrasi yang sudah diterapkan.]
- [Contoh: Jangan menambah dependency tanpa meminta persetujuan.]
- [Tambahkan batasan spesifik proyek; pastikan tidak bertentangan dengan instruksi pengguna yang lebih baru.]

## Menangani konflik

Ikuti urutan acuan yang ditetapkan di `AGENTS.md`. Instruksi langsung pengguna menentukan lingkup permintaan, tetapi perubahan yang melanggar batasan keamanan atau berisiko merusak data perlu diklarifikasi sebelum dilakukan. Jangan diam-diam memilih interpretasi ketika aturan wajib bertentangan.
