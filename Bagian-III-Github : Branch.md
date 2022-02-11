
### Branching

Branching dapat digunakan untuk:
- Membuat Git Branch
- Membuat snapshot tanpa mengganggu jalur utama (Master Branch)
- Fitur experimental, misal ingin menambahkan suatu fitur namun belum yakin akan keberhasilannya
- 2 orang dapat mengerjakan repo yang sama

 **Ada dua cara untuk membuat Branch**
1. Melakukan editing lalu saat melakukan commit, pilih option “Create a new branch for this commit..”.
2. Klik di bagian “Switch Branch” lalu create new branch. Tampilan pada branch seperti di copy paste dari master branch.

### Merging

Merging adalah melakukan penggabungan dua buah branch
Caranya klik “compare & pull request” lalu akan masuk ke bagian “Open a pull request”. Git ini dapat menentukan suatu branch dapat digabung atau tidak. 
Proses merge ini harus meminta izin pada pemilik master branch.

### Bagaimana jika terjadi conflict merge?

Hal ini dapat diselesaikan oleh pemilik Master Branch secara manual. Setelah conflict selesai, kita baru dapat melakukan merging.
