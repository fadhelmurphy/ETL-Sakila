# ETL SQL to GDRIVE

Proses ETL sederhana untuk memindahkan dari SQL ke GDrive

## Instalasi

### Langkah 1: Kloning Repositori

```
git clone https://github.com/fadhelmurphy/ETL-Sakila.git
```

### Langkah 2: Instalasi Dependencies

```
cd ETL-Sakila/
pip install -r requirements.txt
```

## Konfigurasi ENV

1. **Kredensial MySQL**:

   - Pastikan Anda memiliki database Sakila dan kredensial untuk akses ke MySQL.
   - Buat file`.env` di direktori proyek dan masukkan kredensial MySQL:

   ```
   MYSQL_USER=your_username
   MYSQL_PASSWORD=your_password
   ```
2. **Kredensial Google Drive**:

   - Untuk mengunggah ke Google Drive, pastikan Anda memiliki kredensial OAuth.
   - Simpan file kredensial Google Drive dalam format JSON di direktori proyek sebagai`credentials.json`.

## Menjalankan Project

### Jika menggunakan jupyter notebook

```
jupyter etl-sakila.ipynb
```

### Jika menggunakan VSCode

dapat langsung membuka file `etl-sakila.ipynb`
