# Catatan Serah Terima (v5) / Handoff Note — Kalkulator BMI v5 (Tema Luar Angkasa & Fakta Planet Ramah Anak)

- **Tanggal / Date**: 2026-10-12
- **Dari / From**: Taroko (Anggota Tim / Member)
- **Untuk / To**: Wailan (Pemimpin Tim / Leader) melalui Captain Romyal
- **Berkas Hasil / Target File**: [`20261012-bmi-calculator-index-v5.html`](file:///c:/Users/Fatih%20Ahmad%20Faisal/OneDrive/Documents/my-team/workspace/outbox/20261012-bmi-calculator-index-v5.html)
- **Status Versi Sebelumnya**:
  - v1 ([`20261012-bmi-calculator-index.html`](file:///c:/Users/Fatih%20Ahmad%20Faisal/OneDrive/Documents/my-team/workspace/outbox/20261012-bmi-calculator-index.html)) utuh, tidak diubah.
  - v2 ([`20261012-bmi-calculator-index-v2.html`](file:///c:/Users/Fatih%20Ahmad%20Faisal/OneDrive/Documents/my-team/workspace/outbox/20261012-bmi-calculator-index-v2.html)) utuh, tidak diubah.
  - v3 ([`20261012-bmi-calculator-index-v3.html`](file:///c:/Users/Fatih%20Ahmad%20Faisal/OneDrive/Documents/my-team/workspace/outbox/20261012-bmi-calculator-index-v3.html)) utuh, tidak diubah.
  - v4 ([`20261012-bmi-calculator-index-v4.html`](file:///c:/Users/Fatih%20Ahmad%20Faisal/OneDrive/Documents/my-team/workspace/outbox/20261012-bmi-calculator-index-v4.html)) utuh, tidak diubah.

---

### Satu Baris Ringkasan Serah Terima / Handoff Line
> **Menambahkan tema antariksa berbintang kontras tinggi, ilustrasi 4 planet CSS dinamis per kategori BMI (Mars, Bumi, Jupiter, Saturnus), kutipan fakta planet ramah anak yang dipilih acak, dan penerjemahan dwibahasa instan pada 20261012-bmi-calculator-index-v5.html; mempertahankan seluruh fitur v4; berkas mandiri siap langsung dibuka dan digunakan di browser.**

---

### Fitur yang Dikerjakan di Versi 5 / What was done in v5
1. **Tema Latar Belakang Luar Angkasa (Space Theme)**:
   - Gradasi langit malam antariksa berbintang dengan animasi melayang kosmis yang halus.
   - Kartu antarmuka bergaya dark cosmic slate dengan kontras tinggi (teks putih/terang, aksen cyan bercahaya) sehingga seluruh teks dan elemen input sangat mudah dibaca.
2. **Ilustrasi 4 Planet Murni CSS (Pure CSS Planets)**:
   - **Kurus (< 18.5) \(\rightarrow\) Mars**: Planet merah jingga dengan kawah dan bayangan 3D realistis.
   - **Normal (18.5–24.9) \(\rightarrow\) Bumi (Earth)**: Planet biru laut dengan benua hijau dan lapisan awan putih lembut.
   - **Kelebihan berat badan (25.0–29.9) \(\rightarrow\) Jupiter**: Planet gas bergaris dengan Bintik Merah Raksasa (Great Red Spot).
   - **Obesitas (\(\ge\) 30.0) \(\rightarrow\) Saturnus (Saturn)**: Planet emas dengan cincin elliptical 3D miring dari es dan batuan.
   - Dilengkapi animasi melayang/mengapung (*floating animation*) yang hidup tanpa memerlukan gambar eksternal maupun library luar.
3. **Kutipan Fakta Planet Ramah Anak (Kid-Friendly Quotes)**:
   - Menyediakan 4 kutipan ilmiah nyata dan akurat untuk tiap planet (total 16 kutipan terkurasi).
   - Dipilih secara acak (*random pool*) setiap kali tombol Hitung ditekan sehingga pengalaman pengguna terasa dinamis.
   - Gaya bahasa mudah dipahami anak sekolah dasar (kalimat pendek, seruan ramah seperti "Wah!", "Tahukah kamu?", "Keren!"), tanpa istilah medis rumit dan berfokus pada keajaiban astronomi tanpa menghakimi tubuh.
4. **Dwibahasa Instan (Bilingual ID/EN)**:
   - Kutipan planet dan nama planet memiliki versi Bahasa Indonesia dan English.
   - Mengganti bahasa saat hasil sedang tampil langsung menerjemahkan kutipan yang aktif secara instan tanpa perlu menekan hitung ulang.
5. **Mempertahankan Seluruh Fitur Versi 4**:
   - Mode ketik manual dan slider tersinkronisasi dua arah.
   - Bar skala visual BMI dengan jarum penunjuk dinamis.
   - Rekomendasi rentang berat badan ideal berdasarkan tinggi badan.
   - Validasi ketat (angka 0, masukan di luar rentang wajar, dsb.) dengan pesan kesalahan dwibahasa.
