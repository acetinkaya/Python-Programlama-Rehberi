# Python Programlama Dili Rehberi

Bu repo, Python programlama dili üzerine hazırlanmış bir rehberdir. Temel konulardan ileri düzey uygulamalara kadar adım adım ilerleyen örneklerle, Python programlama dilini öğrenme sürecinizi kolaylaştırmayı amaçlamaktayım.

🎯 Hedef Kitle

Python diline yeni başlayan öğrenciler

Python programlama dilini öğrenmek isteyen herkes

Gömülü sistem uygulamalarında algoritma geliştirmeyi ve programlamaya ilgi duyan tüm geliştiriciler.

# 📘 Ders Video İçerikleri:

Python Programlama Dili Soru Çözüm Videosu :> 

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

2.2 Değişkenler ve Veri Tipleri (int, float, str, char)

yas = 25                  # int (tam sayı)   
sicaklik = 36.5           # float (ondalıklı sayı)   
harf = 'A'                # str (tek karakter de str türündedir)   
isim = "Ali"              # str (metin ifadesi)   
PI = 3.14                 # sabit gibi kullanılan değişken (float)    
GUN_SAYISI = 7            # sabit gibi kullanılan değişken (int)   

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

6.1 Tek Boyutlu Dizi





