# Tugas-2-PBO-Baim-mudrik-aziz_G1A022071

Kode di atas merupakan implementasi dari sistem manajemen data mahasiswa di sebuah universitas. Berikut adalah penjelasan dari setiap bagian kode:

Kelas Mahasiswa:

Kelas ini memiliki atribut nama, nim, dan jurusan.
Metode __init__ digunakan untuk menginisialisasi objek Mahasiswa dengan nilai-nilai atribut.
Metode tampilkan_info digunakan untuk menampilkan informasi lengkap tentang seorang mahasiswa, yaitu nama, NIM, dan nama jurusan.
Kelas Jurusan:

Kelas ini merepresentasikan sebuah jurusan di universitas.
Kelas ini memiliki atribut NamaJurusan yang merupakan nama dari jurusan tersebut, serta atribut DaftarMahasiswa yang merupakan daftar objek Mahasiswa yang terdaftar di jurusan tersebut.
Metode __init__ digunakan untuk menginisialisasi objek Jurusan dengan nama jurusan.
Metode tambah_mahasiswa digunakan untuk menambahkan objek Mahasiswa ke dalam daftar mahasiswa di jurusan tersebut.
Metode tampilkan_daftar_mahasiswa digunakan untuk menampilkan daftar mahasiswa yang terdaftar di jurusan tersebut.
Kelas Universitas:

Kelas ini merepresentasikan sebuah universitas.
Kelas ini memiliki atribut NamaUniversitas yang merupakan nama dari universitas tersebut, serta atribut DaftarJurusan yang merupakan daftar objek Jurusan yang ada di universitas tersebut.
Metode __init__ digunakan untuk menginisialisasi objek Universitas dengan nama universitas.
Metode tambah_jurusan digunakan untuk menambahkan objek Jurusan ke dalam daftar jurusan di universitas tersebut.
Metode tampilkan_daftar_jurusan digunakan untuk menampilkan daftar jurusan yang ada di universitas tersebut.
Langkah 2:

Membuat objek universitas_xyz dengan nama "XYZ University" menggunakan kelas Universitas.
Langkah 3:

Membuat objek jurusan_ti dengan nama "Teknik Informatika" menggunakan kelas Jurusan.
Menambahkan objek jurusan_ti ke dalam daftar jurusan di objek universitas_xyz menggunakan metode tambah_jurusan.
Langkah 5:

Menampilkan daftar jurusan yang ada di objek universitas_xyz menggunakan metode tampilkan_daftar_jurusan.
Langkah 6:

Menampilkan daftar mahasiswa yang terdaftar di objek jurusan_ti menggunakan metode tampilkan_daftar_mahasiswa.
Langkah 7:

Meminta pengguna untuk memasukkan jumlah mahasiswa yang akan ditambahkan.
Melakukan perulangan sebanyak jumlah mahasiswa yang akan ditambahkan.
Pada setiap iterasi, meminta pengguna untuk memasukkan data mahasiswa seperti nama, NIM, dan nama jurusan.
Memeriksa apakah jurusan sudah ada dalam dictionary daftar_mahasiswa_per_jurusan.
Jika jurusan sudah ada, maka menggunakan objek jurusan yang sudah ada dalam dictionary.
Jika jurusan belum ada, maka membuat objek Jurusan baru, menambahkannya ke dictionary `daftar_mahasiswa_per
