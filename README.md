# idmancım.az — Ürün Spesifikasyonu (MVP + Yol Haritası)

Bu depo, **idmancım.az** girişiminin mobil uygulama ve web yönetim paneli için başlangıç ürün dokümantasyonunu içerir.

## Proje Özeti

**Kurucu:** Tuncay Qurbanlı  
**Ürün Tipi:** Mobil Uygulama (iOS + Android) + Geleceğin Web Kontrol Paneli  
**Konumlandırma:** Fitness + Doğa Yürüyüşü + Sağlık + Turizm entegre platformu

## Temel Vaat

Kullanıcının gerçek dünyadaki hareketleri (adım, mesafe, rakım) izlenir; bu hareketler oyunlaştırılmış bir başarı yoluna dönüştürülür ve topluluk/tur rezervasyon sistemi ile değer yaratılır.

## Ana Özellik Alanları

1. **Akıllı Hareket Takip Sistemi**
   - Adım sayacı, GPS mesafe, kalori, aktif zaman, rakım
2. **Başarı Yolu (Gamification)**
   - Kilometre bazlı hayvan rozetleri ve profil amblemleri
3. **Yollar (Tur Paketleri)**
   - Tur listeleme, zorluk, fiyat, kontenjan, rezervasyon/ödeme
4. **Tren (Kişisel Antrenman)**
   - Seviye ve hedefe göre planlar, premium içerik
5. **Sağlık Entegrasyonu**
   - Sağlık profil girişi, Apple Health / Google Fit uyumluluğu
6. **Topluluk Modülü**
   - Liderlik tablosu, başarı paylaşımı, davet sistemi
7. **Abonelik Sistemi**
   - Ücretsiz ve Premium katman ayrımı
8. **Yönetici Paneli**
   - Kullanıcı, tur, analitik, gelir, promosyon kod yönetimi

## Dokümanlar

- [Ürün Gereksinim Dokümanı (TR)](docs/PRD.tr.md)
- [MVP Yol Haritası](docs/MVP-roadmap.md)
- [Teknik Mimari Taslağı](docs/architecture.md)

## Tasarım Sistemi (Özet)

- Ana Renk: `#0B5D3B` (Koyu Doğal Yeşil)
- İkincil: `#1E88E5` (Gökyüzü Mavisi), `#D32F2F` (Enerji Kırmızısı)
- Nötr: Beyaz, Kömür Siyahı
- Stil: Minimal, premium, temiz UI, dış mekan enerjisi

## Başlangıç Kapsamı (MVP)

MVP sürümünde aşağıdaki akışın uçtan uca çalışması hedeflenir:

**Kaydol → Sağlık verilerini gir → Takibi başlat → İlk rozetin kilidini aç → Toplulukta görünür ol → Tur rezervasyonu yap → Premium teklifini gör**
