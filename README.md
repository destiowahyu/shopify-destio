# Cara Setup
UNTUK MENJALANKAN LAKUKAN PERINTAH GIT CLONE

### 1. Masuk ke direktori aplikasi
```bash
cd shopify-destio
```

### 2. Jalankan :
```bash
npm install
```
untuk install dependensi

### 3. Sesuaikan file docker-compose

### 4. sesuaikan isi file 
```/src/app.module.ts```
   
  samakan dengan file docker-compose

### 5. Jalankan Aplikasi Docker
   Buka Aplikasi Docker

### 6. jalankan docker-compose
```bash
docker-compose up -d --build
```

### 7. Cek Container yang berjalan
```bash
docker ps -a
```
