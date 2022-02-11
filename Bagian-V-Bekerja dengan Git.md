
## Catatan Penting

Terdapat 3 area pada repo git, yaitu
1. Working area (folder tempat kita bekerja)
2. Staging area (kita ngasih tau git udah buat perubahan)
3. History (Perubahan yang sudah di-commit akan masuk ke history)

Staging area dan history akan disimpan dalam sebuah folder tersembunyi dengan nama .git 
Perubahan yang dilakukan di working area akan disimpan ke staging area dengan proses perintah git add. 
Perubahan yang di-commit tersebut akan disimpan ke history dengan perintah git commit. 

### Git Command (local)

$ git init → Melakukan inisialisasi folder untuk menjadi repo

$ git add→ Menambahkan file ke staging area, hal ini harus dilakukan sebelum melakukan commit

$ git status → Memberikan informasi mengenai file baru ataupun perubahan file

$ git commit -m “pesan commit” → Melakukan commit

$ git commit  -am “pesan commit” → Melakukan add dan juga commit, biasanya untuk commit data perubahan

$ git config → Mengisi data yang diperlukan sebelum melakukan commit

$ git add . → Add semua file

$ git log → Melihat semua perubahan (melihat commit yang sudah dilakukan)

$ git log-3 → Melihat commit 3 terakhir

$ git log -- nama file → Melihat commit yang spesifik mengenai suatu hal

$ git checkout xxxxx (5 digit awal hash suatu commit) → Melakukan checkout ke suatu commit
