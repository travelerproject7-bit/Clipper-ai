# Clipper AI V2

## Tujuan
Frontend + backend awal untuk menganalisis transkrip video dan menghasilkan kandidat clip:
start, end, score, hook, reason.

## Penting
V2 tidak mengunduh atau melewati pembatasan YouTube. Untuk analisis nyata, backend perlu menerima transcript yang memang boleh diproses.

## Menjalankan
1. Install Node.js.
2. Masuk folder project.
3. Jalankan `npm install` dari folder `server`.
4. Set environment variable `OPENAI_API_KEY` di server.
5. Jalankan `npm start`.
6. Buka alamat server.

## Tahap berikutnya
Hubungkan transcript provider yang berwenang ke `analyzeTranscript()` pada `server/analyzer.js`.
Setelah analisis stabil, tambahkan modul FFmpeg untuk file video yang pengguna berhak proses.
