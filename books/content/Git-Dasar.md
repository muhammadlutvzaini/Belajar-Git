# بِسْمِ اللهِ الرَّحْمَنِ الرَّحِيْم 

----

# A. Git Dasar

---

## 1. Pengenalan Version Control

---

#### Sebelum Ada Version Control System

Saat mengerjakan sebuah **project / pekerjaan** kita akan sering sekali melakukan revisi, biasanya kita akan menyimpan project pertama dengan nama **Project_1**, setelah mendapat revisi, kita akan simpan dengan nama **Project_2**, jika masih terdapat revisi akan di simpan dengan nama **Project_3**, dan begitu pun seterusnya sampai benar-benar FIX.

**Kenapa?**

Karena agar kita bisa mengetahui perubahan yang terjadi antar revisi pada Project kita, jika sewaktu-waktu kita perlu menggunakan revisi yang sebelumnya, kita bisa beralih dan menggunakanannya dengan mudah.

#### Version Control System (VCS)

**Version Control System** disingkat **VCS** adalah sebuah system yang merekam perubahan pada file dari waktu ke waktu, sehingga kita bisa melihat versi sebelumnya jika sewaktu-waktu diperlukan.

Dengan version control programmer / developer bisa merekam semua perubahan yag terjadi, sehingga jika sewaktu-waktu terjadi kesalahan, kita bisa dengan mudah dan cepat kembali ke versi sebelumnya sehingga kita tidak perlu membackup setiap perubahan secara manual.

#### Tipe

Ada 3 tipe VCS yaitu :

1. **Local Version Control System**
   
    Adalah  version control yang berjalan hanya pada local komputer atau hanya di laptop kita, artinya setiap revisi atau perubahan versi yang terjadi pada file hanya disimpan di local komputer kita.
    **Note :**
    - Sulit untuk berkolaborasi dengan Team atau pengguna lain. 
    - Jika komputer atau laptop kita rusak, maka seluruh data akan hilang.

2. **Centralized Vesion Control System**
   
   Yaitu version control yang menyimpan seluruh data di server, jika ingin melakukan perubahan pengguna harus mengirim data ke server terlebih dahulu, pengguna bisa mengakses data ke server untuk melihat file, yang di simpan di laptop /  komputer adalah versi yang terakhir atau terbaru.
   Dan jika ingin pindah revisi tinggal konek ke server dan geser ke versi yang diinginkan.
   **Contoh Software :**
   Subversion.
   **Note :**
   - Jika pengguna offline, mereka tidak bisa  melihat riwayat file karena semua riwayat hanya ada di server.
   -  Dan jika server down, maka seluruh pengguna tidak bisa melakukan perubahan dan melihat revisi file.  
  
3. **Distributed Version Control System**

    Adalah version control yang tidak hanya mengambil file revisi versi terakhir, namun seluruh riwayat revisi akan di copy seluruhnya. ini adalah alternatif lain dari Centralized Version Control. jika terdapat masalah dengan server, pengguna masih tetap bekerja dan memanipulasi file sampai dengan melihat perubahan.
    Bahkan dalam Distributed Version Control, server bisa lebih dari satu, dikarenakan setiap server isinya sama.
    **Contoh Software :**     
    - Git.
    - Mercurial.
    - BitKeeper.
    - Dan lain-lain.
    
## 2. Pengenalan Git

---

#### Sejarah Git

**Git** muncul dengan latar belakang **OpenSource** project **Linux Kernel**, pada tahun 1991 - 2002 **Linux Kernel** di kembangkan hanya dengan memanfaatkan patch dan archive files, selanjutnya tahun 2002, **Linux Kernel** mulai menggunakan **Distributed Version Control System** bernama **BitKeeper**.

Dan setelah itu di tahun 2005, hubungan antara perusahaan **BitKeeper** dengan Komunitas **Linux Kernel** berjalan kurang baik, sehingga pembuat Linux yaitu **Linus Torvals** mulai membuat **Distributed Version Control System** sendiri.
Pada tahun 2005 Git mulai di perkenalkan, semakin berjalannya waktu **Git** semakin populer dan sekarang menjadi **Distributed Version Control System** yang paling populer di dunia.

**Git** sangan cepat, ringan dan baik dalam me-manage baik itu project kecil sampai dengan project besar.

#### Apa itu Git?
 
 **Git** adalah software salah satu **Distributed Version Control System** yang tidak membutuhkan server untuk melakukan perubahan atau melihat riwayat revisi, dikarenakan  di dalam git, semua riwayat project akan selalu di duplikasi atau di copy baik itu di server maupun di local komputer kita, itu berarti Git juga bisa digunakan sebagai Local Version Control.

Setiap perubahan yang terjadi di **Git** pasti selalu di buat tanda (**signature**), karena Git menggunakan **algoritma hashing SHA-1**, dan menjadikan perubahan sekecil apapun akan terdeteksi olah **Git**. serta semua yang terjadi secara otomatis akan tercatat, dan menjadikan perubahan apapun di **Git** pasti bisa dikembalikan ke versi sebelumnya.



## 3. Repository
## 4. The Three Tree
## 5. Working Directory
## 6. Staging Index
## 7. Commit
## 8. Reset Commit
## 9. Dan lain-lain