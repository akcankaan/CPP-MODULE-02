# 🧮 C++ Module 02

Bu depo, 42 okulu C++ müfredatının bir parçası olan **Module 02** kapsamındaki egzersizleri içermektedir. Bu modülde **ad-hoc polymorphism**, **operator overloading** ve **Orthodox Canonical Form** gibi konulara odaklanılmaktadır.

---

## 🎯 Amaç

Bu modülde şunları öğreneceksiniz:

- Sabit noktalı (fixed-point) sayılar ile çalışmak
- Operatör aşırı yükleme (operator overloading)
- Karşılaştırma ve aritmetik işlemleri
- Pre/post arttırma ve azaltma işlemleri
- `Orthodox Canonical Form` (kopyalama ve atama gibi)

---

## 📁 Egzersizler

| Egzersiz | Açıklama |
|----------|----------|
| **ex00** | `Fixed` sınıfı, Orthodox Canonical Form'a uygun şekilde oluşturulur. Bellek yönetimi ve `getRawBits` fonksiyonu tanımlanır. |
| **ex01** | Sayıları `int` ve `float` olarak alabilen yapıcılar, `toFloat()` ve `toInt()` dönüşüm fonksiyonları, `<<` operatörünün aşırı yüklenmesi eklenir. |
| **ex02** | Karşılaştırma (`==`, `!=`, `<`, `>`, `<=`, `>=`) ve aritmetik (`+`, `-`, `*`, `/`) operatörleri aşırı yüklenir. Artırma/azaltma işlemleri ve `min/max` fonksiyonları eklenir. |

---

## ⚙️ Derleme

Her egzersiz klasöründe `Makefile` yer almaktadır. Kodlar aşağıdaki şekilde derlenmelidir:

```bash
-Wall -Wextra -Werror -std=c++98
```

## 🚫 Kurallar ve Yasaklar
- malloc, free, printf gibi C fonksiyonları yasaktır.
- using namespace std ve friend kullanımı yasaktır.
- STL veri yapıları ve algoritmaları yalnızca Module 08'den itibaren serbesttir.
- Tüm sınıflar Orthodox Canonical Form'a göre yazılmalıdır:
- - Default constructor
  - Copy constructor
  - Copy assignment operator
  - Destructor

## ✅ Teslimat ve Değerlendirme
- Tüm çalışmalar Git üzerinden teslim edilir.
- Dosya isimleri, dizin yapısı ve sınıf isimleri belirtilen kurallara uymalıdır.
- Kod okunabilir, anlaşılır ve temiz yazılmalıdır.

## 🧠 Tavsiyeler
- Bellek sızıntılarını (memory leaks) kontrol etmeyi unutmayın.
- Header dosyalarında include guard kullanmayı ihmal etmeyin.
- main.cpp içinde örnek test senaryoları yazarak her fonksiyonu test edin.
- Modül başlamadan önce tüm dökümanı dikkatlice okuyun.

## 🧑‍💻 Yazar
Mehmet Kaan Akcan 42 Kocaeli / [https://github.com/akcankaan]
