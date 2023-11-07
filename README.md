# Ramadhani-Prasetyo_4522210009_Prak_DW_A_Tgs8

##Picture Hasil Setelah Di Style
![Picture](Pitcuretgs8.png)

## Alur Logika dari Program
- Pengguna mengisi data pada form pendaftaran. Data yang harus diisi nama lengkap, ID 
siswa, email, password, dan tanggal lahir.
- Saat pengguna mengklik tombol "Daftar", event submit akan berfungsi. Event submit 
adalah event yang terjadi saat form Kirim.
- JavaScript akan mencegah form dari submit otomatis dengan menggunakan fungsi 
event.preventDefault(). 
- JavaScript akan melakukan validasi terhadap data yang diisi oleh pengguna. Validasi 
dilakukan untuk memastikan bahwa data yang diisi adalah valid.
- seperti Nama lengkap harus diisi.ID siswa harus diisi.Email harus diisi dan memiliki 
format yang valid.
Password harus memiliki panjang minimal 14 karakter dan mengandung huruf, angka, 
serta simbol.Tanggal lahir harus diisi.
- Jika ada data yang tidak valid, JavaScript akan menampilkan pesan error. Pesan error 
akan ditampilkan menggunakan fungsi alert() pada setiap if dari masing-masing 
validasi.
- Jika semua data valid, JavaScript akan menampilkan pesan berhasil. Pesan berhasil 
akan ditampilkan menggunakan fungsi alert(‘Pendaftaran berhasil!’) .

