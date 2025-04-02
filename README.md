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
- `BSP (Binary Space Partitioning)` algoritması

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
