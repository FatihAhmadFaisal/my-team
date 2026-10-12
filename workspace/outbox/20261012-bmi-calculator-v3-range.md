# Catatan Serah Terima (v3) / Handoff Note — Kalkulator BMI v3 (Mode Slider)

- **Tanggal / Date**: 2026-10-12
- **Dari / From**: Taroko (Anggota Tim / Member)
- **Untuk / To**: Wailan (Pemimpin Tim / Leader) melalui Captain Romyal
- **Berkas Hasil / Target File**: [`20261012-bmi-calculator-index-v3.html`](file:///c:/Users/Fatih%20Ahmad%20Faisal/OneDrive/Documents/my-team/workspace/outbox/20261012-bmi-calculator-index-v3.html)
- **Status Versi Sebelumnya**:
  - v1 ([`20261012-bmi-calculator-index.html`](file:///c:/Users/Fatih%20Ahmad%20Faisal/OneDrive/Documents/my-team/workspace/outbox/20261012-bmi-calculator-index.html)) utuh, tidak diubah.
  - v2 ([`20261012-bmi-calculator-index-v2.html`](file:///c:/Users/Fatih%20Ahmad%20Faisal/OneDrive/Documents/my-team/workspace/outbox/20261012-bmi-calculator-index-v2.html)) utuh, tidak diubah.

---

### Satu Baris Ringkasan Serah Terima / Handoff Line
> **Menambahkan kontrol input geser (slider) dengan sinkronisasi dua arah dan tombol pengalih mode pada 20261012-bmi-calculator-index-v3.html sambil mempertahankan seluruh fitur visual dan validasi ketat v2; aplikasi mandiri siap langsung dibuka dan digunakan di browser.**

---

### Fitur yang Dikerjakan di Versi 3 / What was done in v3
1. **Tombol Pengalih Mode (Mode Switcher)**:
   - Disediakan tombol pilihan "Ketik Manual" (mode bawaan/default) dan "Gunakan Slider".
   - Mengalihkan panel kontrol slider secara mulus tanpa mengganggu input angka.
2. **Kontrol Slider dengan Nilai Terkini**:
   - **Berat Badan**: rentang 0 – 200 kg (langkah 1 kg).
   - **Tinggi Badan**: rentang 0 – 300 cm (langkah 1 cm).
   - Indikator nilai waktu nyata di samping label slider (contoh: "70 kg", "175 cm").
3. **Sinkronisasi Dua Arah (Two-Way Synchronization)**:
   - Menggeser slider otomatis memperbarui angka di kolom ketik.
   - Mengetik angka manual otomatis menggeser posisi slider ke angka yang bersangkutan.
4. **Validasi Menyeluruh**:
   - Tombol "Hitung BMI" berlaku terpadu untuk kedua mode.
   - Menggeser ke angka 0 kg atau angka di luar batas wajar (tinggi < 50 cm atau > 300 cm; berat < 10 kg atau > 500 kg) tetap memicu pesan kesalahan berbahasa Indonesia yang ramah.
5. **Mempertahankan Seluruh Fitur v2**:
   - Bar skala visual BMI dengan jarum penunjuk dinamis.
   - Perhitungan rentang berat badan ideal (BMI 18.5 – 24.9) dan saran penyesuaian berat badan.
   - Tabel referensi standar kategori BMI.
