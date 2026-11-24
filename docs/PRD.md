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
| Tamu | Melihat informasi acara dan galeri, mengonfirmasi kehadiran, dan mengirim ucapan | Tautan undangan. Aturan akses menyusul. |
| Pemilik (superadmin) | Membuat template dan melihat angka kunjungan, jumlah pengguna, serta jumlah undangan yang dibagikan | Dasbor superadmin. Rincian akses menyusul. |

## Lingkup
**Fokus peluncuran:** Undangan pernikahan.
**Model biaya untuk pelanggan:** Gratis saat peluncuran.
**Cakupan usulan:** Halaman depan website (landing page), dasbor pelanggan, dan dasbor superadmin. Tautan yang dibagikan mengarah ke halaman undangan untuk tamu.
**Di luar cakupan versi pertama:** Undangan untuk jenis acara selain pernikahan dan alur pembayaran pelanggan. Batas fitur lainnya menunggu hasil wawancara.
**Asumsi dan ketergantungan:** Pemilik menginginkan pengiriman undangan sekaligus dari nomor WhatsApp calon pengantin. Perlu memvalidasi kelayakan nomor untuk integrasi resmi, persetujuan penerima, persetujuan templat pesan, dan biaya. Definisi angka di dasbor dan kewenangan tambahan superadmin belum diputuskan.

## Fitur prioritas
| ID | Fitur | Prioritas | Kriteria penerimaan | Status |
|---|---|---|---|---|
| F-001 | Halaman depan website | Belum ditentukan | Menunggu detail wawancara | Draf |
| F-002 | Katalog template, pengeditan undangan, dan pembagian tautan ke daftar tamu | Belum ditentukan | Menunggu detail wawancara | Draf |
| F-003 | Pembuatan template dan pemantauan aktivitas di dasbor superadmin | Belum ditentukan | Menunggu detail wawancara | Draf |
| F-004 | Isi halaman undangan pernikahan | Wajib | Tamu dapat melihat nama dan foto pasangan, jadwal dan lokasi akad atau pemberkatan serta resepsi, dan galeri foto. | Cakupan disepakati |
| F-005 | Konfirmasi kehadiran (RSVP) | Wajib | Tamu dapat mengirim konfirmasi kehadiran dari halaman undangan. | Cakupan disepakati |
| F-006 | Ucapan tamu | Wajib | Tamu dapat mengirim ucapan dari halaman undangan. | Cakupan disepakati |
| F-007 | Pengiriman undangan sekaligus melalui WhatsApp | Diminta untuk versi pertama | Calon pengantin dapat memulai pengiriman dari dasbor pelanggan untuk mengirim tautan undangan dari nomor WhatsApp calon pengantin ke daftar tamu dalam satu proses. | Alur utama disepakati, kelayakan layanan menunggu kajian |
| F-008 | Input dan impor daftar tamu | Wajib | Calon pengantin dapat menambah atau mengoreksi nama dan nomor WhatsApp di dasbor, mengunduh templat Excel, mengunggah .xlsx, dan memeriksa hasil impor sebelum memulai pengiriman. | Cakupan disepakati |
| F-009 | Kirim via WhatsApp per tamu | Wajib sebagai pilihan cadangan | Jika nomor calon pengantin tidak dapat dipakai untuk pengiriman otomatis, tombol per tamu membuka percakapan WhatsApp untuk nomor tamu tersebut dengan pesan dan tautan yang sudah diisi. Calon pengantin menekan Kirim di WhatsApp. Klik tombol hanya dicatat sebagai pembukaan WhatsApp jika aktivitas itu dilacak. | Cakupan disepakati |

### Format daftar tamu Excel
- Unduhan: [templat daftar tamu](../templates/Template-Daftar-Tamu-Story-Invitationku.xlsx).
- Baca lembar `Daftar Tamu`. Baris pertama berisi `Nama Tamu` dan `Nomor WhatsApp`. Data dimulai pada baris kedua. Lembar `Petunjuk` berisi panduan pengisian.
- Nama dan nomor wajib diisi untuk setiap baris data. Baca nomor sebagai teks agar awalan `0` atau `+` tetap utuh. Abaikan baris yang sepenuhnya kosong.
- Alur yang diusulkan: perlihatkan hasil impor untuk diperiksa dan dikoreksi sebelum menekan **Kirim undangan**. Pengunggahan file hanya menyiapkan daftar tamu.

## Alur pengguna
Alur awal pelanggan: pilih template, edit undangan, masukkan daftar nama dan nomor WhatsApp, lalu mulai pengiriman sekaligus dari dasbor pelanggan jika nomornya memenuhi syarat. Jika pengiriman otomatis tidak tersedia untuk nomor tersebut, calon pengantin membuka WhatsApp dari tombol per tamu dan menekan Kirim sendiri. Alur tamu: buka tautan, lihat informasi acara dan galeri, lalu dapat mengonfirmasi kehadiran atau mengirim ucapan. Rincian skenario dan kondisi khusus menyusul.

## Kebutuhan nonfungsional
Keamanan, privasi, aksesibilitas, performa, responsivitas, reliabilitas, dan backup: [isi sesuai proyek].

## Pertanyaan terbuka
- Pilihan satu tautan untuk semua tamu atau tautan masing-masing tamu yang menampilkan nama penerima.
- Aturan akses undangan, rincian konfirmasi kehadiran, serta aturan tampilan dan pengelolaan ucapan tamu.
- Aturan penanganan nomor tidak valid dan duplikat.
- Kelayakan integrasi dan persetujuan templat undangan, cara memperoleh persetujuan penerima, biaya layanan WhatsApp, perlindungan nomor tamu, serta cara mencatat status dan menghitung undangan yang dibagikan.
- Wewenang tambahan pemilik di dasbor superadmin.

## Planning Gate
- [ ] Masalah, tujuan, pengguna, dan scope lengkap
- [ ] Fitur dan prioritas disetujui
- [ ] Risiko dan asumsi dipahami
- [ ] Persetujuan eksplisit pemilik dicatat di docs/DECISIONS.md

**Status Planning Gate: PENDING**
