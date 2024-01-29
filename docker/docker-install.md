# Cara Install Docker di Linux | UBUNTU

# Ikuti Langkah-langkah berikut ini :

Langkah pertama, kamu update package yang sudah terinstall:
```bash
    sudo apt update
```

selanjutnya kamu install beberapa package untuk syarat menggunakan package yang menggunakan HTTPS:

```bash
    sudo apt install apt-transport-https ca-certificates curl software-properties-common
```

lalu tambahkan GPG, repository resmi docker ke sistem kamu:

```bash
    curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```

tambahkan juga repository docker ke APT kalian:

```bash
    sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"
```

setelah itu barulah kalian install dockernya:

```bash
    sudo apt install docker-ce
```

lalu kemudian periksa docker kalian apakah sudah berjalan atau belum:

```bash
    sudo systemctl status docker
```

selamat kamu telah berhasil menginstall docker di linux || **UBUNTU**

Terimakasih telah melihat repository ini, berikan star ⭐⭐⭐ pada repo ini jika kalian merasa terbantu.