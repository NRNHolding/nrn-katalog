# nrn-katalog — Portfolio Radja Leather

Halaman portfolio publik. Baca live dari Google Sheet "NRN HUB" via Apps Script web app.

- Sumber data: endpoint publik (client-safe) — tidak pernah menampilkan pattern, harga, versi, atau klien yang belum beri izin.
- Update: ubah baris di Sheet NRN HUB → halaman ikut berubah (tanpa re-deploy).
- Ganti nama klien jadi publik/terjaga: kolom `klien_publik` (TRUE/FALSE) di Sheet.

Bagian internal (index aset, kelengkapan pattern) TIDAK ada di sini — itu file terpisah yang harus digate aksesnya.
