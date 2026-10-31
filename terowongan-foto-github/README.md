# Terowongan Foto

Website romantis: terowongan 3D berisi foto yang melaju, lalu berganti otomatis tiap 30 detik ke galaksi foto
(matahari, planet, dan galaksi mini yang mengorbit). Lengkap dengan pemutar tiga lagu.

## Isi folder

- `index.html`: seluruh kode website (HTML, CSS, JavaScript dalam satu file)
- `audio/`: tiga lagu (mp3)
- `foto/`: 20 foto (`foto01.webp` sampai `foto20.webp`, 360×360 piksel)

## Cara membuka di komputer

Buka lewat server lokal supaya lagu dan foto termuat:

```
python3 -m http.server 8000
```

Lalu buka `http://localhost:8000`.

## Cara dipakai

- Tekan **Mulai**, lagu langsung berputar.
- Terowongan dan galaksi bergantian tiap 30 detik.
- Di galaksi: tekan dan tahan foto untuk memperbesar, geser layar ke arah mana saja untuk memutar galaksi.
- Tombol **Sembunyikan panel** di pojok kanan atas menyembunyikan daftar lagu.

## Mengganti foto atau lagu

- Foto: ganti file di `foto/` (nama dan jumlah tetap), atau ubah daftar `PHOTOS` di `index.html`.
- Lagu: ganti file di `audio/`, atau ubah daftar `SONGS` dan `TRACKS` di `index.html`.

## Catatan penting

- Repository ini sebaiknya **private**. Isinya foto pribadi dan lagu berhak cipta.
- GitHub Pages untuk repository private hanya tersedia di paket berbayar. Di paket gratis, Pages hanya untuk repository
  public. Jika dipublikasikan, siapa pun bisa melihat foto dan mengunduh lagunya, dan lagu berhak cipta berisiko
  dihapus oleh pemiliknya.
- Tombol **Pesan untuk pembuat** hanya berfungsi di dalam Claude. Di luar itu tombolnya disembunyikan otomatis.
