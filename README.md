# tomboltermux
Cara memunculkan tombol tersembunyi termux


impor  os
dari  waktu  tidur impor 


a  = ' \ 033 [92m'
b  = ' \ 033 [91m'
c  = ' \ 033 [0m'
os . sistem ( 'bersih' )
cetak ( a + ' \ t   Tombol Tambahan Termux' )
cetak ( a + ' \ t   ATAS, Bawah, kanan, Kiri, CTRL' )
cetak ( b + ' \ t   Bye: Kumpulan Remaja' )
cetak ( ' \ t web: Kumpulanremaja.com' )
cetak ( ' \ t Facebook: fb.me/elsadarengganis' )
cetak ( ' \ t Github: https://github.com/Yt-Real' )
cetak ( a + '+' * 40 )
cetak ( ' \ n Proses ..' )
tidur ( 1 )
print ( b + ' \ n [!] Berharap File Default Termux' )
tidur ( 1 )
coba :
      os . mkdir ( '/data/data/com.termux/files/home/.termux' )
kecuali :
      lulus
print ( a + '[!] Sukses!' )
tidur ( 1 )
cetak ( b + ' \ n [!] tambahkan File Tambahan ..' )
tidur ( 1 )

key  =  "extra-keys = [['ESC', '/', '-', 'HOME', 'UP', 'END', 'PGUP'], ['TAB', 'CTRL', 'ALT' , 'LEFT', 'DOWN', 'RIGHT', 'PGDN']] "
