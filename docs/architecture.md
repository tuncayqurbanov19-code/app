# Teknik Mimari Taslağı

## 1) Önerilen Teknoloji Yığını

### Mobil
- React Native (TypeScript) **veya** Flutter
- Harita/GPS SDK
- Cihaz sensör erişimi (adım sayar)

### Backend
- Firebase Authentication
- Cloud Firestore (gerçek zamanlı veri)
- Cloud Functions (hesaplama ve otomasyon)
- Cloud Storage (medya)

### Ödeme
- Stripe (veya yerel PSP adaptörü)

### Yönetici Paneli
- Web app (React + component library)
- Rol bazlı yetkilendirme (admin/editor)

## 2) Mantıksal Modüller

- **Auth Service:** Kayıt, giriş, rol bilgisi
- **Tracking Service:** Adım, GPS, aktivite oturumu
- **Achievement Engine:** Rozet ve ilerleme hesaplama
- **Tours Service:** Tur katalogu, kontenjan, rezervasyon
- **Billing Service:** Abonelik, ödeme geçmişi, fatura olayları
- **Community Service:** Sıralama, paylaşım, davet
- **Analytics Service:** KPI olaylarını toplama

## 3) Veri Modeli (Örnek Koleksiyonlar)

- `users`
- `health_profiles`
- `activity_sessions`
- `distance_milestones`
- `badges`
- `tours`
- `tour_bookings`
- `subscriptions`
- `leaderboard_snapshots`

## 4) Güvenlik ve Uyum

- Firestore security rules ile alan bazlı erişim
- Hassas veriler için en az ayrı koleksiyon + kurallı erişim
- Ödeme webhook doğrulama
- Log denetimi ve kötüye kullanım izleme

## 5) Ölçeklenebilirlik

- Liderlik tabloları için periyodik snapshot yaklaşımı
- Yoğun hesaplamaları Cloud Functions queue modeline taşıma
- Mobilde offline-first önbellek ve yeniden senkronizasyon
