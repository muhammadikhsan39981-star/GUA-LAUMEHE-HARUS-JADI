# GUA LAUMEHE — Digital Cave Experience
Situs statis (HTML, CSS, JS, Leaflet, OpenStreetMap). Siap untuk GitHub Pages.

## Menjalankan
Buka `index.html`, atau jalankan `python3 -m http.server`. Untuk GitHub Pages: push, lalu Settings → Pages → branch `main`, folder `/root`.

## Gambar (taruh di `images/`)
`hero.jpg`, `peta-laumehe.png` (sudah terpasang, jangan diedit), `pintu-masuk.jpg`, `ruang-stalaktit.jpg`, `ruang-stalagmit.jpg`, `danau-biru.jpg`, `ruang-besar.jpg`, `ruang-akhir.jpg`, `gal-1.jpg` … `gal-6.jpg`.
Gambar yang belum ada otomatis tampil sebagai placeholder. Kompres ke WebP/JPG di bawah 300 KB agar cepat.

## Yang perlu Anda isi
- **Marker**: ubah `x` dan `y` (persen) di `POINTS` pada `script.js` agar pas dengan gambar mapping. Ini posisi pada gambar, bukan GPS.
- **Teks**: `desc`, `edu`, `safety`, dan `STORY` masih placeholder. Jangan isi sejarah atau legenda tanpa narasumber.
- **Virtual tour**: isi `TOUR.panorama` atau `TOUR.video` di `script.js`.
- **Media sosial**: ubah tautan `data-social` di footer.
- Data kedalaman (± 86 m) dan tracking (± 400 m) adalah informasi awal dan perlu diverifikasi.
