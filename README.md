# The Oracle's Framework

Alat bantu penilaian saham berbasis kerangka kuantitatif ala Warren Buffett, dibuat sebagai Tugas Akhir mata kuliah Desain Sistem Informasi (Akuntansi, STIE YKPN Yogyakarta). Aplikasi web satu berkas (`index.html`), berjalan di peramban tanpa server.

Demo: https://otosakaayuu.github.io/Buffett-valuation/

> **Bukan rekomendasi investasi.** Hasil adalah alat bantu analisis yang sangat bergantung pada masukan dan penilaian pengguna.

## Delapan tahap
1. **Bisnis**: sektor, enam metrik keuangan (disesuaikan per sektor), checklist circle of competence
2. **Moat**: lima jenis moat, pricing power, retention rate
3. **Owner Earnings**: owner earnings dan DCF dua tahap (10 tahun + nilai terminal)
4. **Margin of Safety**: selisih harga pasar terhadap nilai intrinsik, gauge, matriks sensitivitas
5. **Manajemen**: enam kriteria bintang dan checklist
6. **Sector Intel**: catatan sektor
7. **Exceptions**: pelajaran dari pengecualian dan kesalahan Buffett
8. **Verdict**: skor 0–100 dan kategori

## Aturan skor (ringkas)
- Skor total = kualitas bisnis + moat + margin of safety + manajemen (masing-masing maks. 25).
- Kategori: ≥ 80 sangat sesuai, ≥ 60 sesuai dengan catatan, ≥ 40 pantau, < 40 tidak sesuai.
- Metrik berstatus "lewati" (mis. ROIC dan D/E pada bank) tidak dihitung; skor metrik diskalakan ke 30.
- Bank: owner earnings memakai laba yang dapat dibagikan = laba bersih × (1 − g/ROE).
- Perusahaan dengan owner earnings atau laba negatif tidak dihitung nilai intrinsiknya.

## Riwayat perubahan
- Perbaikan 6 bug penilaian (metrik lewati, D/E nol, perusahaan rugi, ambang kategori, pengali 15×, matriks sensitivitas)
- Pilihan mata uang dan label keputusan netral
- Verifikasi dan perbaikan kutipan Buffett
