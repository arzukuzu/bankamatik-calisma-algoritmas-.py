# Bankamatik (ATM) Konsol Simülasyonu

Python veri yapıları (Listeler ve Sözlükler) kullanılarak geliştirilmiş, kullanıcı kimlik doğrulaması içeren temel bir bankamatik ve hesap yönetimi konsol uygulaması.

---

## Özellikler

- **Kullanıcı Kimlik Doğrulama (`login`):** E-posta ve parola kontrolü ile güvenli hesap erişimi simülasyonu.
- **Bakiye Sorgulama:** Hesabın anlık bakiye bilgisini görüntüleme.
- **Para Yatırma:** Girilen tutarın ana bakiyeye dinamik olarak eklenmesi.
- **Para Çekme:** Ana bakiye kontrolü yapılarak bakiye düşümü ve yetersiz bakiye uyarısı.
- **Çoklu Kullanıcı Desteği:** Sözlük (`dict`) listesi üzerinden birden fazla müşteri verisinin yönetimi.

---

##  Desteklenen Menü İşlemleri

| Menü No | İşlem | Açıklama |
| :---: | :--- | :--- |
| **1** | Bakiye Sorgulama | Mevcut ana bakiyeyi ekrana yazdırır. |
| **2** | Para Çekme | İstenen tutarı çeker, yetersiz bakiye durumunu kontrol eder. |
| **3** | Para Yatırma | Hesaba belirtilen tutarda para ekler. |

---

##  Çalıştırma

Projeyi yerel ortamda çalıştırmak için:

```bash
python bankamatik.py
