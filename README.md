<h3 align="center"><img src="https://i.imgur.com/o8QXIco.png" alt="logo" height="100px"></h3>
<p align="center">The minimalist window manager.</p>

aphelia windows manager adalah sebuah file tunggal yang memiliki binary sangat kecil dan konsumsi sumber daya ruang yang kecil. aphelia wm hanya memiliki satu buah ruang kerja, tidak memiliki title bar dan windows border, tidak dapat 'meminimize', hanya dapat memunculkan program dengan dmenu dan mengerakan serta merubah ukuran tampilan program.

## pengaturan awal tombol keyboard

 * memunculkan tampilan program ke bagian belakang `Alt+a`
 * memunculkan tampilan program ke bagian atas `Alt+s`
 * menutup tampilan program `Alt+q`
 * membuka *Simple Terminal (st)* `Alt+Return`
 * membuka *dmenu* `Alt+d`
 * menutup window manager `Alt+Backspace`
 * menggerakan bilah program `Alt+Left Click`
 * merubah ukuran tampilan program  `Alt+Right Click`

kostumisasi pengaturan keyboard dapat merubah file `aphelia.c`

## Instalisasi

Instalisasi:
```
sudo make install
```

Uninstalisasi:
```
sudo make clean
```

Reinstalisasi:
```
sudo make reinstall
```

## kontribusi 

untuk berkotribusi cabangkanlah repositori ini dan apabila memiliki sesuatu yang ingin dibahas.
