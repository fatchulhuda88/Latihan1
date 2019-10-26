>>Tutorial memakai git<<

A.Installasi Git
	1.Pertama download aplikasi git di (git-scm.com).
	2.Klik download for windows. 
	3.Unduh git sesuai versi komputer seperti 32bit atau 64bit. 
	4.Buka File installasi Git di folder Download. 
	5.dan kemudian Install seperti biasa. 
	6.Cek git sudah terinstall atau belum dengan cara, buka CMD atau PowerShell. 
	  kemudian ketikan perintah "git --version" tanpa kutip.(screanshot 1) 


B.Membuat Repository Local
	1.Buat atau Buka Folder di Windows Explorer. 
	2.Klik kanan pada Folder tersebut, dan pilih menu Git Bash, sehingga muncul git bash command. 
	3.Buat direktori project praktikum pertama dengan nama Latihan1. 
		a.Ketikan "mkdir Latihan1" tanpa kutip, agar terbentuk satu direktori baru di bawahnya.(screanshot 2) 
		b.Ketikan "cd Latihan1" tanpa kutip, untuk masuk ke direktori Latihan1. (screanshot 3) dan (screanshot 4)

C.Menambahkan Global Config 
	1.Buka CMD
	2.Ketikan " git config --global user.name nama_user " tanpa kutip.(screanshot 5) 
	3.Ketikan " git config --global user.email nama_email " tanpa kutip. (screanshot 6)

	
D.Membuat Repository Local
	1.Ketikan perintah "git init" di Git Bash, untuk membuat Repository Local. 
	2.Akan terbentuk file hidden bernama .git, yang menandakan repository berhasil di inisialisasi. 
	3.Pada direktori tersebut, semua perubahan pada working directory akan disimpan
	
E.Menambahkan File Baru Pada Repository
	1.Anda bisa membuat file nya menggunakan text editor lalu menyimpan filenya pada repository,
	  atau lanjut menggunakan Git Bash, tutorial ini akan menggunakan Git Bash
	2.Buat file README.md, ketikan (echo "#Latihan 1#" >> README.md) tanpa kurung  
	  File README.md berhasil dibuat dan bisa di edit.(screanshot 7) 
	3.Masukan perintah "git add README.md" tanpa tanda kutip.(screanshot 8)
F.Commit(Menyimpan Perubahan Ke Database)
	1.Gunakan perintah (git commit -m "File pertama saya") tanpa kurung, 
	  untuk menyimpan perubahan kedalam database repository local.(screanshot 9) 

G.Membuat Repository Server
	1.Buka browser lalu masuk ke web http://github.com(screanshot 10)
	2.Jika belum punya akun daftar dulu, jika sudah punya langsung Sign in.(screanshot 11) 
	3.Pada laman beranda github anda, klik start a project atau dari menu (icon +) klik New Repository. 
	4.Isi nama repositorynya: Latihan1. (sreanshhot 12)
	5.Lalu klik tombol Create Repository. (sreanshot 13)
	
H.Menambahkan Remote Repository
	1.Buka Repository Server Latihan1. 
	2.Copy alamat repositorynya.(screanshot 14) 
	3.Buka Git Bash nya lagi, kemudian jalankan perintah "git remote add origin [URL]" tanpa kutip.(sreanshot 15)

I.Push(Mengirim Perubahan Ke Server)
	1.Jalankan perintah git push "git push -u origin master" tanpa kutip.(sreanshot 16) 
	2.Anda akan di minta memasukan username & password pada akun github.com.
	3.Jika sukses, kita lihat hasil nya pada repository server.(screanshot 17)
	4.Buka laman github.com arahkan pada repository Latihan1. 
	5.Maka perubahan akan terlihat. 

J.Clone Repository
	1.Gunakan perintah git clone "git clone [URL]" tanpa kutip.(screanshot 18) 

Nama  : MUHAMMAD FATCHUL HUDA
NIM   : 311910101
kelas : TI.19.D.2