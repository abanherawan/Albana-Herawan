# Albana-Herawan
# Pertama, pastikan Anda berada di direktori repository Anda
cd repository-anda

# Buat dan pindah ke branch baru bernama "fitur-login"
git checkout -b fitur-login

# Lakukan beberapa perubahan, lalu commit
git add .
git commit -m "Menambahkan fitur login"

# Kembali ke branch utama
git checkout main

# Buat branch kedua untuk fitur lain
git checkout -b fitur-pendaftaran

# Lakukan perubahan, commit
git add .
git commit -m "Menambahkan fitur pendaftaran"

# Kembali ke branch utama
git checkout main

# Buat branch ketiga untuk perbaikan bug
git checkout -b perbaikan-navbar

# Lakukan perubahan, commit
git add .
git commit -m "Memperbaiki masalah pada navbar"
