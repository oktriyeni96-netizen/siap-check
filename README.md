# SIAP CHECK

Aplikasi statis gratis untuk analisis awal karya tulis ilmiah.

## Deploy ke Vercel
1. Ekstrak ZIP ini.
2. Masuk ke https://vercel.com/new dan login.
3. Pilih **Add New → Project** lalu impor folder/repository `siap-check` (atau unggah melalui GitHub).
4. Framework Preset: **Other**. Build Command dan Output Directory dikosongkan.
5. Deploy. Vercel akan memberikan URL publik.

## Fitur
- Tempel teks atau unggah TXT, DOCX, PDF.
- Tidak ada batas kata yang ditetapkan aplikasi; kapasitas praktis bergantung pada browser/perangkat.
- Perbandingan kemiripan lokal dengan teks referensi yang dimasukkan pengguna.
- Pencarian frasa melalui Google untuk pemeriksaan sumber secara manual.
- Indikator pola AI heuristik (bukan detektor AI tervalidasi).
- Unduh laporan TXT atau cetak/simpan sebagai PDF.

## Batasan penting
Tanpa API/basis data eksternal, aplikasi ini **tidak** dapat memindai seluruh internet atau database jurnal secara otomatis. Skor kemiripan hanya membandingkan teks dengan referensi yang ditambahkan. Skor AI tidak dapat membuktikan bahwa tulisan dibuat manusia atau AI. Jangan gunakan skor ini sebagai satu-satunya dasar keputusan akademik.

Dokumen diproses di browser; pustaka pembaca DOCX/PDF dimuat dari CDN sehingga fitur unggah memerlukan koneksi internet.
