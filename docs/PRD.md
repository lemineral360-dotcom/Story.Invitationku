# Rencana produk — story.invitationku

**Status:** DRAF UNTUK TINJAUAN PEMILIK
**Versi:** 0.2
**Pemilik:** Pemilik story.invitationku
**Intake:** [Ringkasan proyek](PROJECT_INTAKE.md)

## Masalah dan tujuan

Calon pengantin perlu cara mudah untuk membuat undangan pernikahan, menyesuaikan desain siap pakai, dan membagikan tautan yang menyapa setiap tamu dengan namanya. Pemilik perlu cara untuk membuat template dan melihat angka total layanan.

Keberhasilan versi pertama diukur dengan uji alur lengkap. Calon pengantin dapat membuat dan menerbitkan undangan tanpa bantuan admin, memasukkan tamu langsung dan lewat Excel, serta membuka pesan WhatsApp yang sudah diisi untuk setiap tamu. Pada uji yang sama, dua tamu dengan nama berbeda mendapat sapaan yang sesuai, satu tamu dapat memberikan konfirmasi hadir dan ucapan, serta superadmin dapat menerbitkan template dan melihat ringkasan total. Gunakan data uji sintetis.

## Pengguna dan peran

| Peran | Kebutuhan dan akses |
|---|---|
| Calon pelanggan | Melihat penjelasan layanan gratis dan masuk ke alur membuat undangan dari halaman depan. |
| Calon pengantin | Memakai dasbor untuk memilih template, menyiapkan dan menerbitkan undangan, mengelola daftar tamu, dan membagikan tautan. Setiap akun hanya mengelola undangan dan daftar tamunya sendiri. |
| Tamu | Mengakses undangan melalui tautan aktif tanpa akun atau kode, melihat informasi acara, mengonfirmasi kehadiran, dan mengirim ucapan. |
| Superadmin | Melihat ringkasan angka total dan mengelola katalog melalui menu Kelola Template. |

## Cakupan peluncuran

Versi pertama gratis bagi calon pengantin dan berfokus pada undangan pernikahan. Tombol kirim WhatsApp per tamu wajib tersedia. Versi pertama boleh diluncurkan sebelum pengiriman WhatsApp otomatis siap.

Undangan untuk jenis acara lain, pembayaran pelanggan, serta penyusunan tata letak template secara bebas berada di luar cakupan versi pertama. Pengiriman otomatis tetap menjadi kebutuhan lanjutan sesuai alur yang disepakati. Sebelum diaktifkan, verifikasi kelayakan koneksi nomor pengantin, cara mendapatkan izin penerima, persetujuan templat pesan, dan biaya layanan.

## Fitur prioritas

| ID | Fitur | Prioritas | Kriteria penerimaan draf |
|---|---|---|---|
| F-001 | Halaman depan | Wajib | Pengunjung dapat memahami layanan undangan pernikahan gratis dan menemukan tombol untuk mulai membuat undangan. |
| F-002 | Katalog dan editor undangan | Wajib | Calon pengantin dapat memilih template terbit, mengisi konten, menyimpan draf, melihat pratinjau, lalu menerbitkan undangan. Draf belum dapat dibuka oleh tamu. |
| F-003 | Ringkasan dasbor superadmin | Wajib | Dasbor menampilkan angka total. Definisi dan usulan angkanya dirinci di bawah. |
| F-004 | Halaman undangan | Wajib | Tamu dapat melihat nama dan foto pasangan, jadwal dan lokasi akad atau pemberkatan serta resepsi, dan galeri foto. |
| F-005 | Konfirmasi kehadiran (RSVP) | Wajib | Tamu dapat mengirim konfirmasi dari halaman undangan. Calon pengantin dapat melihat hasilnya di dasbor. |
| F-006 | Ucapan tamu | Wajib | Tamu dapat mengirim ucapan dari halaman undangan. |
| F-007 | Kirim WhatsApp otomatis sekaligus | Dapat menyusul | Setelah syarat WhatsApp dipenuhi, calon pengantin dapat memulai pengiriman tautan ke daftar tamu dari dasbor dengan nomor WhatsApp sendiri. Fitur ini bukan syarat peluncuran. |
| F-008 | Input manual dan impor Excel | Wajib | Calon pengantin dapat menambah dan mengoreksi nama serta nomor WhatsApp secara langsung, atau mengimpor file .xlsx dan memeriksa hasilnya. |
| F-009 | Kirim via WhatsApp per tamu | Wajib | Tombol pada baris tamu membuka percakapan WhatsApp dengan pesan dan tautan khusus yang sudah diisi. Calon pengantin menekan Kirim dari akun WhatsApp sendiri. Klik pembuka WhatsApp tidak menambah angka terkirim. |
| F-010 | Tautan khusus per tamu | Wajib | Tautan menampilkan nama tamu asal, termasuk jika diteruskan. Siapa pun yang memiliki tautan aktif dapat membuka undangan langsung. |
| F-011 | Buat Template (Template Builder) | Wajib | Dari menu Kelola Template, superadmin memilih tata letak siap pakai, mengatur warna, font, dan gambar sampul, lalu menerbitkannya ke katalog. |
| F-012 | Daftar Template | Wajib | Superadmin bisa melihat dan mengurutkan template berdasarkan kategori, serta menghapusnya dari katalog. Undangan yang sudah terbit tetap bisa dibuka sampai masa aktifnya berakhir. |
| F-013 | Masa aktif undangan | Wajib | Calon pengantin memilih 1 atau 2 bulan saat menerbitkan undangan. Masa aktif dimulai saat penerbitan. Tautan kedaluwarsa berhenti menampilkan undangan. |

