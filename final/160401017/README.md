server.py dosyası herhangi bir host bilgisi istemeden çalışmaktadır. İçerisindeki utcVariable değişkeni ile UTC değerini ayarlaya bilirsiniz. Utc nin hesaplanması için bir metod bulunmakta UTCType diye ve utcVariable değişkenin değerini değiştirebilmek için de SerUtc metodu bulunmaktadır.

client.py dosyası ilk açılırken host bilgisi istemektedir. Şayet host bilgisi yanlış girildiğinde bağlantı gerçekleşmeyecektir. Dosya bağlantıyı doğru gerçekleştiği taktirde direkt olarak sunucuya istek yollamaktadır. Gelen cevapları consolda göstermektedir.