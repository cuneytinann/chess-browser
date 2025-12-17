# Browser Chess Game (Vanilla JS)

Bu proje, **harici kütüphane kullanmadan** (pure HTML, CSS ve JavaScript) geliştirilmiş,
tarayıcı üzerinde çalışan bir satranç oyunudur. Oyuncu, rastgele hamle yapan bir bilgisayara
karşı oynar.

---

## 📸 Uygulama Görüntüleri

### Oyun Başlangıcı – Taş ve Süre Seçimi

![Chess Browser Screenshot 1](chess-browser1.png)

### Oyun İçi – Hamleler ve Saatler

![Chess Browser Screenshot 2](chess-browser2.png)

### Oyun Ortası – Terfi Penceresi

![Chess Browser Screenshot 3](chess-browser3.png)

### Oyun Sonu – Mat / Berabere Ekranı

![Chess Browser Screenshot 3](chess-browser4.png)

---

## Özellikler

* ♟️ Tam satranç kuralları

  * Rok
  * Geçerken alma (en passant)
  * Terfi (vezir, kale, fil, at)
  * Mat, pat, 50 hamle kuralı
  * Üç kez tekrar
  * Yetersiz materyal
* ⏱️ Esnek süre sistemi

  * Klasik süreli oyun (dakika bazlı)
  * Hamle başına ek süre (increment)
  * **Sınırsız süre** seçeneği
  * **Çok esnek özel süre ayarları** (0 süre / 0 increment kombinasyonları desteklenir)
  * Süre bitiminde FIDE uyumlu sonuç değerlendirmesi
* 🧠 Bilgisayar rakip

  * Yasal hamleler arasından **rastgele** seçim yapar
* 🖱️ Gelişmiş kullanıcı etkileşimi

  * Tıklama ile oynama
  * Sürükle–bırak (mobil uyumlu, Pointer Events)
* 🔄 Tahta yönü

  * Siyah oynandığında tahta otomatik ters çevrilir
* 📱 Tam responsive tasarım

  * Mobil, tablet ve masaüstü ekranlara otomatik uyum
* 🧩 Tek HTML dosyası

  * Kurulum gerektirmez

---

## Kurulum

Herhangi bir kurulum gerekmez.

1. Depoyu klonlayın veya ZIP olarak indirin
2. `chess-browser.html` dosyasını bir tarayıcıda açın

```bash
git clone <repo-url>
cd <repo-name>
open chess-browser.html
```
