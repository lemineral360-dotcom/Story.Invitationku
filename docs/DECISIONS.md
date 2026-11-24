# Decision log — new project
All project approvals PENDING. Starter kit rules are not project approvals. No historical master repository test claims apply to this project.
## New decision
- ID / date / topic:
- Status: PROPOSED / APPROVED / REJECTED / SUPERSEDED
- Context, options, decision, rationale and impact:
- Owner approval and exact revision/evidence:
Append decisions; preserve actual history once project starts.

## D-001 — Jenis acara saat peluncuran (24 November 2026 WIB)

- Status: APPROVED untuk keputusan cakupan ini. Planning Gate masih PENDING.
- Keputusan: versi pertama berfokus pada undangan pernikahan. Jenis acara lain di luar cakupan versi pertama.
- Bukti: jawaban pemilik pada wawancara Beginner Mode, “Ya, untuk pertamakali kita fokuskan ke undangan pernikahan”.

## D-002 — Pelanggan utama saat peluncuran (24 November 2026 WIB)

- Status: APPROVED untuk pilihan pelanggan utama. Planning Gate masih PENDING.
- Keputusan: calon pengantin menjadi pelanggan utama versi pertama.
- Dampak: alur pemilihan template, pengeditan, dan pembagian tautan dirancang berdasarkan kebutuhan calon pengantin yang mengurus undangan pernikahannya sendiri.
- Bukti: jawaban pemilik pada wawancara Beginner Mode, “Calon pengantin”.

## D-003 — Isi dan fitur halaman undangan (24 November 2026 WIB)

- Status: APPROVED untuk cakupan halaman undangan. Planning Gate masih PENDING.
- Keputusan: versi pertama memuat nama dan foto pasangan, jadwal dan lokasi akad atau pemberkatan serta resepsi, galeri foto, konfirmasi kehadiran (RSVP), dan kolom ucapan tamu.
- Bukti: pemilik menjawab “Ya boleh seperti itu” setelah daftar tersebut diajukan pada wawancara Beginner Mode.

## D-004 — Pengiriman undangan lewat WhatsApp (24 November 2026 WIB)

- Status: APPROVED untuk arah pengiriman. Planning Gate masih PENDING.
- Keputusan: calon pengantin memberikan daftar nama dan nomor WhatsApp tamu untuk pengiriman tautan undangan sekaligus ke daftar itu.
- Terbuka: pihak yang menekan tombol kirim, metode memasukkan daftar, identitas pengirim, biaya dan kelayakan layanan.
- Bukti: pemilik meminta daftar nama dan nomor WhatsApp dipakai untuk mengirim undangan sekaligus pada wawancara Beginner Mode.

## D-005 — Pihak yang memulai pengiriman WhatsApp (24 November 2026 WIB)

- Status: APPROVED untuk alur pengguna. Planning Gate masih PENDING.
- Keputusan: calon pengantin menekan tombol Kirim undangan dari dasbor pelanggan untuk memulai pengiriman sekaligus.
- Bukti: pemilik memilih “Calon pengantin” saat ditanya siapa yang menekan tombol Kirim undangan saat peluncuran.

## D-006 — Input langsung dan impor Excel (24 November 2026 WIB)

- Status: APPROVED untuk pilihan input daftar tamu. Planning Gate masih PENDING.
- Keputusan: sediakan input langsung di dasbor dan unggah Excel melalui templat standar.
- Bukti: pemilik menjawab “Sediakan keduanya” dan meminta templat untuk memudahkan pembacaan oleh sistem.
- Artefak: [Template-Daftar-Tamu-Story-Invitationku.xlsx](../templates/Template-Daftar-Tamu-Story-Invitationku.xlsx). Nama lembar dan judul kolom ada di PRD.

## D-007 — Nomor pengirim undangan (24 November 2026 WIB)

