# Implementasi-etherchannel-menggunakan-LACP
tugas akhir semester

🔧 Penjelasan setiap perangkat
- 🖥️ PC1 dan PC2: Terhubung ke Switch 1 untuk mengirim dan menerima data.
- 🖥️ PC3 dan PC4: Terhubung ke Switch 2 untuk berkomunikasi melalui jaringan.
- 🔀 SW1: Switch pertama yang menghubungkan PC1 dan PC2.
- 🔀 SW2: Switch kedua yang menghubungkan PC3 dan PC4.
- 🔗 2 kabel antar-switch: Menghubungkan SW1 dengan SW2 menggunakan EtherChannel.
- ⚙️ LACP: Menggabungkan kedua kabel menjadi satu jalur logis secara otomatis.
  
🔄 Cara kerja topologi
1. 🖥️ PC1 mengirim data melalui SW1.
2. 🔀 SW1 meneruskan data ke SW2 melalui EtherChannel.
3. 🔀 SW2 meneruskan data ke PC3 atau PC4.
4. 🔌 Jika salah satu kabel terputus, kabel lainnya tetap bekerja sehingga koneksi masih tersedia.

🎯 Kesimpulan
Topologi ini dibuat untuk meningkatkan kecepatan transfer data dan menjaga koneksi jaringan agar tetap berjalan meskipun salah satu kabel penghubung mengalami gangguan.

📌 Intinya: Dua switch dihubungkan dengan dua kabel yang digabungkan menggunakan EtherChannel LACP.
