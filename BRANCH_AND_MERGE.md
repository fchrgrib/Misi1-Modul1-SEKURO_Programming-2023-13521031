# Branch And Merge

## Overview

Pada sebelumnya kita sudah membahas tentang cara melakukan branch dan merge pada github.
Pada pembahasan kali ini akan membahas tentang cara melakukan branch and merge dengan menggunakan git.

## Cara Melakukan Branching Dan Merge Dengan Menggnunakan GIT

Pertama-tama buatlah folder telebih dahulu dan buatlah sebuah file berisi source code apa saja lalu copy alamat dari folder tersebut pada git bash.
setelah melakukannnya tambahkan file yang sudah kalian buat dengan melakukakan "git add" pada file yang sudah dibuat.
lalu cek dengan git status apakah file tersebut sudah ditambahkan atau tidak pada repository.
lalu lakukanlah "git commit -m (masukkan pesan)" setelah melakukan add agar file yang sudah di add tersimpan.
setelah melakukan hal tersebut buatlah terlebih dahulu sebuah branch yang ingin kita buat dengan cara "git branch (nama branch yang ingin dibuat)" dan klik enter.
lalu untuk mengecek apakah branch sudah dibuat atau belum kita bisa mengeceknya dengan cara "git branch" lalu cari nama branch yang baru kita buat apakah ada atau tidak.
cara pindah dari branch satu dengan branch lainnya adalah dengan cara mengetik "git checkout <nama branch>" lalu klik enter.
setelah itu kita cek kita sedang ada di branch mana dengan cara "git branch".
lalu buatlah sebuah file dan add commit file tersebut sehingga tersimpan pada branch yang baru kita buat.
jika kita ingin melakukan merge pada branch ke master maka kita ubah terlebih dahulu branch ke master lalu ketiklah "git merge <nama branch yang ingin di merge>" ketik enter dan branch akan tergabung pada branch master.

## Cara Menghapus Branch
Cara menghapus sebuah branch cukup simpel dengan mengetikkan "branch -d <nama branch yang ingin dihapus>" lalu tekan enter.
Branch yang dipilih akan terhapus. cek saja dengan menggunakan git status maka branch yang dipilih akan menghilang.

## Screenshot