- Status: APPROVED untuk identitas pengirim yang diinginkan. Planning Gate masih PENDING.
- Keputusan: tamu menerima undangan dari nomor WhatsApp calon pengantin.
- Bukti: dalam wawancara Beginner Mode, pemilik menjawab “Dari nomor WhatsApp pengantin”.
- Kelayakan: [dokumentasi Meta](https://developers.facebook.com/documentation/business-messaging/whatsapp/overview) menjelaskan integrasi resmi untuk nomor WhatsApp Business. [Kebijakan WhatsApp Business](https://business.whatsapp.com/policy/preview?lang=id_ID) mewajibkan izin penerima dan templat pesan yang disetujui untuk memulai percakapan di platform bisnis. Kelayakan nomor dan templat untuk penggunaan proyek ini, biaya, serta pilihan jika nomor tidak memenuhi syarat masih terbuka.

## D-008 — Pilihan cadangan kirim WhatsApp per tamu (24 November 2026 WIB)

- Status: APPROVED untuk alur cadangan versi pertama. Planning Gate masih PENDING.
- Keputusan: jika nomor calon pengantin tidak dapat dipakai untuk pengiriman otomatis, calon pengantin dapat membuka WhatsApp per tamu dari dasbor dengan pesan dan tautan yang sudah terisi, lalu menekan Kirim sendiri.
- Bukti: pemilik menjawab “Ya boleh” terhadap usulan tombol Kirim via WhatsApp per tamu.

## D-009 — Model biaya saat peluncuran (24 November 2026 WIB)

- Status: APPROVED untuk model biaya saat peluncuran. Planning Gate masih PENDING.
- Keputusan: layanan versi pertama gratis bagi calon pengantin. Alur pembayaran pelanggan di luar cakupan rilis awal.
- Dampak: biaya operasional layanan, termasuk kemungkinan biaya WhatsApp otomatis, masih perlu diperkirakan.
- Bukti: pemilik memilih “Gratis” saat ditanya bagaimana biaya dikenakan kepada calon pengantin pada versi pertama.

## D-010 — Tautan undangan khusus per tamu (24 November 2026 WIB)

- Status: APPROVED untuk pilihan tautan. Planning Gate masih PENDING.
- Keputusan: setiap tamu mendapat tautan undangan khusus yang menampilkan nama tamu tersebut ketika dibuka. Pengiriman WhatsApp otomatis dan per tamu menggunakan tautan khusus.
- Bukti: pemilik memilih “Nomor 2” pada pilihan antara satu tautan untuk semua tamu dan tautan khusus per tamu.
- Terbuka: aturan akses ketika tautan diteruskan.

## D-011 — Akses langsung melalui tautan undangan (24 November 2026 WIB)

- Status: APPROVED untuk akses halaman undangan. Planning Gate masih PENDING.
- Keputusan: siapa pun yang memiliki tautan undangan yang berlaku dapat membukanya langsung tanpa akun atau kode akses, termasuk jika tautan diteruskan.
- Dampak: halaman tetap menampilkan nama tamu asal. Perlakuan konfirmasi kehadiran jika tautan diteruskan masih perlu dirinci.
- Bukti: pemilik menjawab “Bisa langsung buka” saat diberi pilihan antara akses langsung dan kode akses.

## D-012 — Pembuatan template dari tata letak siap pakai (24 November 2026 WIB)

- Status: APPROVED untuk alur pembuatan template. Planning Gate masih PENDING.
- Keputusan: superadmin memilih tata letak siap pakai, bisa mengganti warna, font, dan gambar sampul, lalu menerbitkan template ke katalog pelanggan. Penyusunan tata letak secara bebas berada di luar cakupan versi pertama.
- Bukti: pemilik memilih “1” dari pilihan tata letak siap pakai atau susun tata letak sendiri.

## D-013 — Jumlah undangan tercatat terkirim (24 November 2026 WIB)

- Status: APPROVED untuk definisi metrik dasbor superadmin. Planning Gate masih PENDING.
- Keputusan: gunakan jumlah undangan yang pengirimannya tercatat berhasil sebagai metrik “Undangan tercatat terkirim”. Klik yang membuka WhatsApp tidak dihitung sebagai pengiriman berhasil. Pembuatan tautan dan pembukaan undangan juga tidak dihitung sebagai pengiriman berhasil.
- Bukti: pemilik memilih “Undangan tercatat terkirim” dari opsi tautan siap dibagikan, tercatat terkirim, dan dibuka.
- Terbuka: sumber catatan untuk pengiriman manual, serta perlakuan untuk pengiriman ulang.

## D-014 — Dasbor superadmin berupa angka total (24 November 2026 WIB)

- Status: APPROVED untuk bentuk halaman dasbor. Planning Gate masih PENDING.
- Keputusan: halaman dasbor superadmin hanya memuat angka total, misalnya total pengguna serta total undangan yang tersebar atau dibuat. Definisi undangan tercatat terkirim tetap tercatat pada D-013.
- Dampak: tampilan dasbor cukup berupa ringkasan total. Daftar akhir metrik dan metode penghitungannya masih terbuka.
- Terbuka: apakah pembuatan template yang disepakati pada D-012 tetap tersedia melalui menu terpisah atau dikeluarkan dari versi pertama.
- Bukti: pemilik meminta dasbor superadmin berisi angka total saja, dengan contoh total pengguna dan total undangan.

## D-015 — Satu menu Kelola Template (24 November 2026 WIB)

- Status: APPROVED untuk struktur menu dan cakupan pengelolaan template. Planning Gate masih PENDING.
- Keputusan: menu Kelola Template untuk superadmin berisi Buat Template (Template Builder) dan Daftar Template. Daftar dapat diurutkan berdasarkan kategori dan menyediakan tindakan hapus. Builder mengikuti alur tata letak siap pakai pada D-012.
- Dampak: dasbor superadmin tetap berupa ringkasan angka total sesuai D-014. Keputusan ini menjawab letak fitur pembuatan template yang sebelumnya terbuka.
- Terbuka: penanganan penghapusan template yang sudah dipakai pelanggan.
- Bukti: pemilik meminta satu menu “Kelola Template” untuk membuat dan mengelola template, termasuk pengurutan kategori dan penghapusan.

## D-016 — Undangan tetap aktif setelah template dihapus dari katalog (24 November 2026 WIB)

- Status: APPROVED untuk kelangsungan undangan yang sudah terbit dan opsi masa aktif. Planning Gate masih PENDING.
- Keputusan: penghapusan template dari katalog tidak memutus tautan undangan yang sudah terbit. Tautan tetap dapat dibuka hingga akhir masa aktifnya. Pilihan masa aktif versi pertama adalah 1 bulan atau 2 bulan.
- Terbuka: awal perhitungan, cara memilih durasi, perlakuan draf, dan aturan setelah kedaluwarsa.
- Bukti: pemilik menjawab “Ya boleh” untuk mempertahankan tautan setelah penghapusan template dan menyebut pilihan 1 atau 2 bulan.
