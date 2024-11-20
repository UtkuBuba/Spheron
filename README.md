# Spheron


# Kurulum

> [Buradan](https://fizz.spheron.network/) cüzdanınızı bağlıyorsunuz.

> Sonra ilerlemeniz gereken bir kaç step var onları tamamlayıp node kurulum sayfasına geçiyorsunuz.

> Sonra lokasyonunuza yakın olan (sunucu lokasyonu) bir provider seçiniz ve görseldeki setup kısmına geliniz.

<img width="790" alt="Ekran Resmi 2024-10-04 22 29 00" src="https://github.com/user-attachments/assets/c1bde16d-56c4-4da1-920a-113d6aba9a44">

> Setup dosyasını indiirp sunucunuzun içine atınız (WinSCP gibi bir program ile veya termius)



```console
# dosya izinlerini verelim
chmod +x /root/fizzup-v1.1.0.sh

screen -S fizz

# iki komuttan birisi ile başlatabilirsiiz.
bash /root/fizzup-v1.1.0.sh
sh /root/fizzup-v1.1.0.sh
```


```console
#log kontrol
docker-compose -f ~/.spheron/fizz/docker-compose.yml logs -f
```







