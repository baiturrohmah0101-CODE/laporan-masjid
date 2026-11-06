# Laporan Keuangan Masjid Baiturrohmah

Halaman laporan keuangan (hanya-baca) yang tampil baik di HP dan komputer.

- Data **tidak disimpan di repo ini**. Data diambil langsung dari spreadsheet lewat Apps Script setiap kali halaman dibuka.
- Halaman hanya menampilkan data bila dibuka dengan **link lengkap dari pengurus** (ada bagian setelah tanda `#`).
  Tanpa itu halaman hanya menampilkan "Link tidak lengkap".
- Halaman diberi tanda `noindex` dan `robots.txt` agar tidak muncul di mesin pencari.

`index.html` dibuat otomatis dari kode Apps Script web laporan (`build_static.py`); jangan diedit manual.
