# Product Requirements Document (PRD)

**Status:** DRAFT — wawancara awal.
**Nama proyek:** story.invitationku
**Pemilik:** Owner proyek
**Versi:** 0.1

## Masalah dan tujuan
- Calon pengantin perlu cara mudah untuk membuat undangan digital, menyesuaikan desain siap pakai, dan membagikan tautan kepada daftar tamu.
- Pemilik perlu satu tempat untuk membuat template dan memantau aktivitas website.
- Tujuan terukur: menunggu hasil wawancara.
- Indikator keberhasilan: menunggu hasil wawancara.

## Pengguna dan peran
| Peran | Kebutuhan | Hak akses |
|---|---|---|
| Pengunjung | Mengenal layanan dari halaman depan website | Akses halaman depan |
| Calon pengantin (pelanggan utama) | Memilih template, mengedit undangan, dan memulai pengiriman WhatsApp sekaligus dari dasbor pelanggan | Dasbor pelanggan. Rincian akses menyusul. |
| Tamu | Melihat informasi acara dan galeri, mengonfirmasi kehadiran, dan mengirim ucapan | Siapa pun yang memiliki tautan khusus yang berlaku dapat membuka undangan langsung tanpa akun atau kode akses. |
| Pemilik (superadmin) | Membuat dan mengelola template, serta melihat angka kunjungan, jumlah pengguna, dan jumlah undangan tercatat terkirim | Dasbor ringkasan dan menu Kelola Template. |

## Lingkup
**Fokus peluncuran:** Undangan pernikahan.
**Model biaya untuk pelanggan:** Gratis saat peluncuran.
**Cakupan usulan:** Halaman depan website (landing page), dasbor pelanggan, dan dasbor superadmin. Tautan yang dibagikan mengarah ke halaman undangan untuk tamu.
**Di luar cakupan versi pertama:** Undangan untuk jenis acara selain pernikahan, alur pembayaran pelanggan, dan penyusunan tata letak template secara bebas. Batas fitur lainnya menunggu hasil wawancara.
**Asumsi dan ketergantungan:** Pemilik menginginkan pengiriman undangan sekaligus dari nomor WhatsApp calon pengantin. Perlu memvalidasi kelayakan nomor untuk integrasi resmi, persetujuan penerima, persetujuan templat pesan, dan biaya. Definisi angka di dasbor dan kewenangan tambahan superadmin belum diputuskan.

## Fitur prioritas
| ID | Fitur | Prioritas | Kriteria penerimaan | Status |
|---|---|---|---|---|
| F-001 | Halaman depan website | Belum ditentukan | Menunggu detail wawancara | Draf |
| F-002 | Katalog template, pengeditan undangan, dan pembagian tautan ke daftar tamu | Belum ditentukan | Menunggu detail wawancara | Draf |
| F-003 | Ringkasan angka total di dasbor superadmin | Wajib | Halaman dasbor menampilkan angka total saja, seperti total kunjungan, total pengguna, dan total undangan tercatat terkirim. Total undangan yang dibuat menjadi kandidat angka tambahan. Klik pembuka WhatsApp tidak menambah angka terkirim. | Tampilan angka total disepakati. Daftar akhir metrik dan cara menghitungnya menyusul. |
| F-004 | Isi halaman undangan pernikahan | Wajib | Tamu dapat melihat nama dan foto pasangan, jadwal dan lokasi akad atau pemberkatan serta resepsi, dan galeri foto. | Cakupan disepakati |
| F-005 | Konfirmasi kehadiran (RSVP) | Wajib | Tamu dapat mengirim konfirmasi kehadiran dari halaman undangan. | Cakupan disepakati |
| F-006 | Ucapan tamu | Wajib | Tamu dapat mengirim ucapan dari halaman undangan. | Cakupan disepakati |
| F-007 | Pengiriman undangan sekaligus melalui WhatsApp | Diminta untuk versi pertama | Calon pengantin dapat memulai pengiriman dari dasbor pelanggan untuk mengirim tautan undangan dari nomor WhatsApp calon pengantin ke daftar tamu dalam satu proses. | Alur utama disepakati, kelayakan layanan menunggu kajian |
| F-008 | Input dan impor daftar tamu | Wajib | Calon pengantin dapat menambah atau mengoreksi nama dan nomor WhatsApp di dasbor, mengunduh templat Excel, mengunggah .xlsx, dan memeriksa hasil impor sebelum memulai pengiriman. | Cakupan disepakati |
| F-009 | Kirim via WhatsApp per tamu | Wajib sebagai pilihan cadangan | Jika nomor calon pengantin tidak dapat dipakai untuk pengiriman otomatis, tombol per tamu membuka percakapan WhatsApp untuk nomor tamu tersebut dengan pesan dan tautan yang sudah diisi. Calon pengantin menekan Kirim di WhatsApp. Klik tombol hanya dicatat sebagai pembukaan WhatsApp jika aktivitas itu dilacak. | Cakupan disepakati |
| F-010 | Tautan undangan khusus per tamu | Wajib | Setiap entri tamu memiliki tautan tersendiri. Saat tautan dibuka, halaman undangan menampilkan nama tamu yang sesuai. Pengiriman WhatsApp otomatis dan per tamu memakai tautan tersebut. Jika tautan diteruskan, halaman dapat dibuka tanpa verifikasi dan tetap menampilkan nama tamu asal. | Cakupan disepakati |
| F-011 | Buat Template (Template Builder) | Wajib | Di menu Kelola Template, superadmin dapat memilih tata letak siap pakai, mengganti warna, font, dan gambar sampul, lalu menerbitkan template ke katalog pelanggan. | Cakupan disepakati |
| F-012 | Daftar Template | Wajib | Di menu Kelola Template, superadmin dapat melihat daftar template, mengurutkannya berdasarkan kategori, dan menghapus template sesuai aturan penghapusan. | Cakupan disepakati. Aturan penghapusan menyusul. |

