##APA ITU GIT

GIT merupakan bagian dari Version Control System. VCS adalah sistem yang mengelola perubahan dalam suatu dokumen.

**Kenapa harus menggunakan VCS?**
1. Mengatasi perubahan di file, dapat melihat history perubahan yang dilakukan
2. Memudahkan kita dalam berkolaborasi
3. Sharing proyek yang sudah dikerjakan

**Apa bedanya sama Gdrive dan Dropbox?**
Karena dua app ini tidak didesain untuk source code

##Version Control System(VCS)

VCS adalah ebuah sistem yang menyimpan ‘rekaman/snapshot’ perubahan pada source code. 
VCS ini dapat membuat kita:
1. Memungkinkan bekerja berkolaborasi dengan lebih baik
2. Mengetahui siapa yang melakukan dan kapan sebuah perubahan terjadi
3. Memungkinkan kita untuk kembali ke keadaan sebelum perubahan (checkout)

## Jadi apa itu Git?

Sebuah VCS yang memungkinkan kita untuk mengelola file di dalam folder. Folder di git disebut repository/repo. Git akan menyimpan riwayat perubahan yang dilakukan dengan menggunakan sesuatu yang dinamakan commit. Dalam commit kita tidak hanya menyimpan perubahan tersebut tapi juga menambahkan penjelasan fitur apa yang ditambahkan, bagian mana yang dihilangkan, dll. Dan setelah melakukan commit, git akan merekam snapshot tersebut. Setiap commit memiliki suatu penanda khusus berupa string acak yang disebut hash. Dalam sebuah commit juga terdapat keterangan berupa author (pembuat commit), waktu dibuatnya commit tersebut, dan juga pesan commit (commit message). Sebuah commit dapat dibuat cabang, proses ini disebut branch (cabang). Dan proses untuk menggabungkan 2 atau lebih branch disebut merge. Semua proses ini dapat dilakukan secara lokal di dalam komputer.

## Apa itu Github?

Layanan cloud untuk menyimpan dan mengelola project atau repo git.  Dalam github ini kita dapat melakukan semua proses yang dilakukan di git, seperti membuat repo, commit, merge, dan branch. Perbedaanya, semua proses dilakukan secara online di cloud.  

## Apa yang terjadi ketika Git dan Github digunakan secara bersamaan?

Kita dapat menyimpan project/ source code/ repo di github (push) dan dapat mengambil project/ source code/ repo dari github ke komputer kita (pull). Sesuatu yang di push dan pull ini adalah commit nya. Syarat melakukan ini adalah menjadikan github sebagai remote. Remote adalah sumber repo. Repo yang sudah dibuat di github di clone ke git yang ada di dalam komputer. Sehingga, repo di komputer dan di github tersambung. 

## Apa manfaat dari proses di atas?

Hal ini akan memudahkan kita untuk berkolaborasi dengan orang lain. Selain itu, kita juga dapat lebih mudah mengelola source code dan perubahannya.

## Istilah Git

Repo : Folder project
Commit : Rekaman/snapshot dari repo
Hash : Penanda unik dalam sebuah commit
Checkout : Berpindah ke sebuah commit
Branch : Cabang bebas dari sebuah commit
Merge : Menggabungkan branch
Remote : Sumber yang memiliki repo
Clone : Mengambil repo dari remote
Push : Mengirimkan commit ke repo
Pull : Mengambil commit dari repo
