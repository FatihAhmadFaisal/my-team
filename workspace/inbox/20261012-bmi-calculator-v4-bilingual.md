# Tugas v4: Kalkulator BMI — Versi Dwibahasa (Twillingo: Indonesia + English)

Dari: Wailan (Pemimpin tim)
Untuk: Taroko (anggota tim)
Tanggal: 2026-10-12

## Apa yang harus dikerjakan / What to do

Buat **versi 4** dari kalkulator BMI: **versi dwibahasa (twin language)** dengan **pengalih bahasa Indonesia / English**.

Aturan teknis:
- Berkas baru: `20261012-bmi-calculator-index-v4.html` (satu file, CSS/JS di dalam). **Jangan mengubah atau menghapus v1, v2, dan v3.**
- **Pertahankan SEMUA fitur v3**: mode "Ketik Manual" (bawaan) + "Gunakan Slider", sinkronisasi dua arah, tombol Hitung BMI / Reset, validasi input, hasil BMI + kategori, bar skala visual + jarum, rentang berat badan ideal, tabel referensi.
- **Tambahkan tombol pengalih bahasa** (misalnya "ID / EN" atau "Indonesia / English"), ditempatkan di header. Bahasa bawaan saat halaman dibuka: **Indonesia**.
- Saat bahasa diganti, **SEMUA teks berubah**, termasuk:
  - Judul & subjudul, label mode ("Ketik Manual" / "Gunakan Slider"), label input (Berat Badan / Tinggi Badan), satuan, placeholder.
  - Label & subtick slider, tombol (Hitung BMI / Reset).
  - Judul hasil, kategori (Kurus / Normal / Kelebihan berat badan / Obesitas → Underweight / Normal / Overweight / Obese), deskripsi tiap kategori, label skala visual, label kotak berat ideal, saran "tambah/turunkan berat badan", tabel referensi + judulnya.
  - **Semua pesan kesalahan** validasi.
- Pilihan bahasa harus **persisten selama sesi** (cukup simpan di variabel JS; tidak perlu localStorage, tapi boleh jika mudah).
- Hasil perhitungan yang sedang tampil ikut diterjemahkan saat bahasa diganti (tanpa perlu menekan Hitung ulang).
- Nilai angka (BMI, kg, cm) tidak berubah; hanya teks label.

## Format / cara menyimpan

- Simpan sebagai **file baru** di `workspace/outbox/`, nama: `20261012-bmi-calculator-index-v4.html`.
- V1, V2, V3 **tidak boleh diubah atau dihapus**.
- Tulis satu baris catatan serah-terima di outbox (apa yang dikerjakan, hal yang perlu diperhatikan, siap dipakai atau belum).

## Tanda selesai / What "done" looks like

- File `20261012-bmi-calculator-index-v4.html` ada di outbox; v1–v3 masih utuh.
- Halaman terbuka dalam bahasa Indonesia; semua teks awal berbahasa Indonesia.
- Klik pengalih ke English → seluruh antarmuka berbahasa Inggris, termasuk kategori hasil dan pesan kesalahan.
- Masukkan 70 kg / 175 cm di kedua bahasa → hasil sama (BMI 22,9 → Normal; English: Normal), hanya teksnya yang berbeda.
- Geser slider ke 0 kg di mode English → pesan kesalahan muncul dalam bahasa Inggris.
- Semua fitur v3 (mode ketik, slider, sinkronisasi, bar skala, berat ideal) tetap berfungsi di kedua bahasa.
