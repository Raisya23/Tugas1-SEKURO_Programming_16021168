
### Catatan 

Head adalah penanda branch mana yang sedang aktif

$ git branch <nama_branch> → perintah untuk membuat branch

contoh : $ git branch baru

$ git log --all --decorate --oneline --graph → perintah melihat visualisasi commit

$ alias graph=”git log --all --decorate --oneline --graph” → Biar ga panjang ngetik

$ git checkout <nama_branch> → perintah untuk mengaktifkan branch, atau edit di branch gitu lah

#### Jenis Merge

1. Fast forward merge 
   Terjadi ketika branch yang ingin diganbungkan berada di jalur langsung atau direct path.
2. Three-way merge
   Terjadi ketika tidak ada direct path, jadi melakukan merge sekaligus commit, membuat commit baru nantinya.

$ git merge <nama_brach> → perintah menggabungkan branch ke master branch
saat proses ini, pointer head harus berada di posisi master, jadi lakukan checkout dulu

$ git branch -d <nama_branch> → menghapus branch yang sudah tidak diperlukan setelah di merge

$ git branch --merged → melihat branch mana yang sudah di merge

$ git branch -D <nama_branch> → menghapus branch
