# Design direction — DRAFT
Single source of truth for approved visual direction; DESIGN_APPROVAL.md records the approved revision.
## Brief
Landing page untuk calon pengantin yang akan membuat undangan pernikahan digital gratis. Rancang untuk ponsel dan desktop dengan satu ajakan utama yang mudah ditemukan.
## Direction — Elegan dan modern

Pemilik memilih opsi 2 pada 24 November 2026 WIB. Rincian di bawah adalah usulan untuk mockup pertama. Tinjauan mockup dan Design Gate belum selesai.

| Elemen | Usulan visual |
|---|---|
| Latar | Putih `#FFFFFF`; abu kehijauan sangat muda `#F4F6F1` untuk bagian yang perlu dibedakan. |
| Tombol utama | Hijau zaitun gelap `#3B472E` dengan tulisan putih. Gunakan untuk **Buat Undangan Gratis**. |
| Teks | `#252922` untuk judul dan isi, `#5D6558` untuk keterangan. |
| Huruf | Plus Jakarta Sans. Judul tebal, isi reguler, label tombol dan navigasi semi-bold. |
| Foto dan pratinjau | Satu pratinjau undangan di layar ponsel dengan foto pasangan bercahaya alami. Kartu katalog memperlihatkan contoh undangan dalam gaya yang berbeda. |
| Tata letak | Ruang kosong yang cukup antara bagian, garis pemisah tipis, tombol sekunder sederhana. Pertahankan urutan dan posisi elemen utama pada sketsa v0.1. |

Pemeriksaan awal warna: rasio kontras tulisan putih pada tombol zaitun adalah 9,87:1. Teks utama pada putih 14,80:1 dan teks keterangan pada putih 6,06:1. Kombinasi warna pada kartu, foto, dan keadaan interaktif ditinjau saat mockup tersedia.
## Rules
Avoid generic decoration, gratuitous gradients, inconsistent spacing and arbitrary components. Use realistic synthetic content. Record source/license for assets. No fixed brand/font is imposed by this kit.

## Konteks produk

story.invitationku membantu calon pengantin membuat undangan pernikahan gratis dan membagikan tautan khusus ke setiap tamu. Pengunjung pertama landing page perlu memahami hasil yang akan didapat, melihat contoh, dan menemukan cara memulai. Rujukan cakupan adalah [rencana produk v0.2](../docs/PRD.md). Arah visual elegan dan modern sudah dipilih. Pemilik memilih FigCraft untuk mockup yang dapat diedit.

## Landing page — urutan untuk sketsa

| Urutan | Bagian | Isi dan tindakan |
|---|---|---|
| 1 | Navigasi | Nama story.invitationku, tautan Template dan Cara Kerja, serta Masuk untuk pelanggan yang sudah punya akun. |
| 2 | Bagian pembuka (hero) | Judul usulan “Buat undangan pernikahan digital gratis”. Tampilkan satu pratinjau undangan di ponsel. Tombol utama **Buat Undangan Gratis** menuju alur pembuatan. Tautan **Lihat Template** menuju bagian katalog. |
| 3 | Pilihan template | Tampilkan beberapa contoh desain dengan nama dan pratinjau. Tautkan ke katalog lengkap agar pasangan bisa melihat contoh sebelum mulai. |
| 4 | Cara kerja | Pilih template, isi detail pernikahan dan daftar tamu, lalu terbitkan dan kirim tautan lewat WhatsApp per tamu. |
| 5 | Isi undangan | Tunjukkan secara singkat isi halaman tamu, terutama informasi acara, galeri, konfirmasi kehadiran, ucapan, dan sapaan dengan nama tamu. |
| 6 | Pertanyaan umum | Jawab pertanyaan tentang biaya, masa aktif 1 atau 2 bulan, dan cara tamu membuka tautan tanpa akun. |
| 7 | Ajakan penutup dan footer | Ulangi tombol **Buat Undangan Gratis** setelah pertanyaan umum. Tampilkan tautan pendukung yang sudah tersedia. |

Pada ponsel, judul dan tombol utama muncul sebelum pratinjau. Bagian pilihan template langsung mengikuti bagian pembuka. Gunakan contoh desain realistis dengan nama dan data sintetis. Pemilik menyetujui susunan ini untuk dijadikan sketsa awal pada 24 November 2026 WIB. Tinjauan visual dan prototipe masih menunggu.

### Sketsa v0.1

[Sketsa-Landing-Page-v0.1.pdf](Sketsa-Landing-Page-v0.1.pdf) berisi dua halaman, desktop dan ponsel. Keduanya memakai struktur yang sama. Di desktop pratinjau undangan berdampingan dengan judul. Di ponsel tombol utama tampil sebelum pratinjau, dan kartu template terlihat di bagian berikutnya. Nama, ucapan sapaan, dan nama template adalah contoh sintetis. Kotak silang menandai foto atau gambar pratinjau yang akan dipilih setelah arah visual ditetapkan.

Sketsa ini bersifat statis. Pada 24 November 2026 WIB, pemilik menyetujui posisi tombol utama dan contoh template pada [sketsa v0.1](https://github.com/lemineral360-dotcom/Story.Invitationku/blob/25bf8b0c9d47a844765425675dbbc704d93c485e/design/Sketsa-Landing-Page-v0.1.pdf). Persetujuan ini berlaku untuk penempatan pada sketsa. Mockup visual dan prototipe akan ditinjau pada tahap desain.

### Mockup FigCraft v0.1

[Mockup-Landing-Page-FigCraft-v0.1.svg](Mockup-Landing-Page-FigCraft-v0.1.svg) memuat dua kelompok lapisan, **Desktop** dan **Ponsel**. Teks, tombol, kartu, warna, dan ilustrasi tersusun sebagai elemen SVG terpisah. Contoh nama dan acara bersifat sintetis. Ilustrasi lanskap merupakan aset contoh buatan untuk mockup dan dapat diganti dengan foto pasangan pada revisi berikutnya.

Untuk memasukkan desain ke dokumen aktif, buka **File → Import from file…** pada FigCraft desktop dan pilih SVG. Gunakan **File → Open…** untuk membukanya sebagai dokumen baru, lalu simpan sebagai `.figcraft` jika diperlukan. [Panduan FigCraft](https://craft.wiki/apps/figcraft/workflows/#open-files-from-other-apps)

Struktur SVG, penamaan kelompok, dan keberadaan bagian utama diperiksa. Impor di FigCraft desktop dan uji prototipe belum dijalankan. FigCraft Live belum tersedia di sesi ini. Design Gate masih PENDING.
