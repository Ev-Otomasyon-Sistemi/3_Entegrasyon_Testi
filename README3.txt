Uygulamanın görsel erişimleri "Entegrasyon_Testi/Uygulama" klasörünün içerisinde mevcuttur. 
Bu klasörden mobil uygulamamızda kullandığımız görsel ve iconlara erişim sağlayabilirsiniz.

Giriş-çıkış kodlarına "Entegrasyon_Testi/Cihaz_Kontrolleri/Cihaz" dan ulaşabilirsiniz.
Çıktıların entegresyonu burada gerçekleştirilmiştir.
Çıktı doğru görüntülenirse doğru entegre edilmiş olur.

Henüz veritabanı ve ardunio verilirimiz tam olarak girilmediğinden, testlerimizde eksiklerimiz 
mevcuttur. 

Testimizin ilk aşaması bağlantı kesme BluetoothClient.Disconnect(bağlantı kesme) işlemi
gerçekleştirilir ve ListPicker (kullanıcının aralarından seçim yapabileceği metinlerin bir
listesini görüntüleyen bir düğme) ile listelenir. Geri bağlanmak için BluetoothClient.
AddressesAndNames(bağlantı) yapılır ve şifre girilmesi beklenir. Burada if-then-else komutu
kullanılır şifre doğruluğuna göre yönlendirme yapar.Labeller yardımı ile mesaj verirler ama 
butona basıldığında aktif hale gelirler. Onun dışında görünmezler. Ayrıca yardımcı info vardır
bu sayede bağlantının nasıl olacağı hakkında bilgi verir. Kullanıcı ev sıcaklığını görmek 
istediğinde gerekli butona tıkladığında bağlantı olup olmadığını içi içe if-then-else ve 
if-then komutları ile yapar eğer bağlantı var ise evin sıcaklık değerini gerekli TextBoxda 
gösteriri , fakat yok ise ‘‘bağlantı sorunu’’ hatta mesajını verir. Bu aşamaya kadar testlermiz 
bu şekilde yapılmıştır. İlerleyen aşamalarda test aşamaları detaylandırılacaktır.
