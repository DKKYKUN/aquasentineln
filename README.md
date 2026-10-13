# Aqua Sentinel

Hal penting agar hasil AI tidak menyesatkan

Jangan menjanjikan akurasi 95% atau 99% tanpa pengujian. Model perlu dataset dan evaluasi yang sesuai.

Jangan membuat grafik dengan angka acak yang terlihat seperti data sensor asli. Mode demo harus diberi label.

Jangan menyamakan anomali dengan pencemaran. Kesalahan sensor, kalibrasi, dan perubahan lingkungan juga dapat menyebabkan pola yang tidak biasa.

Jangan menganggap model langsung siap saat pertama dijalankan. Isolation Forest membutuhkan baseline yang memadai dan telah diperiksa kualitasnya.

Jangan mengklaim air aman diminum hanya dari pH, TDS, dan suhu. Pemeriksaan parameter lain dan pengujian laboratorium mungkin diperlukan.

Saran pengerjaan: berikan master prompt tersebut kepada Lovable saat proyek referensi sudah dibuka atau diimpor. Jika Lovable tidak mampu menyelesaikan seluruh implementasi dalam satu proses, prioritaskan integrasi backend Python, penyimpanan data, dan dashboard real-time terlebih dahulu. Ketiganya merupakan fondasi agar Aqua Sentinel berfungsi sungguhan, bukan sekadar dashboard yang terlihat menarik. pastikan bisa di hosting di vercel

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/2cfbabe2-eb08-4fa1-9d02-6cad1dd3a235).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
