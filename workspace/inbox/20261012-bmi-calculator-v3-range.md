# Tugas v3: Kalkulator BMI — Mode Input Geser (Slider) Tambahan

Dari: Wailan (Pemimpin tim)
Untuk: Taroko (anggota tim)
Tanggal: 2026-10-12

## Apa yang harus dikerjakan / What to do

Buat **versi 3** dari kalkulator BMI. Intinya: tambahkan **pilihan input berupa slider (geser)** di samping cara ketik yang sudah ada.

Aturan teknis:
- Berkas baru: `20261012-bmi-calculator-index-v3.html` (satu file, CSS/JS di dalam). **Jangan menimpa atau menghapus v1 dan v2.**
- **Pertahankan SEMUA fitur v2** yang sudah berjalan: input ketik + validasi, tombol Hitung BMI / Reset, hasil BMI + kategori, bar skala visual + jarum, rentang berat badan ideal, tabel referensi, seluruh teks bahasa Indonesia.
- **Tambahkan tombol pengalih mode** (misalnya "Gunakan Slider" / "Ketik Manual") yang menampilkan dan menyembunyikan panel slider. Cara ketik tetap menjadi mode bawaan saat halaman dibuka.
- Panel slider berisi dua kontrol geser:
  - **Berat Badan**: rentang 0 – 200 kg (kenaikan 1 kg)
  - **Tinggi Badan**: rentang 0 – 300 cm (kenaikan 1 cm)
- Setiap slider harus menampilkan **angka nilai terkini** di sebelahnya (misalnya "70 kg", "175 cm") dan **tersinkronisasi** dengan kolom ketik — menggeser slider mengubah nilai ketik, sebaliknya mengetik mengubah posisi slider.
- Tombol "Hitung BMI" tetap satu, berlaku untuk kedua mode, dan hasilnya sama persis di kedua mode.
- **Validasi tetap berlaku** untuk kedua mode: nilai 0 atau di luar batas wajar (tinggi < 50 cm atau > 300 cm; berat < 10 kg atau > 500 kg) tetap menampilkan pesan kesalahan berbahasa Indonesia seperti versi sebelumnya.
- Tampilan rapi di layar kecil maupun besar, tanpa library/framework luar.

## Format / cara menyimpan

- Simpan sebagai **file baru** di `workspace/outbox/`, nama: `20261012-bmi-calculator-index-v3.html`.
- V1 (`20261012-bmi-calculator-index.html`) dan V2 (`20261012-bmi-calculator-index-v2.html`) **tidak boleh diubah atau dihapus**.
- Tulis satu baris catatan serah-terima di outbox (apa yang dikerjakan, hal yang perlu diperhatikan, siap dipakai atau belum).

## Tanda selesai / What "done" looks like

- File `20261012-bmi-calculator-index-v3.html` ada di outbox; v1 dan v2 masih utuh.
- Mode ketik berfungsi seperti v2: 70 kg + 175 cm → BMI 22,9 → "Normal".
- Tekan tombol pengalih → panel slider muncul; geser ke 70 kg dan 175 cm → hasil Hitung BMI sama persis dengan mode ketik.
- Nilai slider selalu cocok dengan isi kolom ketik (tersinkron dua arah).
- Geser berat ke 0 kg lalu Hitung → muncul pesan kesalahan berbahasa Indonesia (validasi aktif).
- Seluruh teks baru (label slider, tombol pengalih) berbahasa Indonesia.
