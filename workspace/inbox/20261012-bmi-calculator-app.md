# Tugas: Aplikasi Kalkulator BMI (UI berbahasa Indonesia)

Dari: Wailan (Pemimpin tim)
Untuk: Taroko (anggota tim)
Tanggal: 2026-10-12

## Apa yang harus dikerjakan / What to do

Buat aplikasi **kalkulator BMI (Body Mass Index)** dengan **tampilan berbahasa Indonesia**.

Aturan teknis:
- Satu file saja: `index.html` (CSS dan JavaScript ditulis di dalam file yang sama, tanpa file tambahan).
- Input: berat badan (kg) dan tinggi badan (cm), dengan validasi (nilai harus angka dan masuk akal; tampilkan pesan kesalahan dalam bahasa Indonesia jika input salah).
- Rumus: BMI = berat (kg) / tinggi (m)². Tinggi dalam cm harus dikonversi ke meter.
- Tampilkan hasil BMI (angka, 1 desimal) dan kategori:
  - BMI < 18.5 → "Kurus"
  - 18.5 ≤ BMI < 25 → "Normal"
  - 25 ≤ BMI < 30 → "Kelebihan berat badan"
  - BMI ≥ 30 → "Obesitas"
- Semua teks di layar (judul, label, tombol, pesan kesalahan, kategori hasil) dalam bahasa Indonesia.
- Tampilan rapi dan sederhana: bisa dipakai di browser biasa, tanpa library/framework luar.

## Format / cara menyimpan

- Simpan hasil sebagai **file baru** di `workspace/outbox/`, nama file: `20261012-bmi-calculator-index.html`.
- Jangan menimpa file lain, jangan mengubah file di `workspace/shared/`.

## Tanda selesai / What "done" looks like

- File `20261012-bmi-calculator-index.html` ada di `workspace/outbox/`.
- Buka file itu di browser: masukkan berat 70 kg dan tinggi 175 cm → muncul BMI ≈ 22,9 dan kategori "Normal".
- Input yang salah (misalnya huruf atau angka negatif) menampilkan pesan kesalahan berbahasa Indonesia, bukan error.
- Seluruh tampilan berbahasa Indonesia.
- Tulis satu baris catatan serah-terima (apa yang dikerjakan, hal yang perlu diperhatikan, siap dipakai atau belum) di dalam outbox.
