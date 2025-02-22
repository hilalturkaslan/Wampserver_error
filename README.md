## Wampserver ikonunun turuncudan yeşile dönmemesi probleminin çözümü ##
Wamp ikonuna sol tik ile tıklayıp apache seçilerek  httpd.conf seçimi yapılır ve  ctrl+F ile 80 portu bulunur ve bulunması ile portun 80 değilde
8080 olarak değiştirilir  bunu bütün LİSTEN yazılı 3 alanda daha uygulamak gereklidir. Bu işlem kaydedildikten sonra wamp ikonunda yine 
sol tik apache httpd-vhosts.conf seçilip virtual host 80 yerine 8080 yapılıp kaydedilme işlemi yapıldıktan sonra wamp ikonu
sol tik restart all service ile ikon yeşile döner. phpMyadmin e tıklandığında localhost kısmında 80 yerine  8080 olarak düzeltildiğinde phpmyadmine ulaşım sağlanır. 
