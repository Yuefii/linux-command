# Cara menggunakan Docker tanpa perintah SUDO

## Ikuti langkah-langkah berikut ini :

pertama kalian tambahkan username kalian ke docker group seperti ini:

```bash
sudo usermod -aG docker ${USER}
```
lalu untuk menambahkan group baru kalian bisa ketik command ini:

```bash
su - ${USER}
```
**(optional)** jika kalian ingin menambahkan username baru ke group bisa ketik ini:

```bash
sudo usermod -aG docker <username>
```

okeey, kalian telah berhasil restart docker kalian dengan cara ini :

```bash
sudo systemctl restart docker
```

bisa juga dengan cara merestart komputer kalian, atau yang lebih simpel kalian ketik: 

```bash
sudo reboot
```

Terimakasih telah melihat repository ini, berikan star ⭐⭐⭐ pada repo ini jika kalian merasa terbantu.