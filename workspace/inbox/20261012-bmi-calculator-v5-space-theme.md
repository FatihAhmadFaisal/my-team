# Tugas v5: Kalkulator BMI — Tema Luar Angkasa + Fakta Planet (Kid-Friendly)

Dari: Wailan (Pemimpin tim)
Untuk: Taroko (anggota tim)
Tanggal: 2026-10-12

## Apa yang harus dikerjakan / What to do

Buat **versi 5**: kalkulator BMI dengan **tema luar angkasa (space theme)** dan **kutipan fakta planet** untuk tiap hasil BMI.

Aturan teknis:
- Berkas baru: `20261012-bmi-calculator-index-v5.html` (satu file, CSS/JS di dalam, **tanpa library/gambar luar** — semua planet & bintang digambar dengan CSS). **Jangan mengubah atau menghapus v1–v4.**
- **Pertahankan SEMUA fitur v4**: dwibahasa ID/EN + pengalih bahasa, mode "Ketik Manual" (bawaan) + "Gunakan Slider", sinkronisasi dua arah, Hitung BMI / Reset, validasi, hasil BMI + kategori, bar skala visual + jarum, rentang berat ideal, tabel referensi.

### 1. Tema Luar Angkasa (background)
- Latar berubah jadi langit malam berbintang: warna gelap (mis. gradasi hitam–biru tua), bintang-bintang kecil (boleh berkelip pelan dengan CSS animation), wajib **tetap mudah dibaca** — teks dan kartu tidak boleh hilang di atas latar gelap.
- Tampilan card/kalkulator menyesuaikan tema (warna tombol, kartu, teks menyesuaikan supaya kontras aman).

### 2. Satu Planet per Kategori (tampil saat hasil muncul)
Saat tombol Hitung BMI ditekan, tampilkan **satu planet** di dalam kartu hasil sesuai kategori hasil. Ganti planetnya tiap kategori berubah:
| Kategori BMI | Planet | Fakta nyata yang boleh dipakai (WAJIB akurat) |
|---|---|---|
| Underweight / Kurus | **Mars** | Planet kecil, tetapi punya gunung berapi TERTINGGI di tata surya (Olympus Mons). |
| Normal | **Bumi (Earth)** | Planet kita sendiri; satu-satunya yang diketahui punya kehidupan & air cair. |
| Overweight / Kelebihan | **Jupiter** | Planet TERBESAR; seperti perisai raksasa yang melindungi Bumi dari komet. |
| Obesitas | **Saturnus (Saturn)** | Raksasa es yang begitu ringan sampai bisa "mengapung" di air; terkenal cincinnya dari es & batu. |

- Gambar planet dengan CSS (bulat + warna/cincin khas: Mars jingga, Bumi biru-hijau, Jupiter garis cokelat + Bintik Merah Raksasa, Saturnus kuning + cincin miring).
- Ganti warna/aksen kartu hasil mengikuti planet yang tampil (boleh samarkan, yang penting kontras aman).
- Planet ikut berubah saat pengguna mengganti bahasa? TIDAK perlu — planet bergantung kategori hasil, bukan bahasa.

### 3. Kutipan Fakta Planet (1 kutipan tiap hitungan, dari kumpulan)
- Sediakan **kumpulan 3–5 kutipan per kategori** (total 12–20 kutipan). Setiap kali Hitung BMI ditekan, **pilih satu acak** dari kumpulan kategori itu, supaya hasil berulang terasa segar.
- **Setiap kutipan WAJIB berisi fakta planet yang benar** sesuai tabel di atas (Mars→Underweight, Bumi→Normal, Jupiter→Overweight, Saturnus→Obesitas). Jangan mengarang fakta; kalau ragu, pakai fakta dari tabel.
- **Gaya bahasa untuk anak SD (mudah dipahami anak)**: kalimat pendek (maks. ± 12 kata), kata sehari-hari, boleh pakai seruan ramah ("Wah!", "Tahukah kamu?"). **Tanpa istilah medis rumit.**
- **Nada harus ramah & menyemangati, TIDAK menghakimi** tentang berat badan. Fokus ke keajaiban planet, bukan ke cacat/masalah tubuh.
- **Dwibahasa**: tiap kutipan ada versi Indonesia DAN English. Saat pengalih bahasa dipakai, kutipan yang sedang tampil ikut berganti bahasa **tanpa perlu hitung ulang** (sama seperti perilaku teks hasil di v4).

## Format / cara menyimpan
- Simpan sebagai **file baru** di `workspace/outbox/`, nama: `20261012-bmi-calculator-index-v5.html`.
- V1–V4 **tidak boleh diubah atau dihapus**.
- Tulis satu baris catatan serah-terima di outbox (apa yang dikerjakan, hal yang perlu diperhatikan, siap dipakai atau belum).

## Tanda selesai / What "done" looks like
- File `20261012-bmi-calculator-index-v5.html` ada di outbox; v1–v4 masih utuh.
- Halaman terbuka dengan latar luar angkasa berbintang; semua teks tetap terbaca jelas.
- Hitung 70 kg / 175 cm → hasil Normal → muncul **Bumi** + kutipan fakta Bumi (bukan Mars/Jupiter/Saturnus).
- Ulangi Hitung beberapa kali dengan nilai sama → **kutipan berbeda-beda** (terbukti dari kumpulan), planet tetap Bumi.
- Geser ke 0 kg → validasi tetap muncul, dalam bahasa yang aktif.
- Ganti ke English → **kutipan ikut berbahasa Inggris**, teks hasil berubah, planet tetap menampilkan kategori yang sama.
- Semua fakta planet di kutipan benar (sesuai tabel) dan kalimatnya enak dibaca anak.
- Semua fitur v4 tetap berfungsi di kedua bahasa.
