# Dockerized Express Server

Basit bir Express sunucusu. Port 3000'de çalışır.

Kullanım:

1. Image oluştur:

```bash
# WSL shell için
docker build -t basictest:latest .
```

2. Container çalıştır:

```bash
docker run -p 3000:3000 basictest:latest
```

3. Tarayıcıda aç:

http://localhost:3000
