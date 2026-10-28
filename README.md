# 🐤 Bouncy Bird (Web PWA + Offline + Proximity & NFC)

Tamamen bağımsız, tek dosyalık gelişmiş bir Bouncy Bird oyunu. İnternetsiz (offline) çalışır, PWA olarak telefona kurulabilir; QR, Proximity (AirDrop / Quick Share) ve Web NFC ile paylaşılabilir.

---

## 🎮 Özellikler

* **5 Farklı Oyun Modu:** Klasik, Zamana Karşı (60s), Zen (Ölümsüz), Ters Yerçekimi, Günlük Mücadele.
* **Boss Sistemi:** Ejderha savaşları, can barları, mermiler ve özel animasyonlar.
* **Karakter ve Kostümler:** 13+ skin (robot, penguen, anka kuşu, hayalet...), boru temaları, arka planlar ve uçuş izleri (trail).
* **Şans Atölyesi:** Çarkıfelek, şans yumurtası, kart açma ve yazı-tura mini oyunları.
* **%100 Çevrimdışı (Offline PWA):** İlk açılıştan sonra internet kesilse bile Service Worker sayesinde tamamen offline oynanır.
* **Proximity & NFC Paylaşım:**
  * **Yakındakine At (Jest):** Telefonları birbirine dokundurarak (iOS 17+ AirDrop/NameDrop veya Android Quick Share) anında oyunu paylaşma.
  * **NFC Desteği (Web NFC):** Oyun linkini veya kayıt kodunu fiziksel NFC etiketlerine/kartlarına yazma ve okuma.
  * **Cihaz Aktarımı:** Kamera ile QR okuma, kayıt senkronizasyonu ve çakışma çözümü.

---

## 🚀 GitHub Pages ile Yayınlama

GitHub reponuzda **Settings → Pages** sekmesine gidin:
* **Source:** `Deploy from a branch` seçin.
* **Branch:** `main` / `/(root)` seçip **Save** butonuna basın.

Yaklaşık 1 dakika sonra oyununuz şu adreste canlıya geçer:
> **`https://HeXtR0.github.io/bouncy-bird/`**

---

## 📱 Telefonda Oynama ve Paylaşma

* **Oyunu Açma:** Linke tıkladığınız an oyun tam ekran tarayıcıda başlar.
* **Telefona Yükleme:** Tarayıcı menüsünden *"Ana Ekrana Ekle"* (veya *"Uygulamayı Yükle"*) diyerek gerçek bir mobil oyun gibi internetsiz oynayabilirsiniz.
* **Yakındakine Gönder (Jest):** Ayarlar → "Oyunu Paylaş" ekranından **"YAKINDAKİNE AT"** butonuna basıp telefonunuzu arkadaşınızın telefonuna dokundurduğunuzda (AirDrop / Quick Share) anında iletilir.

