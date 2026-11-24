SISTEM CARIAN SLIP PENCAPAIAN MURID V2
SEKOLAH KEBANGSAAN PADANG HILIRAN

KANDUNGAN
- index.html : Muat naik ke root repository GitHub Pages
- Code.gs    : Salin ke Google Apps Script
- README.txt : Panduan ini

TETAPAN
Folder ID: 1iXkIhgEECUES8cDKq-W4wKBu3QwFNR6a
Apps Script Web App: https://script.google.com/macros/s/AKfycbxZuq4UEhzKyPrBwztHgtsAZeR4Ec70gAnVYAtoS4Npc66LhAnooVMIZ7zYn3urlhg6/exec
Format PDF: NoKP_JENISPENTAKSIRAN_TAHUN.pdf
Contoh: 120101011234_UASA_2026.pdf
        120101011234_UPSA_2026.pdf
        120101011234_PBD_AKHIR_2026.pdf

CARA PASANG APPS SCRIPT
1. Buka projek Apps Script asal bagi URL di atas.
2. Gantikan semua kandungan Code.gs dengan kod baharu dalam pakej.
3. Simpan; jalankan fungsi ujiSambungan dan luluskan akses Google Drive.
4. Deploy > Manage deployments > Edit > Version: New version > Deploy.
5. Gunakan deployment /exec yang sama. Deployment mesti dilaksanakan oleh akaun
   yang mempunyai akses ke folder Drive. Semak polisi akses organisasi.

CARA PASANG GITHUB
1. Buka repository GitHub.
2. Muat naik index.html ke root repository (gantikan fail lama).
3. Settings > Pages > Deploy from a branch > main / (root).
4. Uji dengan slip contoh menggunakan nombor KP rekaan.

REKA BENTUK / LENCANA
Lencana rasmi yang dibekalkan oleh pengguna:
https://iili.io/of0UXs9.jpg
Imej dimuat melalui pautan HTTPS ini terus daripada halaman index.html.
Oleh itu, paparan lencana memerlukan sambungan internet dan hos imej aktif.
Tema baharu menggunakan biru, merah, kuning emas dan putih seperti lencana.
Gradient header, hover button dan reka bentuk responsif dikekalkan.

KESELAMATAN
PENTING: sistem semasa menggunakan nombor KP sahaja; nombor KP bukan rahsia
atau bukti pengesahan identiti. Sebelum pelaksanaan sebenar, sekolah perlu
menambah pengesahan (contoh: kod akses individu) dan mendapat kelulusan yang
berkaitan. Web App akses 'Anyone' membolehkan sesiapa yang mengetahui nombor
KP mencari dokumen. Jangan guna data murid sebenar sebelum kawalan mencukupi.

NOTA TEKNIKAL
- Kod mencari semua PDF dalam folder yang mempunyai awalan no KP yang tepat.
- Klik Lihat PDF untuk pratonton atau Muat Turun untuk menyimpan.
- Fail PDF yang melebihi 8MB ditandai sebagai terlalu besar.
- Jika tiada hasil, periksa nama fail, akses folder, dan Apps Script deployment.
- Akses Drive sebenar tidak dapat diuji di sini.
