# Tugas Pertemuan 2

Fork dan clone repository ini, lalu jalankan perintah 
```
flutter pub get
```
Buatlah tampilan form yang berisi nama, nim, dan tahun lahir pada file `ui/form_data.dart`, lalu buatlah tampilan hasil dari input data tersebut pada file `ui/tampil_data.dart`

JELASKAN PROSES PASSING DATA DARI FORM MENUJU TAMPILAN DENGAN FILE `README.md`

Buat tampilan semenarik mungkin untuk dilihat.


Nama : Muhammad Iqbal Firmansyah

NIM : H1D022079

Shift Baru: D

Proses passing data:
1. Membuat form awal dengan menggunakan widget textfield untuk mengambil data nama, NIM dan tahun lahir
2. Setelah input diterima, maka data akan diteruskan dengan menggunakan Navigator
3. Untuk memindahkan pengguna dari halaman form_data ke halaman tampil_data, digunakan Navigator.push
4. Maka data yang telah dimasukkan akan ditampilkan pada halaman tampil_data

## Screenshot
Contoh :
![Lampiran Form](form.png)
![Lampiran Hasil](hasil.png)
