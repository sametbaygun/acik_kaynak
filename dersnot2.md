: 1. *Paket yöneticisi (apt) hakkında bilgi görüntülemek için kullanılan komut nedir?*  
   Komut: apt --help

2. *"grep" komutuna ilişkin detaylı bilgileri görüntülemek için kullanılan komut nedir?*  
   Komut: man grep

3. *Linux işletim sisteminin dağıtım bilgisini görüntülemek için kullanılan komut nedir?*  
   Komut: lsb_release -a

4. *İşletim sisteminin kullandığı kernel versiyonunu ve ağ içinde kullanılan host adını görüntülemek için kullanılan komutlar nedir?*  
   Komut: uname -r ve hostname

5. *İşletim sisteminin hangi kimlikle çalıştığını ve en son ne zaman açıldığını bilgisini veren komutlar nedir?*  
   Komut: whoami ve uptime

6. *Disk kullanımını dosya bilgisiyle birlikte…
    : Çıktı: /usr/local

9. *Sistemde sadece "b" ile başlayan gizli dosyaları görüntülemek için kullanılan komut nedir?*  
Komut: ls -a | grep '^.b'

10. *Sistemdeki dosyaları büyüklüğüne ve dosya üzerinde yapılan değişiklik tarihine göre sıralayan komut nedir?*  
 Komut: ls -lS ve ls -lt
     : # Açık Kaynak İşletim Sistemi Projesi

## Hakkında
Bu proje, temel komut satırı becerilerini kullanarak dokümanlar oluşturma, düzenleme, birleştirme ve yetkilendirme işlemlerini nasıl gerçekleştirebileceğinizi göstermeyi amaçlar. 

## Örnek Görevler ve Çözümler

### Görev 1: "okul.txt" Dosyasının Oluşturulması
- *Amaç*: Masaüstünde "okul.txt" adında bir dosya oluşturmak, içerisine ad-soyad ve bölüm bilgilerini eklemek, kelime ve karakter sayısını bulmak.
- *Komutlar*:
  ```bash
  cd Masaüstü
  touch okul.txt
  echo "İsim Soyisim Bölüm" > okul.txt
  cat okul.txt
  wc -c okul.txt
  wc -w okul.txt
  
Görev 2: Dosyaların Birleştirilmesi
Amaç: "ben.txt" ve "program.txt" dosyalarını oluşturmak, içerik eklemek ve bu dosyaları birleştirerek "birleştirme.txt" oluşturmak.
<br>
 
- *Komutlar*:
 
      *cd Masaüstü
      *touch ben.txt
      *echo "İsim Soyisim Memleket" > ben.txt
      *cat ben.txt
      *touch program.txt
      *echo "Python C++ HTML" > program.txt
      *paste ben.txt program.txt > birleştirme.txt
      *cat birleştirme.txt
      *mkdir komut
      *mv birleştirme.txt komut
