# Python Programlama Dili Rehberi

![alternatif metin](https://github.com/acetinkaya/Python-Programlama-Rehberi/blob/main/python_rehberi.png)

Bu repo, Python programlama dili üzerine hazırlanmış bir rehberdir. Temel konulardan ileri düzey uygulamalara kadar adım adım ilerleyen örneklerle, Python programlama dilini öğrenme sürecinizi kolaylaştırmayı amaçlamaktayım.

🎯 Hedef Kitle

Python diline yeni başlayan öğrenciler

Python programlama dilini öğrenmek isteyen herkes

Gömülü sistem uygulamalarında algoritma geliştirmeyi ve programlamaya ilgi duyan tüm geliştiriciler.

# 📘 Ders Video İçerikleri:

Python Programlama Dili Konu Anlatımı - 1 Videosu :> https://youtu.be/i2QxxYTaaxs

Python Programlama Dili Konu Anlatımı - 2 Videosu :> https://youtu.be/hHtVqEu7UZY

Python Programlama Dili Soru Çözüm Videosu :> https://youtu.be/Eyzd5ItzZI0

# 📘 Ders İçerikleri:

## 1. Python Programlama Diline Genel Bakış

-> Python Nedir?

* Yüksek seviyeli, okunabilirliği yüksek, çok amaçlı ve yorumlanabilir bir programlama dilidir. Dinamik yapısı ve geniş kütüphane desteği ile veri analitiği, yapay zekâ, web geliştirme, otomasyon gibi birçok alanda kullanılır.
  
-> Python Nerelerde Kullanılır?

* Bilgisayarda Programlama Python, Algoritma & Veri Yapıları, Yapay zeka ve makine öğrenimi, veri analizi, web uygulamaları (Django, Flask), otomasyon scriptleri, gömülü sistemler (MicroPython), bilimsel hesaplamalar, oyun geliştirme konularında python programlama dili kullanılmaktadır.

-> İlk Python Programı:

    print("Merhaba Hayat")

## 2. Python Programlama Diline Giriş   

2.1 Yorum Satırları   

    # Tek satırlık yorum   

    """   
    Çok satırlı   
    yorum bloğu   
    """   

2.2 Değişkenler ve Veri Tipleri (int, float, str, bool)

    yas = 25                  # int (tam sayı)   
    sicaklik = 36.5           # float (ondalıklı sayı)   
    harf = 'A'                # string || str (tek karakter de str türündedir)   
    isim = "Ali"              # string || str (metin ifadesi)   
    degisken = True           # bool değişlen türü True || False 

## 3. Operatörler

3.1 Aritmetik Operatörler

    toplam = 5 + 3         # 8   
    carpim = 4 * 2         # 8    
  
3.2 Karşılaştırma Operatörleri

    a = 10
    b = 10
    
    if a == b:
        print("Eşittir")
        
3.3 Mantıksal Operatörler

    a = 5
    b = 7
    
    if a > 0 and b > 0:
        print("Pozitif sayılar")

    ---

      not1 = 45
      not2 = 60
          
      if not1 >= 50 or not2 >= 50:
        print("Ders geçildi.")

    ---

    aktif = False
    if not aktif:
        print("Kullanıcı pasif.")

## 4. Kontrol Yapıları

4.1 Koşullu İfadeler

    yas = 17
    
    if yas > 18:
        print("Yetişkin.")
    else:
        print("Çocuk.")

    ---

    yas = 20
    puan = 85
    
    if yas >= 18 and puan >= 80:
        print("Sınava girmeye uygunsunuz.")
    else:
        print("Şartları sağlamıyorsunuz.")

4.2 Döngüler

4.2.1 for Döngüsü

    for i in range(5):
        print(i)

4.2.2 while Döngüsü

    i = 0
    while i < 5:
        print(i)
        i += 1
        
## 5. Fonksiyonlar

5.1 Fonksiyon Tanımı ve Kullanımı

    # Toplama yapan fonksiyon
    
    def topla(a, b):
        return a + b
    
    # Fonksiyon çağrısı
    
    sonuc = topla(5, 3)
    print(sonuc)   

## 6. Listeler

6.1 Tek Boyutlu Liste

    sayilar = [1, 2, 3, 4, 5]
    print(sayilar[2])  # 3

6.2 Çok Boyutlu Liste

    matris = [
        [1, 2, 3],
        [4, 5, 6]
    ]
    
    print(matris[1][2])  # 6

## 7. Python Programlama Dili Kütüphaneleri

7.1. Python’da Genel Amaçlı Kullanılan Kütüphaneler

| Modül Adı  | Ana İşlev Grubu       | Örnek Fonksiyonlar                               | Kısaca Ne Yapar                                             |
| ---------- | --------------------- | ------------------------------------------------ | ----------------------------------------------------------- |
| `time`     | Tarih & Zaman         | `time()`, `localtime()`, `strftime()`, `sleep()` | Unix zaman damgası, yerel zaman, bekleme fonksiyonu sağlar. |
| `sys`      | Sistem İşlemleri      | `argv`, `exit()`, `getsizeof()`                  | Komut satırı argümanları, çıkış işlemleri.                  |
| `os`       | İşletim Sistemi       | `mkdir()`, `remove()`, `system()`, `getcwd()`    | Dosya/dizin işlemleri, komut çalıştırma.                    |
| `math`     | Matematik             | `sqrt()`, `pow()`, `sin()`, `log()`, `ceil()`    | Karekök, üstel, trigonometrik işlemler.                     |
| `random`   | Rastgele Sayılar      | `random()`, `randint()`, `choice()`, `shuffle()` | Rastgele sayı ve seçim üretimi.                             |
| `builtins` | Yerleşik Fonksiyonlar | `len()`, `type()`, `input()`, `print()`          | Python’ın varsayılan yerleşik işlevleri.                    |

7.2. Python’da Özel Amaçlı Kütüphaneler

| Modül Adı | Ana İşlev Grubu          | Örnek Fonksiyonlar                          | Kısaca Ne Yapar                                               |
| --------- | ------------------------ | ------------------------------------------- | ------------------------------------------------------------- |
| `string`  | Karakter Dizileri        | `ascii_letters`, `digits`, `punctuation`    | Hazır karakter kümeleri sağlar.                               |
| `re`      | Düzenli İfadeler (regex) | `match()`, `search()`, `findall()`, `sub()` | Metin arama ve değiştirme işlemleri.                          |
| `assert`  | Hata Ayıklama            | `assert`                                    | Koşul doğru değilse hata fırlatır (C’deki `assert.h` gibi).   |
| `locale`  | Yerelleştirme            | `setlocale()`, `localeconv()`               | Sayı formatı, para birimi biçimi gibi yerel ayarları yönetir. |
| `errno`   | Hata Kodları (dolaylı)   | `errno`, `strerror()` (via `os.strerror`)   | Sistem hatalarının yorumlanması.                              |

## 8. Python’da try-except Yapısı

8.1. Try-Except yapısı

    try:
        # Hata çıkarabilecek kod
    except HataTuru:
        # Hata yakalandığında çalışacak kod
        
8.2. Python Try-Except Hata Türleri 

| Hata Türü           | Açıklama                                                               | Örnek Kod                             |
| ------------------- | ---------------------------------------------------------------------- | ------------------------------------- |
| `ValueError`        | Uygun olmayan veri tipiyle işlem yapılmaya çalışıldığında oluşur.      | `int("merhaba")`                      |
| `TypeError`         | Yanlış türdeki verilerle işlem yapılırsa oluşur.                       | `"Ali" + 5`                           |
| `ZeroDivisionError` | Sayı sıfıra bölünmeye çalışıldığında oluşur.                           | `10 / 0`                              |
| `IndexError`        | Listede olmayan bir indekse erişildiğinde oluşur.                 | `[1, 2, 3][5]`                        |
| `KeyError`          | Sözlükte olmayan bir anahtara erişildiğinde oluşur.                    | `{"ad": "Ali"}["soyad"]`              |
| `NameError`         | Tanımlanmamış bir değişkene erişilmeye çalışıldığında oluşur.          | `print(x)` (x tanımlı değilse)        |
| `AttributeError`    | Nesne üzerinde tanımlı olmayan bir fonksiyon/metoda erişilirse oluşur. | `"Ali".append("x")`                   |
| `FileNotFoundError` | Açılmak istenen dosya bulunamazsa oluşur.                              | `open("yok.txt")`                     |
| `ImportError`       | Var olmayan veya yüklenemeyen bir modül çağırıldığında oluşur.         | `import yok_modul`                    |
| `IndentationError`  | Kod bloğu girintileme kurallarına uymazsa oluşur.                      | `if True:\nprint("merhaba")`          |
| `SyntaxError`       | Yazım hatası varsa oluşur.                                             | `for i in range(5)` (iki nokta eksik) |
| `Exception`         | Tüm hata türlerinin üst sınıfıdır (genel hata yakalamada kullanılır).  | `except Exception as e:`              |

## 9. Python Programlama Dili Örnekleri

9.1 Kullanıcı Girdisinin Doğruluğunu Kontrol Etme

    try:
        sayi = int(input("Bir sayı girin: "))
        print("Girilen sayı:", sayi)
    except ValueError:
        print("Geçersiz karakter girişi yaptınız.")

9.2 Girilen Bir Sayının Tek mi Çift mi Olduğunu Bulma 

    try:
        sayi = int(input("Bir sayı girin: "))
        
        if sayi % 2 == 0:
            print(sayi, "çift sayıdır.")
        else:
            print(sayi, "tek sayıdır.")
    except ValueError:
        print("Lütfen geçerli bir tamsayı girin.")

9.3. Girilen Bir Değerin Sayı Olduğu Kontrol Edildikten Sonra Tek mi Çift mi Olduğunu Bulma

    try:
        sayi = int(input("Bir sayı girin: "))
        
        if sayi % 2 == 0:
            print(sayi, "çift sayıdır.")
        else:
            print(sayi, "tek sayıdır.")
    
    except ValueError:
        print("Geçersiz giriş! Lütfen bir tamsayı giriniz.")

9.4. Kullanıcıdan Alınan Sayıları Listeye Aktarma ve Yazdırma

    sayilar = []
    
    print("Lütfen 6 adet tamsayı giriniz:")
    
    for i in range(6):
      try:
         sayi = int(input(str(i + 1) + ". sayı: "))
         sayilar.append(sayi)
      except ValueError:
         print("Geçersiz giriş! Lütfen tamsayı giriniz.")
    
    # Girilen sayıları yazdır
    
    print("Girilen sayılar:", sayilar)


9.5. Kullanıcının Belirlediği Sayı Adedi ile Girilen Sayı Adedinin Karşılaştırılması

    sayilar = []
    
    istenen_adet = 6
    
    print("6 Adet Sayı Giriniz")
    
    for i in range(istenen_adet):
      try:
        sayi = int(input(str(i + 1) + ". sayi"))
        sayilar.append(sayi)
      except ValueError:
        print("Geçersiz değer girdiniz")
    
    print("Kullanıcıdan Gelen Degerler: ",sayilar)
    sayi_adeti = len(sayilar)
    print("Kullanıcıdan Gelen Sayı Adeti ",sayi_adeti)
    
    if(istenen_adet>sayi_adeti):
      print("Eksik Sayı Girdiniz")
    elif(istenen_adet<sayi_adeti):
      print("Fazla Sayı Girdiniz")
    elif(istenen_adet==sayi_adeti):
      print("Girilen Sayı İstenen Sayı Adeti Kadardır")
    else:
      print("Hata")


9.6. Kullanıcıdan Alınan Sayıların Ortalamasını Hesaplama

    sayilar = []
    print("Lütfen 6 adet tamsayı giriniz:")
        
    for i in range(6):
      try:
          sayi = int(input(str(i + 1) + ". sayı: "))
          sayilar.append(sayi)
      except ValueError:
          print("Geçersiz giriş! Lütfen tamsayı giriniz.")
        
    ortalama = sum(sayilar) / len(sayilar)
    print("Girilen sayıların ortalaması:", ortalama)

9.7. Kullanıcıdan Alınan Sayıların Diziye Atılması ve Tek–Çift Sayıların Adetlerinin Belirlenmesi

    sayilar = []
    tek_sayac = 0
    cift_sayac = 0
    
    print("Lütfen 6 adet tamsayı giriniz:")
    
    for i in range(6):
        try:
            sayi = int(input(str(i + 1) + ". sayı: "))
            sayilar.append(sayi)
    
            if sayi % 2 == 0:
                cift_sayac += 1
            else:
                tek_sayac += 1
        except ValueError:
            print("Geçersiz giriş! Lütfen tamsayı giriniz.")
    
    print("Girilen sayılar arasında:")
    print("Tek sayı adedi: ", tek_sayac)
    print("Çift sayı adedi: ", cift_sayac)

9.8. Kullanıcıdan Alınan Sayıların Diziye Atılması ve Küçükten Büyüğe Göre Sıralaması

    sayilar = []
    print("Lütfen 6 adet tamsayı giriniz:")
        
    for i in range(6):
      try:
          sayi = int(input(str(i + 1) + ". sayı: "))
          sayilar.append(sayi)
      except ValueError:
          print("Geçersiz giriş! Lütfen tamsayı giriniz.")
          
    # Bubble Sort algoritmasıyla küçükten büyüğe sıralama
    for i in range(len(sayilar)):
        for j in range(len(sayilar) - 1):
            if sayilar[j] > sayilar[j + 1]:
                # Elemanları yer değiştiriyoruz
                sayilar[j], sayilar[j + 1] = sayilar[j + 1], sayilar[j]
    


----

## 📖 Kaynak Kitaplar

1. Eftâl Şehirli, Muhammed Kâmil Turan, Python ile Soru Çözüm Kitabı, Nobel Akademik Yayıncılık, Ankara, 2023.
  
2. Prof. Dr. Özlem Türkşen, Optimizasyon Yöntemleri ve Matlab, Python, R Uygulamaları, Nobel Akademik Yayıncılık, 2023.

⚡ **Bilgi Paylaştıkça Gelişir!** 🚀 


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Bu Github paylaşımının IEEE ve APA formatlarınada atıf verilme şekli:

IEEE--> A. Cetinkaya, "Python Programlama Dili Rehberi" GitHub, [Online]. Erişim Linki: https://github.com/acetinkaya/Python-Programlama-Rehberi . Son Erişim Tarihi: Gün Ay Yıl.   

APA--> Cetinkaya, A. (2025). Python Programlama Dili Rehberi [GitHub Deposu]. GitHub. Erişim Linki: https://github.com/acetinkaya/Python-Programlama-Rehberi . Son Erişim Tarihi: Gün Ay Yıl.

---

---

Yukarıdaki bilgi, resim ve kod çalışmaları açık kaynak paylaşım olarak GitHub "acetinkaya" alanında paylaşımı yapılmıştır.

Proje Durumu: İlgili paylaşımlar ve Python programlama dilinde yazılmış yazılım kodlarına sürüm güncellemeleri yaptıkça bu paylaşımları güncelleyeceğiz. GitHub bölümünden beğeni bildirimi olarak bir yıldız vererek çalışmalarımı destekleyebilirsiniz. Bilgi paylaşıldıkça büyür ve gelişir.

Katkıda Bulunma: Fork - Çekme istekleri memnuniyetle karşılanır. Büyük değişiklikler için lütfen önce neyi değiştirmek istediğinizi görüşmek üzere ilgili Python kodunu belirttiğiniz bir soru - yanıt bölümü açın. 
Bilgi paylaşıldıkça çoğalır ve gelişir. İyi çalışmalar dilerim.

Yazar ve Güncelleme Yapan: [Öğr. Gör. Ali Çetinkaya (MSc.)](https://github.com/acetinkaya) - 2025

---

The above information, images, and code examples are shared as open-source content on GitHub under the "acetinkaya" account.

Project Status: The relevant posts and software codes written in the Python programming language will be updated as new versions are released. You can support my work by giving a star to the repository on GitHub. Knowledge grows and develops as it is shared.
Contributing: Forks and pull requests are warmly welcomed. For major changes, please first open a question-answer thread indicating which Python code you want to modify to discuss your proposal. Knowledge multiplies and improves when shared. Best wishes for your work!

Author and Maintainer: [Lect. Ali Cetinkaya (MSc.)](https://github.com/acetinkaya) - 2025

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
