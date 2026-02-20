# Ürün Gereksinim Dokümanı (PRD)

## 1) Ürün Tanımı

**idmancım.az**, doğa odaklı fitness, yürüyüş, sağlık takibi ve tur rezervasyonunu tek bir mobil deneyimde birleştiren platformdur.

### Ürün Kişiliği
- Motive edici
- Güçlü
- Disiplinli
- Doğayla bağlantılı
- Performans odaklı

## 2) Hedef Kullanıcılar

1. **Doğa yürüyüşü yapan bireyler** (haftalık aktivite odaklı)
2. **Fitness odaklı kullanıcılar** (hedef ve metrik odaklı)
3. **Tur katılımcıları** (planlı etkinlik ve güvenli rezervasyon)
4. **Premium kullanıcılar** (koçluk, beslenme, ileri analiz)

## 3) Problem ve Değer Önerisi

### Problem
- Aktivite takibi dağınık uygulamalara bölünmüş durumda.
- Tur rezervasyonu ile kişisel takip süreçleri ayrı ürünlerde yürütülüyor.
- Motivasyon sürdürülebilir değil.

### Çözüm
- Hareket takibi + oyunlaştırma + tur pazaryeri + sağlık içgörüsünü tek çatı altında birleştirme.

## 4) Fonksiyonel Gereksinimler

## 4.1 Akıllı Hareket Takip Sistemi

**Zorunlu gereksinimler**
- Adım sayısı takibi (cihaz sensörü)
- GPS mesafe takibi (km)
- Kalori tahmini (ağırlık, yaş, boy, hız, arazi tipine göre)
- Aktif süre hesaplama
- Yürüyüş modu aktifken rakım takibi

**Panel metrikleri**
- Adım
- Mesafe (km)
- Kalori
- Aktif zaman

## 4.2 Başarı Yolu İlerleme Sistemi

Kullanıcı kilometre arttırdıkça hayvan rozetlerinin kilidini açar:

- 5 km → Tilki 🦊
- 15 km → Kurt 🐺
- 50 km → Kartal 🦅
- 100 km → Leopar 🐆
- 300 km → Dağ Keçisi 🐐
- 1000 km → Aslan 🦁

Her rozet:
- Profil amblemi
- Başarı geçmişinde kayıt
- Toplulukta görünürlük

## 4.3 “Yollar” (Tur Paketleri)

**Kullanıcı tarafı**
- Yaklaşan turlar listesi
- Konum haritası
- Zorluk seviyesi
- Fiyat
- Kontenjan / canlı sayaç
- Rezervasyon + ödeme
- Ekipman listesi
- Hava durumu önizlemesi
- Tur rehberi bilgileri

**Yönetici tarafı**
- Yeni tur ekleme
- Maksimum katılımcı belirleme
- Fiyat belirleme
- Ekipman gereksinimi tanımlama

## 4.4 “Tren” (Kişisel Antrenman)

- Program seviyeleri: Başlangıç / Orta / İleri
- Hedef tipleri: Kilo kaybı / Kas kazanımı / Dayanıklılık
- Video egzersiz içerikleri
- Haftalık plan
- Hedef tabanlı yapay zekâ plan önerisi (faz-2’de derinleştirilebilir)

**Premium ekleri**
- Kişiselleştirilmiş koçluk
- Eğitmene mesaj
- Beslenme planı

## 4.5 Sağlık Entegrasyonu

**Kullanıcı girdileri**
- Ağırlık
- Boy
- Yaş
- Sağlık sorunları
- Hedefler

**Harici entegrasyonlar (faz-2 hedefi)**
- Apple Health
- Google Fit

## 4.6 Topluluk

- En yüksek mesafe liderlik tablosu
- En yüksek kalori
- En yüksek rakım
- Tur katılım akışı
- Başarı paylaşımı
- Arkadaş daveti

## 4.7 Abonelik

**Ücretsiz**
- Adım takibi
- Temel liderlik tablosu
- Temel tur izleme

**Premium**
- Gelişmiş analitik
- AI destekli kişisel antrenör
- Beslenme planı
- Erken tur erişimi
- Rozet güçlendirmeleri

## 4.8 Yönetici Paneli

- Kullanıcı yönetimi
- Tur oluşturma ve düzenleme
- Analitik
- Gelir takibi
- Sponsor yönetimi
- Promosyon kod sistemi

## 5) Monetizasyon

- Tur rezervasyon komisyonu
- Premium abonelik
- Sponsor banner alanları
- Fitness ekipmanları afiliye linkleri
- Sağlık kliniği partnerlikleri

## 6) Teknik Gereksinimler

- React Native **veya** Flutter
- Firebase backend
- Gerçek zamanlı veritabanı
- Güvenli kimlik doğrulama
- Stripe / yerel ödeme entegrasyonu
- GPS + hareket sensörü erişimi
- Ölçeklenebilir bulut barındırma

## 7) KPI Seti

- Günlük aktif kullanıcı (DAU)
- Aylık aktif kullanıcı (MAU)
- Kullanıcı başına ortalama km
- Tur dönüşüm oranı
- Premium yükseltme oranı
- Churn oranı

## 8) Risk ve Güvenlik

- Acil durum SOS düğmesi
- Çevrimdışı GPS modu
- Yaralanma sorumluluk reddi
- Tur rezervasyonundan önce feragatname onayı

## 9) Kullanıcı Akışı (MVP)

1. Kaydol
2. Sağlık verilerini gir
3. Dashboard’u gör
4. Takibi başlat
5. İlk kilometre hedefini tamamla
6. Rozet aç
7. Topluluğa katıl
8. Tur rezervasyonu yap
9. Premium yükseltme ekranını gör
