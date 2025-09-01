# 📦 Dvice Stok Takip Uygulaması

Bu proje, **Python + Tkinter** kullanılarak geliştirilmiş modern bir **stok takip uygulamasıdır**.  
Ürün ekleme, silme, stok azaltma, filtreleme, istatistiksel özetler ve grafiksel stok durum analizi gibi özellikler içerir.  

## 🚀 Özellikler

- ✅ **Ürün ekleme** (isim, stok miktarı, minimum stok)  
- ✅ **Stok azaltma ve silme**  
- ✅ **Arama ve filtreleme**  
- ✅ **Detaylı stok listesi** (renkli uyarı sistemi)  
- ✅ **Stok özet istatistikleri** (toplam stok, kritik stok sayısı)  
- ✅ **Grafiksel gösterim** (stok yüzdeleri bar grafik olarak)  
- ✅ **CSV / Excel aktarma desteği**  
- ✅ **Verilerin kalıcı saklanması** (SQLite veritabanı)  

## 🖼️ Arayüz Görselleri

🔹 Sol panel: Ürün ekleme, filtreleme, stok azaltma ve silme işlemleri  
🔹 Sağ panel: Stok listesi tablosu ve dinamik grafik  


## 🛠️ Kullanılan Teknolojiler

- **Python 3.x**
- **Tkinter** (GUI)
- **SQLite3** (veritabanı)
- **Matplotlib** (grafikler)
- **openpyxl** (Excel desteği)

## 📥 Kurulum

1. Bu repoyu klonlayın:
   ```bash
   git clone https://github.com/kullaniciadi/stok-takip-uygulamasi.git
   cd stok-takip-uygulamasi
2.Gerekli bağımlılıkları yükleyin:

```pip install matplotlib openpyxl```

3.Uygulamayı çalıştırın:

```python app.py```

Dosya Yapısı:
📦 stok-takip-uygulamasi
 ┣ 📜 app.py              # Ana uygulama
 ┣ 📜 stock.db            # SQLite veritabanı (otomatik oluşur)
 ┣ 📜 README.md           # Proje açıklaması

📊 Grafik Renkleri

🟥 Kırmızı → Kritik stok (< %100)

🟧 Turuncu → Uyarı (%100 - %150)

🟩 Yeşil → Normal stok (> %150)

✨ Katkı

Pull request gönderebilir, önerilerinizi paylaşabilirsiniz.


## 🖼️ Arayüz Görseli

<img width="1200" height="777" alt="image" src="https://github.com/user-attachments/assets/eae9772c-8a99-4131-98ca-1eaa4351bda3" />



