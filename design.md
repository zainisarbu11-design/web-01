# Design Brief — Travel Landing Page

## Arah visual

Buat landing page travel dengan nuansa petualangan alam yang sinematik, tenang, dan premium. Gunakan foto pegunungan, danau, hutan, serta air terjun sebagai elemen visual utama. Referensi menunjukkan halaman gelap dengan foto besar, overlay hitam, aksen turquoise, dan ruang kosong yang cukup agar teks tetap terbaca.

## Sasaran pengalaman

- Mengundang pengunjung menjelajahi destinasi dan paket tur.
- Menonjolkan fotografi alam dan suasana perjalanan.
- Menyediakan navigasi singkat menuju bagian utama halaman.
- Menjaga teks, tombol, dan tautan mudah dibaca di desktop maupun ponsel.

## Struktur halaman

### 1. Header dan navigasi

- Letakkan logo teks sederhana di kiri atas.
- Tampilkan navigasi ringkas: Home, About Us, Tours, Gallery, Reviews, Contact.
- Sediakan ikon pencarian di sisi kanan bila pencarian benar-benar tersedia.
- Gunakan latar transparan di atas hero dan pastikan navigasi tetap terbaca.

### 2. Hero utama

- Gunakan foto lanskap pegunungan dan danau sebagai latar penuh lebar.
- Tambahkan overlay gelap bertingkat agar teks kontras tanpa menutupi foto sepenuhnya.
- Letakkan label atau judul besar berwarna turquoise, misalnya “TIME TO TRAVEL”.
- Tambahkan deskripsi singkat dan tautan ajakan bertindak seperti “Explore destinations”.
- Sediakan indikator beberapa slide di sisi kanan hanya jika hero benar-benar berupa carousel.
- Pada bagian bawah hero, tampilkan tiga ringkasan manfaat perjalanan dengan ikon garis sederhana.

### 3. Bagian tur populer

- Gunakan latar hitam atau charcoal untuk memberi jeda dari hero.
- Letakkan judul dan deskripsi pendek di tengah.
- Tampilkan empat kartu destinasi dalam satu baris pada layar lebar.
- Setiap kartu berisi foto, nomor atau nama tur, dan keterangan satu baris.
- Beri garis turquoise tipis atau glow halus pada kartu aktif/hover. Hindari animasi berlebihan.

### 4. Bagian eksplorasi dan video

- Gunakan foto hutan atau lanskap udara sebagai latar bagian.
- Letakkan headline besar di sisi kiri, dengan aksen turquoise dan baris yang pendek.
- Sertakan tombol “Watch the video” dengan ikon play yang jelas.
- Di sisi kanan, buat kolase thumbnail video dengan rasio yang bervariasi dan ikon play di atas tiap thumbnail.
- Tambahkan deskripsi singkat di bawah tombol, dengan ukuran teks yang nyaman dibaca.

### 5. Footer sosial

- Gunakan latar gelap polos.
- Tampilkan ikon media sosial secara ringkas dan sejajar di tengah.
- Gunakan tautan nyata dan label aksesibel untuk setiap ikon.

## Sistem visual

### Warna

- Latar utama: `#050707` atau hitam lembut.
- Panel/kartu: `#101514`.
- Aksen turquoise: `#39D1C8`.
- Teks utama: `#F4F6F5`.
- Teks sekunder: `#A6B0AD`.
- Garis pembatas: `#26302E`.

Gunakan turquoise untuk judul penting, ikon, keadaan hover, dan penanda aktif. Jangan gunakan aksen pada setiap elemen sekaligus.

### Tipografi

- Gunakan sans-serif modern dengan bentuk geometris untuk judul.
- Judul hero dan bagian eksplorasi: huruf kapital, tebal, rapat, dan berukuran besar.
- Paragraf: ukuran sedang, warna abu-abu terang, lebar baris terbatas.
- Navigasi dan label kecil: huruf kapital seperlunya dengan jarak huruf ringan.

### Foto dan overlay

- Pilih foto alam dengan komposisi lebar dan subjek yang masih terlihat di area teks.
- Gunakan `background-size: cover` untuk hero.
- Tambahkan gradient gelap dari kiri/bawah untuk keterbacaan.
- Untuk kartu, gunakan foto yang berbeda-beda dan crop konsisten.
- Hindari placeholder kosong atau foto yang tidak terkait perjalanan.

### Bentuk dan jarak

- Pertahankan layout bersih dengan margin lebar dan jarak vertikal yang jelas antarseksi.
- Gunakan sudut kartu sedikit membulat atau hampir kotak; hindari bentuk pil yang berlebihan.
- Pembatas tipis dan bayangan halus lebih sesuai daripada panel bercahaya kuat.
- Pastikan fokus visual utama tetap pada foto dan judul.

## Responsif

- Desktop: hero lebar penuh; kartu tur empat kolom; area eksplorasi dua kolom.
- Tablet: kartu tur dua kolom; navigasi dapat diringkas; kolase video tetap di samping teks bila ruang cukup.
- Ponsel: susun konten satu kolom, gunakan menu ringkas, kurangi tinggi hero, dan pindahkan indikator slide agar tidak menutupi teks.
- Jangan memotong wajah atau titik fokus pada foto saat ukuran layar berubah.
- Cegah overflow horizontal pada kartu dan kolase.

## Interaksi dan aksesibilitas

- Semua navigasi dan tombol harus berupa tautan atau tombol yang benar-benar berfungsi.
- Tampilkan keadaan hover dan keyboard-focus yang terlihat.
- Pastikan kontras teks memadai di atas foto; jangan mengandalkan warna saja untuk menunjukkan pilihan aktif.
- Beri teks alternatif yang menjelaskan foto secara singkat.
- Ikon tanpa teks harus memiliki label aksesibel.
- Hormati `prefers-reduced-motion`; gunakan transisi lembut dan singkat.
- Jangan membuat carousel, pencarian, atau pemutar video palsu. Jika fitur belum tersedia, gunakan tautan yang jelas atau hilangkan kontrol tersebut.

## Catatan implementasi

Dokumen ini adalah arahan desain berdasarkan gambar referensi, bukan spesifikasi konten final. Gunakan foto dan teks yang memang tersedia dalam proyek. Pertahankan struktur semantik HTML, pisahkan stylesheet, dan hindari menambahkan dependensi tanpa kebutuhan.