### Format daftar tamu Excel
- Unduhan: [templat daftar tamu](../templates/Template-Daftar-Tamu-Story-Invitationku.xlsx).
- Baca lembar `Daftar Tamu`. Baris pertama berisi `Nama Tamu` dan `Nomor WhatsApp`. Data dimulai pada baris kedua. Lembar `Petunjuk` berisi panduan pengisian.
- Nama dan nomor wajib diisi untuk setiap baris data. Baca nomor sebagai teks agar awalan `0` atau `+` tetap utuh. Abaikan baris yang sepenuhnya kosong.
- Alur yang diusulkan: perlihatkan hasil impor untuk diperiksa dan dikoreksi sebelum menekan **Kirim undangan**. Pengunggahan file hanya menyiapkan daftar tamu.

## Alur pengguna
Alur awal pelanggan: pilih template, edit undangan, masukkan daftar nama dan nomor WhatsApp, lalu mulai pengiriman sekaligus dari dasbor pelanggan jika nomornya memenuhi syarat. Jika pengiriman otomatis tidak tersedia untuk nomor tersebut, calon pengantin membuka WhatsApp dari tombol per tamu dan menekan Kirim sendiri. Alur tamu: buka tautan khusus dan lihat sapaan nama, informasi acara, serta galeri, lalu dapat mengonfirmasi kehadiran atau mengirim ucapan. Rincian skenario dan kondisi khusus menyusul.

## Kebutuhan nonfungsional
Keamanan, privasi, aksesibilitas, performa, responsivitas, reliabilitas, dan backup: [isi sesuai proyek].

## Pertanyaan terbuka
- Daftar akhir angka total di dasbor, arti undangan yang dibuat, dan sumber catatan terkirim untuk pengiriman manual.
- Rincian konfirmasi kehadiran, termasuk jika tautan diteruskan, serta aturan tampilan dan pengelolaan ucapan tamu.
- Aturan penanganan nomor tidak valid dan duplikat.
- Kelayakan integrasi dan persetujuan templat undangan, cara memperoleh persetujuan penerima, biaya layanan WhatsApp, perlindungan nomor tamu, serta cara mencatat status pengiriman.
- Aturan penghapusan template yang sudah dipakai oleh pelanggan.

## Planning Gate
- [ ] Masalah, tujuan, pengguna, dan scope lengkap
- [ ] Fitur dan prioritas disetujui
- [ ] Risiko dan asumsi dipahami
- [ ] Persetujuan eksplisit pemilik dicatat di docs/DECISIONS.md

**Status Planning Gate: PENDING**
