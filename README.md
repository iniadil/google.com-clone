# Klon Google Sederhana

Proyek ini adalah tampilan antarmuka pencarian Google yang dibuat dengan HTML, CSS, dan JavaScript.

## Fitur Utama

- Tampilan mirip Google dengan logo, kotak pencarian, dan tombol
- Fungsi pencarian menggunakan API DeepSeek
- Animasi loading saat pencarian
- Tampilan hasil dalam format Markdown
- Responsif untuk berbagai ukuran layar

## Cara Menggunakan

1. Buka file `google.html` di browser
2. Ketik query pencarian di kotak pencarian
3. Tekan Enter atau klik tombol pencarian
4. Hasil akan ditampilkan di bawah kotak pencarian

## Konfigurasi

Untuk menggunakan API DeepSeek:

1. Buat file `config.js` di folder yang sama
2. Isi dengan kode berikut:

```javascript
window.config = {
  DEEPSEEK_API_KEY: "API_KEY_ANDA_DISINI",
};
```

3. Ganti `API_KEY_ANDA_DISINI` dengan API key yang valid

## Catatan Keamanan

- Jangan membagikan API key Anda kepada siapapun
- File `config.js` sebaiknya tidak di-commit ke repository publik

## Lisensi

Proyek ini terbuka untuk umum dan dapat dimodifikasi sesuai kebutuhan.
