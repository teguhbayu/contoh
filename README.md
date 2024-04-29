# App Perpus UKL

## Penggunaan

### Install package-package ini:
```bash
sudo yum install -y yum-utils
sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
sudo yum install -y git nodejs docker
sudo systemctl start docker
```

### Clone repository ini kemudian jalankan:
```bash
git clone https://github.com/teguhbayu/contoh.git

cd contoh/ # PASTIKAN KALIAN MASUK KE DIRECTORY INI!!!!!!
```

### Buat image container docker dan jalankan containernya:
```bash
sudo docker build -t ukl/contoh:1.0.0 .
sudo docker run -d -p 80:3000 ukl/contoh:1.0.0
```
