# Prototipe Sistem Informasi Turnamen E-Sports

Prototipe antarmuka untuk tugas Ujian Akhir Semester mata kuliah **Analisis dan Perancangan Sistem Informasi**, Universitas Esa Unggul.

Prototipe ini merupakan rancangan antarmuka (mockup) berbasis HTML dan CSS yang menggambarkan tujuh halaman utama sistem. Prototipe bersifat statis, artinya belum terhubung dengan basis data maupun logika pemrosesan di sisi server, sesuai ketentuan tugas yang tidak mewajibkan tahap implementasi.

## Cara membuka

Buka tautan GitHub Pages repositori ini, atau unduh seluruh berkas lalu buka `index.html` melalui peramban.

## Daftar halaman

| Halaman | Berkas | Keterangan |
| ------- | ------ | ---------- |
| Login | `index.html` | Halaman masuk pengguna |
| Dashboard | `dashboard.html` | Ringkasan turnamen, bagan, dan jadwal |
| Data Tim Peserta | `data-tim.html` | Daftar tim beserta status verifikasi |
| Tambah Tim | `tambah-tim.html` | Formulir tim dan roster pemain |
| Input Hasil | `input-hasil.html` | Pencatatan skor dan bukti pertandingan |
| Laporan | `laporan.html` | Rekapitulasi dan ekspor laporan |
| Profil & Pengaturan | `pengaturan.html` | Data akun dan preferensi notifikasi |

## Alur penelusuran yang disarankan

1. Dari halaman login, tekan tombol **Masuk**.
2. Gunakan **menu di sisi kiri** untuk berpindah antarhalaman.
3. Pada halaman Data Tim, tekan **+ Tambah Tim** untuk membuka formulir.
4. Tekan **kotak profil** di bagian bawah menu untuk kembali ke halaman login.

Menu yang belum memiliki halaman rancangan (Turnamen, Bracket & Jadwal, Sengketa) sengaja dibiarkan tidak dapat diklik.

## Prinsip perancangan yang diterapkan

- **Konsistensi** — tata letak, warna, dan istilah seragam pada seluruh halaman.
- **Kemudahan navigasi** — penunjuk lokasi halaman dan penandaan menu aktif.
- **Keterbacaan** — ukuran huruf memadai dan kontras warna mencukupi.
- **Kesederhanaan** — informasi penting ditampilkan lebih dahulu.
- **Umpan balik sistem** — status ditandai warna hijau (berhasil), kuning (menunggu), dan merah (ditolak).
- **Kesesuaian warna dan ikon** — warna aksi utama dibedakan dari aksi sekunder.

## Catatan teknis

Prototipe dirancang untuk lebar layar minimal 1180 piksel. Apabila tampilan terpotong, perkecil tingkat perbesaran peramban dengan menekan `Ctrl` dan `-`.

## Penyusun

[NAMA MAHASISWA] — NIM [NIM]
