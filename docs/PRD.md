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
| Calon pengantin (pelanggan utama) | Memilih template, mengedit undangan, dan membagikan tautan kepada daftar tamu | Dasbor pelanggan. Rincian akses menyusul. |
| Tamu | Melihat informasi acara dan galeri, mengonfirmasi kehadiran, dan mengirim ucapan | Tautan undangan. Aturan akses menyusul. |
| Pemilik (superadmin) | Membuat template dan melihat angka kunjungan, jumlah pengguna, serta jumlah undangan yang dibagikan | Dasbor superadmin. Rincian akses menyusul. |

## Lingkup
**Fokus peluncuran:** Undangan pernikahan.
**Cakupan usulan:** Halaman depan website (landing page), dasbor pelanggan, dan dasbor superadmin. Tautan yang dibagikan mengarah ke halaman undangan untuk tamu.
**Di luar cakupan versi pertama:** Undangan untuk jenis acara selain pernikahan. Batas fitur lainnya menunggu hasil wawancara.
**Asumsi dan ketergantungan:** Cara pengiriman tautan, definisi angka di dasbor, dan kewenangan tambahan superadmin belum diputuskan.

## Fitur prioritas
| ID | Fitur | Prioritas | Kriteria penerimaan | Status |
|---|---|---|---|---|
| F-001 | Halaman depan website | Belum ditentukan | Menunggu detail wawancara | Draf |
| F-002 | Katalog template, pengeditan undangan, dan pembagian tautan ke daftar tamu | Belum ditentukan | Menunggu detail wawancara | Draf |
| F-003 | Pembuatan template dan pemantauan aktivitas di dasbor superadmin | Belum ditentukan | Menunggu detail wawancara | Draf |
| F-004 | Isi halaman undangan pernikahan | Wajib | Tamu dapat melihat nama dan foto pasangan, jadwal dan lokasi akad atau pemberkatan serta resepsi, dan galeri foto. | Cakupan disepakati |
| F-005 | Konfirmasi kehadiran (RSVP) | Wajib | Tamu dapat mengirim konfirmasi kehadiran dari halaman undangan. | Cakupan disepakati |
| F-006 | Ucapan tamu | Wajib | Tamu dapat mengirim ucapan dari halaman undangan. | Cakupan disepakati |

## Alur pengguna
Alur awal pelanggan: pilih template, edit undangan, lalu bagikan tautan kepada daftar tamu. Alur tamu: buka tautan, lihat informasi acara dan galeri, lalu dapat mengonfirmasi kehadiran atau mengirim ucapan. Rincian skenario dan kondisi khusus menyusul.

## Kebutuhan nonfungsional
Keamanan, privasi, aksesibilitas, performa, responsivitas, reliabilitas, dan backup: [isi sesuai proyek].

## Pertanyaan terbuka
- Aturan akses undangan, rincian konfirmasi kehadiran, serta aturan tampilan dan pengelolaan ucapan tamu.
- Cara pelanggan membagikan tautan dan cara menghitung undangan yang dibagikan.
- Wewenang tambahan pemilik di dasbor superadmin.

## Planning Gate
- [ ] Masalah, tujuan, pengguna, dan scope lengkap
- [ ] Fitur dan prioritas disetujui
- [ ] Risiko dan asumsi dipahami
- [ ] Persetujuan eksplisit pemilik dicatat di docs/DECISIONS.md

**Status Planning Gate: PENDING**