### Format daftar tamu Excel
- Unduhan: [templat daftar tamu](../templates/Template-Daftar-Tamu-Story-Invitationku.xlsx).
- Baca lembar `Daftar Tamu`. Baris pertama berisi `Nama Tamu` dan `Nomor WhatsApp`. Data dimulai pada baris kedua. Lembar `Petunjuk` berisi panduan pengisian.
- Nama dan nomor wajib diisi untuk setiap baris data. Baca nomor sebagai teks agar awalan `0` atau `+` tetap utuh. Abaikan baris yang sepenuhnya kosong.
- Perlihatkan hasil impor untuk diperiksa dan dikoreksi sebelum menekan **Kirim undangan**. Pengunggahan file hanya menyiapkan daftar tamu.

## Alur utama

1. Calon pengantin memilih template, mengisi informasi acara, melihat pratinjau, dan menyimpan draf.
2. Calon pengantin memasukkan daftar tamu secara langsung atau lewat Excel, memilih masa aktif, lalu menerbitkan undangan.
3. Dari daftar tamu, calon pengantin membuka pesan WhatsApp yang sudah terisi dan mengirimnya dari akun sendiri.
4. Tamu membuka tautan aktif, melihat sapaan nama dan isi undangan, lalu dapat mengisi konfirmasi kehadiran atau mengirim ucapan.
5. Superadmin memantau ringkasan angka total, dan membuat, menerbitkan, atau menghapus template dari menu Kelola Template.

## Usulan aturan untuk ditinjau pemilik

- **Masa aktif:** semua tautan tamu pada satu undangan memakai satu tanggal kedaluwarsa. Setelah itu, tampilkan pemberitahuan bahwa undangan sudah berakhir.
- **Daftar tamu:** tunjukkan baris yang tidak lengkap atau nomor yang perlu diperbaiki. Tandai nomor yang berulang untuk diperiksa karena satu nomor bisa digunakan oleh beberapa anggota keluarga.
- **Dasbor superadmin:** tampilkan total kunjungan halaman depan, total akun pelanggan, total undangan dibuat (jumlah undangan, bukan jumlah tautan per tamu), dan total undangan tercatat terkirim. Usulan pencatatan untuk kirim manual: pengantin dapat menekan **Tandai sudah dikirim** setelah mengirim di WhatsApp. Hitung satu kali per tautan tamu yang sudah ditandai, termasuk jika pesan dikirim ulang.
- **Konfirmasi dan ucapan:** mulai dengan pilihan hadir atau tidak hadir. Karena tautan bisa diteruskan, konfirmasi dari tautan yang sama dikaitkan dengan nama pada tautan itu. Detail perubahan konfirmasi serta tampilan dan moderasi ucapan perlu dirinci pada tahap desain.
- **Draf dengan template yang dihapus:** pertahankan isi draf dan beri petunjuk untuk memilih template aktif sebelum menerbitkan.

## Kualitas, asumsi, dan risiko

- Halaman undangan dan dasbor dapat digunakan di ponsel dan desktop. Label formulir, pesan kesalahan, dan navigasi harus mudah dipahami dan digunakan.
- Tautan undangan menampilkan nama tamu. Nomor WhatsApp disimpan di daftar tamu dan tidak ditampilkan di halaman undangan. Akses ke daftar tamu dibatasi. Rincian penyimpanan dan penghapusan data diputuskan pada tahap arsitektur.
- Pengiriman per tamu memerlukan satu langkah kirim di WhatsApp untuk setiap tamu. Pengiriman otomatis menunggu verifikasi integrasi resmi dan biaya. Biaya operasional website masih perlu diperkirakan sebelum rilis.
- Target pengujian impor adalah file Excel dengan baris valid, kosong, tidak lengkap, atau nomor berulang. Uji bahwa memuat file saja tidak memulai pengiriman.
- Sistem perlu melindungi draf pelanggan, menjaga tautan aktif saat template dikeluarkan dari katalog, dan mendukung pemulihan data. Rinci pendekatannya pada tahap arsitektur.

## Planning Gate

- [x] Masalah, tujuan, pengguna, dan lingkup dirangkum dalam draf.
- [ ] Fitur, prioritas, dan aturan usulan ditinjau dan disetujui pemilik.
- [ ] Risiko dan asumsi ditinjau pemilik.
- [ ] Persetujuan eksplisit pemilik dicatat di docs/DECISIONS.md dengan revisi yang ditinjau.

**Status Planning Gate: PENDING**
