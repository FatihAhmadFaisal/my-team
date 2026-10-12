# Catatan Serah Terima / Handoff Note — Kalkulator BMI

- **Tanggal / Date**: 2026-10-12
- **Dari / From**: Taroko (Anggota Tim / Member)
- **Untuk / To**: Wailan (Pemimpin Tim / Leader) melalui Captain Romyal
- **Berkas Hasil / Target File**: [`20261012-bmi-calculator-index.html`](file:///c:/Users/Fatih%20Ahmad%20Faisal/OneDrive/Documents/my-team/workspace/outbox/20261012-bmi-calculator-index.html)

---

### Satu Baris Ringkasan Serah Terima / Handoff Line
> **Telah membuat aplikasi kalkulator BMI mandiri (HTML/CSS/JS dalam satu berkas) dengan antarmuka bahasa Indonesia dan validasi masukan; perhatikan batas rentang angka tinggi (50–300 cm) dan berat (10–500 kg); aplikasi siap langsung dibuka di browser tanpa dependensi eksternal.**

---

### Hal yang Dikerjakan / What was done
1. **Berkas Mandiri**: Dibuat berkas tunggal `20261012-bmi-calculator-index.html` yang mencakup struktur HTML5, styling CSS responsif, dan logika JavaScript murni (vanilla JS).
2. **Bahasa Antarmuka**: Seluruh teks tampilan (judul, label masukan, tombol, pesan validasi/kesalahan, dan kategori status BMI) disajikan dalam bahasa Indonesia.
3. **Validasi & Penanganan Error**:
   - Memeriksa masukan kosong atau bukan angka.
   - Memastikan nilai positif di atas 0.
   - Membatasi rentang nilai wajar untuk tinggi badan (50–300 cm) dan berat badan (10–500 kg).
   - Menampilkan kotak pesan kesalahan berbahasa Indonesia jika input tidak valid.
4. **Rumus & Kategori BMI**:
   - Mengonversi tinggi badan dari sentimeter ke meter (\(m = \text{cm} / 100\)).
   - Menghitung \(\text{BMI} = \text{berat (kg)} / (\text{tinggi (m)})^2\), dibulatkan menjadi 1 desimal.
   - Pengkategorian:
     - BMI < 18.5: **Kurus**
     - 18.5 ≤ BMI < 25: **Normal**
     - 25 ≤ BMI < 30: **Kelebihan berat badan**
     - BMI ≥ 30: **Obesitas**
5. **Uji Coba Mandiri**:
   - Masukan berat: 70 kg, tinggi: 175 cm \(\rightarrow\) Hasil: BMI 22.9, Kategori: **Normal** (sesuai kriteria selesai).
   - Masukan huruf / angka tidak wajar \(\rightarrow\) Menampilkan pesan kesalahan berbahasa Indonesia tanpa crash.
