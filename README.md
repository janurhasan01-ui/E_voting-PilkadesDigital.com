# Simulasi E-Voting Pilkades Desa Telukbuyung

Website statis HTML untuk demonstrasi antarmuka e-voting dan undangan QR.

## Isi proyek
- `index.html` — halaman utama.
- `assets/calon-1.jpeg` — foto calon nomor urut 1 yang ditampilkan pada kartu dan layar konfirmasi.

## Jalankan secara lokal
Buka `index.html` di browser. Untuk pengujian kamera QR, browser biasanya memerlukan HTTPS atau localhost dan izin kamera.

## Publikasikan dengan GitHub Pages
1. Buat repository baru di GitHub.
2. Unggah `index.html` dan folder `assets/` (atau unggah isi ZIP ini).
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu proses selesai; GitHub akan menampilkan URL situs.

## Penting
Ini hanya **simulasi/demo**. Jumlah suara disimpan dalam variabel JavaScript di halaman dan akan kembali ke nol saat halaman dimuat ulang. Tidak ada autentikasi, database, audit trail, verifikasi pemilih yang aman, atau perlindungan terhadap suara ganda. Jangan gunakan untuk pemungutan suara resmi atau menyimpan data pemilih sungguhan. Sebelum penggunaan nyata, sistem perlu dirancang dan diaudit secara profesional serta mendapat persetujuan otoritas terkait.


Foto kandidat nomor 1 disimpan secara lokal di `assets/calon-nomor-1.jpeg`. Pastikan folder `assets` ikut diunggah ke GitHub bersama `index.html`.
