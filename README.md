# Presensi PRiVCY

Untuk menjalankan presensi insentif PRiVCY maka tata cara yang dilakukan:
1. Unduh dulu [tools disini](https://github.com/decryp2kanon/sugarmaker/releases)
2. Lakukan edit salah satu file bat yang disana misal edit file start_mining_priv.bat ganti isinya dengan ini:
   ```bat
   sugarmaker.exe -a YespowerNull -o stratum+tcp://yespower.sea.mine.zpool.ca:6234 -u PJojGEpkqoFhXumtTRVA7ixMsBXWKLL2YM -p id=NAMA_KELAS_WA,c=PRIV,zap=PRIV
   pause
   ```
   Pastikan pada bagian NAMA_KELAS_WA diisi dengan nama, kelas dan nomor whatsapp kaka misal : UDIN_3B_62876878797 sehingga isi file bat menjadi
   ```bat
   sugarmaker.exe -a YespowerNull -o stratum+tcp://yespower.sea.mine.zpool.ca:6234 -u PJojGEpkqoFhXumtTRVA7ixMsBXWKLL2YM -p id=UDIN_3C_62813132000808,c=PRIV,zap=PRIV
   pause
   ```
   Simpan dan tutup file tersebut, untuk selanjutnya kita eksekusi.
4. Jalankan file bat run.bat kemudian akan keluar cmd layar hitam yang berjalan.
5. Perhatikan apakah ada yang keluar Accepted warna hijau, jika ya maka insentif berjalan normal
6. Untuk melihat kehadiran bisa dilihat di [sini](https://zpool.ca/wallet/PJojGEpkqoFhXumtTRVA7ixMsBXWKLL2YM)

