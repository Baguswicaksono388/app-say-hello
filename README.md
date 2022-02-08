# Menambah Dependency
- Bisa menggunakan go get github.com/Baguswicaksono388/go-say-hello untuk menambahkan module

# Upgrade Dependency
- Unk upgrade dependency ke versi terbaru, kita bisa mengubah isi go.mod, lalu mengubah tagnya menjadi tag terbaru
- Unk mendownload versi terbaru, gunakan perintah : go get
- Jika salah masukan versi di go.mod nya, otomatis akan gagal

# Upgrade major upgrade
- Merubah nama module nya, jika ada perubahan nama module. Sebelumnya adlh require github.com/Baguswicaksono388/go-say-hello di hapus.
- jalankan perintah go get github.com/Baguswicaksono388/go-say-hello/v2

