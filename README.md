<h1 align="center"> Newrl </h1>

![image](https://user-images.githubusercontent.com/101149671/194660242-7679c111-df7a-49fd-b9eb-1d83cd5e010f.png)

# Selamlar, Newrl chain mainnet rehberi:

 * Ödül hakkında bilgi almak için [buraya](https://newrl.medium.com/join-newrls-incentivized-testnet-and-earn-newrl-tokens-716e6af7b1b9) tıkla. Not: bizim Buray değil.
 * Proje hakkında sorularınız için [buradayım](discord.gg/ruescommunity)
 * Projenin discord kanal [linki](https://discord.gg/GWVZxuH2)

## Sistem gereksinimleri:

 * Net bilgi yok, kendim test ettim:

```
4 CPU
8 RAM
80 GB SSD
```

## Portları açalım önce
```
sudo ufw status
```
```
sudo ufw allow 22
sudo ufw allow 22/tcp
sudo ufw allow 21
sudo ufw allow 21/tcp
sudo ufw allow 8456
sudo ufw allow 8456/tcp
```
```
sudo ufw enable
```



## Sunucumuzu güncelliyoruz:
```
sudo apt-get update && sudo apt-get upgrade
```

## Git yüklüyoruz
```
git clone https://github.com/git/git
```

## Python3.7+  yüklüyoruz
```
sudo apt update && sudo apt install python3.10-venv
```
Not: Burda hata alırsanız önemsemeyin devam
## Python3 Pip ve venv yüklüyoruz  
```
sudo apt update
sudo apt install python3-venv python3-pip
```

## Daha önce testnet kuruluysa

```
cd newrl
```
```
screen -X -S newrl kill
```

## Kurulum
```
git clone https://github.com/newrlfoundation/newrl.git
cd newrl
scripts/install.sh mainnet
```

## Cüzdan yedek dönme
auth.json dosyanızı newrl mainnet içine atıyoruz. işlemlere devam ediyoruz. nerde bu auth dosyası testnetini kurduğumuz newrl dosyası içindeki testnet dısyası içinde. böle bulmadınızmı browser üzerinden wallet oluşturmustuk ordan download diyelim sona adını auth.json yapalım ve kurulumu sırasında newrl içindeki mainnet dosyası içine kopyalayalım.

## Düğümü başlatıyoruz
```
apt install screen
```

```
screen -S newrl
```

```
scripts/start.sh mainnet
```

## Node içinde oluşturduğumuz adresi Wallete tanımlama:  UNUTMAYIN LOGLAR AKMAYA BASLADIĞINDA BU SCREENDEN CTRL A D İLE ÇIKIP DEVAM EDİYORUZ. TEKRAR GİRMEK İSTERSENİZ : screen -a -r newrl  ( yine çıkarken ctrl ad )

 * Aşağıdaki komuttan sonra sırayla:
 * mainnet yazıyoruz + enter
 * Y yapıp enterlayıp çıkan çıktıyı kaydedin bu sizin json dosyanızdır.

```
cd newrl
python3 scripts/show_wallet.py
```

Çıkan çıktı yedek aldığımız ve döndüğümüz dosyanın içindeki adresle aynıysa doğru yapmışız demektir.

![image](https://user-images.githubusercontent.com/101149671/194666768-2920d230-3f2f-4fbe-89ff-84fc222bfb00.png)


## https://www.newrlscan.io/  sitesinden ipnizi kontrol edin bir kaç saat sona buraya düşmesi lazım nodun

## şimdi mainneti kurduk ipmiz görunuyor. gelelim birbirimize trust puanı vermeye.cüzdanınızı bana tg özelden atınız isteyenler

## Cüzdanlar
```
0x2de4136d410cab684cb17d3c5f7868ee50b55101
```
```
0xbd5df0304fcd62b8cb0883ab45487c34d55957f4
```
```
0xffb9055c8ad06a87c69bc4f11f41f531064bd27b
```
```
0x54b60f681f367498a16800700632d40ea5b82946
```
```
0x4adfa4ffedf180c9e3343ce016e3404310c059cd
```
```
0xb9f5e3f18d65b601a238fb457eadb6697a6a2cb1
```
```
0xbbc746f991bb1e6ab951aa7f61f52ae3cded682c
```
```
0xaaeaa756d5bc80749b0526c3a5194da8d54a0f73
```
```
0x901d54843ab9f6bc9de5f5ce886a3a732030455c
```
```
0x9b2d184ee616ffdb3a8a7e5d82e3bc07de1b8985
```
```
0x279657578d3178a8cdcbd8921015b1ab7ec80cb4
```
```
0x2cc2dcba84b9687bebe7a26bccecf2119eb17528
```
```
0xfd7537afe2e026a3544844b059e9de5b361687e5
```

![1](https://user-images.githubusercontent.com/91562185/199553273-3859ecc1-b040-447e-8acb-d14f9aa867ce.jpg)

![2](https://user-images.githubusercontent.com/91562185/199553329-3ec31a41-e110-42ef-88a6-9629e506020e.jpg)



