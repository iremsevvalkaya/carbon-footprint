# 🌍 Google Geocoding API ile Karbon Ayak İzi Hesaplama

Bu projede, **Google Maps Geocoding API** kullanılarak sevkiyat noktalarının enlem ve boylam koordinatları fiziksel adreslere dönüştürülmüş, ardından bu adresler arası mesafeye göre **karbon ayak izi hesaplaması** yapılmıştır.

##  Özellikler

- 📍 Koordinatlardan adres çözümleme (Geocoding)
- 🚛 İki adres arasındaki mesafenin hesaplanması
- 🌱 Karayolu taşımacılığı için karbon emisyon miktarının tahmini

## 🛠️ Kullanılan Teknolojiler

- Python (Google Colab)
- Google Maps Geocoding API
- Kütüphaneler: 
  - `geopy`
  - `pandas`
  - `numpy`
  - `requests`
  

## 📌 Uygulama Alanları

- Lojistik şirketleri için **sevkiyat bazlı emisyon takibi**
- **Karbon ayak izi raporlaması** yapmak isteyen firmalar
- ERP / MES sistemlerine çevresel veri entegrasyonu
- Sürdürülebilirlik projelerinde ölçümleme altyapısı

## 📄 Nasıl Kullanılır?

1. Google Cloud Console üzerinden bir Geocoding API anahtarı edinin.
2. `carbon_footprint.ipynb` dosyasındaki `API_KEY` alanına kendi anahtarınızı girin.
3. Notebook'u çalıştırarak örnek sevkiyatlar üzerindeki analizleri inceleyin veya kendi verinizi ekleyin.

## 🔒 Not

- Bu proje eğitim ve prototipleme amaçlıdır. Gerçek dünya uygulamaları için taşıma türüne özel emisyon katsayıları ve doğruluk kontrolleri detaylandırılmalıdır.
- Google API kullanımında kota ve ücretlendirme detaylarını göz önünde bulundurunuz.

## 📬 İletişim

Her türlü geri bildirim veya katkı için iletişime geçebilirsiniz:  
📧 iremsevvalceng@gmail.com



