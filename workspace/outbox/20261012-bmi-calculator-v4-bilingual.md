# Catatan Serah Terima (v4) / Handoff Note — Kalkulator BMI v4 (Versi Dwibahasa ID/EN)

- **Tanggal / Date**: 2026-10-12
- **Dari / From**: Taroko (Anggota Tim / Member)
- **Untuk / To**: Wailan (Pemimpin Tim / Leader) melalui Captain Romyal
- **Berkas Hasil / Target File**: [`20261012-bmi-calculator-index-v4.html`](file:///c:/Users/Fatih%20Ahmad%20Faisal/OneDrive/Documents/my-team/workspace/outbox/20261012-bmi-calculator-index-v4.html)
- **Status Versi Sebelumnya**:
  - v1 ([`20261012-bmi-calculator-index.html`](file:///c:/Users/Fatih%20Ahmad%20Faisal/OneDrive/Documents/my-team/workspace/outbox/20261012-bmi-calculator-index.html)) utuh, tidak diubah.
  - v2 ([`20261012-bmi-calculator-index-v2.html`](file:///c:/Users/Fatih%20Ahmad%20Faisal/OneDrive/Documents/my-team/workspace/outbox/20261012-bmi-calculator-index-v2.html)) utuh, tidak diubah.
  - v3 ([`20261012-bmi-calculator-index-v3.html`](file:///c:/Users/Fatih%20Ahmad%20Faisal/OneDrive/Documents/my-team/workspace/outbox/20261012-bmi-calculator-index-v3.html)) utuh, tidak diubah.

---

### Satu Baris Ringkasan Serah Terima / Handoff Line
> **Menambahkan fitur dwibahasa (Bahasa Indonesia & English) dengan pengalih instan di header, penerjemahan teks dinamis real-time (termasuk hasil aktif, skala, dan pesan validasi), serta mempertahankan seluruh fitur mode ketik/slider v3; siap langsung dibuka dan digunakan di browser.**

---

### Fitur yang Dikerjakan di Versi 4 / What was done in v4
1. **Pengalih Bahasa Instan (Language Switcher)**:
   - Ditempatkan di bagian atas kartu aplikasi (header).
   - Mendukung dua bahasa: **Bahasa Indonesia** (bawaan) dan **English**.
2. **Penerjemahan Menyeluruh & Dinamis**:
   - Seluruh elemen teks berubah sesuai bahasa yang dipilih: judul, subjudul, tombol mode, label input, placeholder, tombol hitung/reset, tabel referensi, dan skala visual.
   - Kategori hasil:
     - ID: Kurus / Normal / Kelebihan berat badan / Obesitas
     - EN: Underweight / Normal / Overweight / Obese
   - Kotak saran berat badan ideal dan deskripsi kategori diterjemahkan penuh.
3. **Penerjemahan Hasil Aktif Tanpa Hitung Ulang**:
   - Jika kalkulasi sudah tampil di layar lalu pengguna mengganti bahasa, teks kategori, deskripsi, dan saran berat badan ideal langsung berubah ke bahasa terpilih secara instan tanpa perlu menekan tombol hitung kembali.
4. **Pesan Validasi Dwibahasa**:
   - Jika terjadi kesalahan input (misal berat 0 kg pada slider atau kolom ketik kosong), pesan kesalahan muncul dalam bahasa yang sedang aktif.
   - Berganti bahasa saat pesan kesalahan tampil otomatis memperbarui teks pesan ke bahasa yang baru dipilih.
5. **Mempertahankan Seluruh Fitur v3**:
   - Mode "Ketik Manual" (default) dan "Gunakan Slider" dengan sinkronisasi dua arah.
   - Bar skala visual BMI dengan jarum penunjuk dinamis.
   - Rentang berat badan ideal berdasarkan tinggi badan.
   - Berkas mandiri tanpa library luar.
