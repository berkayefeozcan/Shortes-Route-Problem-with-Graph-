# Proje Ozeti
 Bu projede gezgin kargo probleminin çözümlenmesi amaçlanmaktadır. Amaç kullanıcının tasarladığımız kullanıcı arayüzü ile girdiği şehirleri dolaşması ve başladığı noktaya mümkün olan en kısa yollardan geri dönmesidir. 

# Programin calistirilmasi
 Program jar dosyası üzerinden çalıştırılmaktadır.Jar dosyasının çalışabilmesi için çalıştırlan bilgisayarda javaFx kütüphanesinin yüklü olması gerekmektedir.Kodun derlenip çalıştırılabilmesi içinse en az jdk1.8.0_251 yüklü olması gerekmektedir.Ubuntuda jar dosyası çalıştırlırken ortaya çıkabilecek hataya karşı şu adımlar izlenir :
-apt purge openjfx
-apt install openjfx=8u161-b12-1ubuntu2 libopenjfx-jni=8u161-b12-1ubuntu2 libopenjfx-java=8u161-b12-1ubuntu2
-apt-mark hold openjfx libopenjfx-jni libopenjfx-java
(tabi java yoksa önce java yüklenir.)
sonra jar dosyasini çaliştirmak için :
java -jar <Jardosyasınınİsmi>

----programin çalışabilmesi için gerekli olan dosyalar:
*harita.png 
*sehirlerArasiMesafeler.txt
*cozunurlukAyar.txt 
*icon.png
Program çalıştırıldıktan sonra textbox a Kocaeli hariç şehirler girilir ve hesapla butonuna basılır.
hesaplama bitince ise radio butonlar ile yollar seçilip harita çizdirilebilir.
 
# Projede kullanilan kutuphaneler
 JavaFx
# Proje ile ilgili notlar :
-Yazmış olduğumuz program kapatılmadan tekrar tekrar hesaplama yapabilmektedir.
-Proje netbeans idesi kullanılarak geliştirilmiştir.
# Projeyi Gelistirenler
 Berkay Efe Özcan --> ogrenci no :180201080
 Cumali Toprak --> ogrenci no :180201090


