# Modul 3: Rekayasa Media Digital dan Dasar CSS

Repositori kerja praktikum mata kuliah Pemrograman Website, Departemen Teknik Informatika, Fakultas Teknik, Universitas Hasanuddin.

| Keterangan | Rincian |
| --- | --- |
| Mata Kuliah | Pemrograman Website |
| Modul | 3 dari 11 |
| Topik | Rekayasa Media Digital dan Dasar CSS |
| Program Studi | Teknik Informatika |
| Institusi | Fakultas Teknik, Universitas Hasanuddin |

## Deskripsi Modul

Modul ini membahas penyisipan media digital secara natif serta dasar penataan tampilan dengan CSS. Pemahaman box model dan spesifisitas yang dibangun di sini menjadi prasyarat mutlak sebelum mempelajari Grid dan Flexbox pada modul berikutnya.

## Capaian Pembelajaran

Setelah menyelesaikan modul ini, mahasiswa diharapkan mampu:

1. **Mengintegrasikan media digital interaktif**
   - Menyisipkan audio dan video menggunakan elemen natif HTML5.
   - Menyediakan dukungan cadangan berkas bagi peramban yang tidak mendukung format tertentu.
2. **Merancang gambar responsif**
   - Mengombinasikan atribut srcset, sizes, dan elemen picture.
   - Memenuhi kebutuhan optimasi performa sekaligus seni tata letak.
3. **Menganalisis mekanisme cascading**
   - Memahami pewarisan dan aturan urutan gaya.
   - Menghitung formula spesifisitas pemilih secara presisi.
4. **Mengimplementasikan CSS Box Model**
   - Membedakan dampak content-box dan border-box.
   - Merancang dimensi elemen secara prediktif.

## Cakupan Materi

- Elemen media natif HTML5 beserta penyediaan berkas sumber cadangan.
- Gambar responsif melalui srcset, sizes, dan elemen picture untuk art direction.
- Mekanisme cascading, pewarisan, dan perhitungan spesifisitas pemilih.
- CSS Box Model serta perbedaan content-box dan border-box.
- Optimasi beban media dan metodologi penamaan kelas BEM.

## Hands-on Lab

Membangun halaman galeri pembelajaran interaktif dengan lembar gaya terpisah.

Kode hasil praktikum terbimbing pada sesi kelas disimpan di dalam repositori ini. Ikuti langkah demonstrasi yang dipandu dosen atau asisten, lalu bandingkan hasil pekerjaan Anda dengan berkas rujukan yang tersedia.

## Struktur Berkas

```
MK-Pemrograman-Website-Modul-03/
  assets/videos/demo-tutorial.mp4
  index.html
  style.css
  unhas_logo.png
```

## Petunjuk Penggunaan

### Kebutuhan Perangkat
1. Peramban modern seperti Google Chrome, Mozilla Firefox, atau Microsoft Edge.
2. Editor kode seperti Visual Studio Code.

### Langkah Menjalankan
1. Klon repositori ini ke komputer lokal Anda.
2. Buka direktori proyek melalui editor kode.
3. Jalankan berkas HTML utama melalui ekstensi Live Server agar halaman dilayani melalui protokol HTTP.
4. Amati hasil render pada peramban dan gunakan Developer Tools untuk menelusuri struktur maupun keluaran konsol.

Menjalankan berkas langsung dari sistem berkas dengan skema `file://` tidak dianjurkan karena sebagian fitur peramban, termasuk pengambilan data melalui jaringan, hanya bekerja pada protokol HTTP.

## Tugas Mandiri

### Pemutar Media Kuliah Responsif

**Skenario**

- Membuat komponen kartu multimedia untuk platform e-learning kampus.
- Kartu harus responsif dan memuat video, audio, serta ilustrasi sampul bergaya art direction.

**Spesifikasi Persyaratan**

1. Terapkan reset global menggunakan model border-box.
2. Buat elemen picture dengan minimal dua source berformat WebP yang dibedakan lewat query media lebar layar.
3. Sertakan pemutar video dengan poster pratinjau valid dan minimal dua format video cadangan.
4. Hiasi kartu mengikuti pola BEM dengan margin terpusat, bayangan, sudut melengkung, dan transisi lembut saat hover.
5. Buktikan pemahaman spesifisitas dengan gaya khusus yang menimpa teks deskripsi saat kartu memiliki kelas status tambahan.

**Berkas yang Dikumpulkan**

- `03-tugas-media-dan-css.html`
- `03-tugas-style.css`

Penamaan berkas wajib mengikuti ketentuan di atas. Berkas dengan penamaan yang tidak sesuai tidak akan diperiksa.

## Ketentuan Pengumpulan

1. Kerjakan tugas pada salinan lokal repositori ini.
2. Pastikan kode berjalan tanpa galat sebelum dikirim.
3. Simpan perubahan dengan pesan commit yang deskriptif.
4. Kirim hasil pekerjaan ke repositori daring sebelum tenggat yang ditetapkan.

```bash
git add .
git commit -m "Selesaikan tugas mandiri modul 3"
git push origin main
```

Riwayat commit menjadi bagian dari penilaian. Kerjakan secara bertahap dan hindari mengunggah seluruh pekerjaan dalam satu commit di akhir.

## Kriteria Penilaian

| Aspek | Bobot |
| --- | --- |
| Ketepatan pemenuhan spesifikasi | 40% |
| Kebenaran dan kerapian penulisan kode | 25% |
| Penerapan standar dan praktik terbaik | 20% |
| Kelengkapan dokumentasi dan riwayat commit | 15% |

## Integritas Akademik

Seluruh pekerjaan harus merupakan hasil karya sendiri. Pemanfaatan referensi dari sumber lain diperkenankan sepanjang dicantumkan sumbernya dan dipahami secara utuh. Penyalinan pekerjaan tanpa atribusi dikenai sanksi sesuai peraturan akademik yang berlaku.

## Lisensi

Materi pada repositori ini digunakan untuk keperluan pembelajaran di lingkungan Departemen Teknik Informatika, Fakultas Teknik, Universitas Hasanuddin.
