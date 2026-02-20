# idmancım.az — Önerilen Sistem Mimarisi

## 1) İstemciler
- Mobil uygulama (React Native veya Flutter)
- Web yönetici paneli (React + TypeScript önerilir)

## 2) Backend (Firebase odaklı)
- Firebase Auth: kullanıcı kimlik doğrulama
- Firestore: uygulama verisi
- Firebase Storage: medya/video içerikleri
- Cloud Functions: iş kuralları, bildirim, ödeme callback
- FCM: push bildirimler

## 3) Dış Servisler
- Harita/GPS: Google Maps veya Mapbox
- Ödeme: Stripe + yerel ödeme sağlayıcı fallback
- Hava durumu: 3. parti API
- Sağlık entegrasyonu: Apple Health, Google Fit (2. faz)

## 4) Çekirdek Domain Modeli
- `users`
- `health_profiles`
- `activity_sessions`
- `achievements`
- `animal_badges`
- `leaderboard_snapshots`
- `tours`
- `tour_bookings`
- `subscriptions`
- `promo_codes`

## 5) Güvenlik
- Firestore Security Rules ile rol tabanlı erişim
- Admin işlemleri yalnızca özel claim ile
- Ödeme webhook doğrulaması
- KVKK/GDPR uyumlu veri saklama politikası

## 6) Ölçeklenebilirlik
- Yazma yükü yüksek sayaçlarda aggregate stratejisi
- Leaderboard için periyodik snapshot
- Cloud Functions queue desenleri

## 7) Gözlemlenebilirlik
- Crashlytics
- Performance Monitoring
- Audit log (admin panel işlemleri)

## 8) Yayınlama Stratejisi
- iOS TestFlight + Android Internal Testing
- Feature flag ile kademeli açılış
- Bölgesel rollout (Azerbaycan → Türkiye → global)

