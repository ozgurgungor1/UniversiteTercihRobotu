# UniversiteTercihRobotu

![Ekran görüntüsü 2025-06-05 173932](https://github.com/user-attachments/assets/31774235-7127-4133-b48f-217935bce1d0)

# Türkiye Üniversiteleri ve Bölümleri JSON Verisi

Bu projede, Türkiye'deki üniversitelerin bölümleri, puan türleri, taban sıralamaları ve şehir bilgilerini içeren kapsamlı bir JSON veri seti sunulmaktadır. Tercih robotları, eğitim danışmanlığı yazılımları, analiz araçları ve benzeri projeler için kullanılabilir.


## 📂 Dosya İçeriği

- `bolumler.json`: Türkiye'deki üniversitelerin çeşitli bölümlerine ait aşağıdaki bilgileri içeren JSON veri seti:
  - `universite`: Üniversite adı
  - `bolum`: Bölüm adı
  - `puan_turu`: Sayısal, Sözel, Eşit Ağırlık gibi puan türü
  - `taban_sirasi`: YÖK Atlas verilerine göre taban başarı sırası
  - `sehir`: Üniversitenin bulunduğu şehir







## 🔍 Kullanım Örnekleri
Bu veri seti aşağıdaki uygulamalarda kullanılabilir:

✅ Tercih robotları

✅ Üniversite-bölüm karşılaştırma araçları

✅ Veri analizi / raporlama sistemleri

✅ Mobil veya masaüstü tercih uygulamaları

✅ Python / C# / JavaScript ile filtreleme ve öneri sistemleri






## 📊 Planlanan Geliştirmeler
🔄 Şehir filtreleme destekli web arayüzü

🎯 Sıralamaya göre bölüm önerme algoritması

📈 Üniversiteye göre ortalama taban sıralaması hesaplama

🗄️ Veritabanı (SQL/MongoDB) entegrasyonu

🌐 API ile veri sunumu (isteğe bağlı)





## 📌 Örnek Kayıt

```json
{
  "universite": "İstanbul Teknik Üniversitesi",
  "bolum": "Bilgisayar Mühendisliği",
  "puan_turu": "Sayısal",
  "taban_sirasi": 5000,
  "sehir": "İstanbul"
}
