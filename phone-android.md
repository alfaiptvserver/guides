# Alfa IPTV Player - Android Kurulum Rehberi

## 🎯 Hızlı Başlangıç

**Alfa IPTV Player**, özel olarak optimize edilmiş yüksek performanslı IPTV oynatıcımızdır. Tüm Android cihazlarda sorunsuz çalışır ve benzersiz özellikleriyle fark yaratır.

---

## 📲 Uygulama Kurulumu

### Yöntem 1: Google Play Store
1. [Alfa IPTV Player'ı Play Store'dan indirin](https://play.google.com/store/apps/details?id=com.alfaiptv.player)
2. Uygulamayı açın ve kurulum sihirbazını takip edin

### Yöntem 2: APK Kurulumu
1. [APK dosyasını indirin](https://download.alfaiptv.com/player/latest.apk)
2. **Ayarlar** → **Güvenlik** → **Bilinmeyen Kaynaklara İzin Ver**
3. İndirilen APK dosyasını çalıştırın

> ⚠️ **Güvenlik Notu:** Sadece resmi kaynaklardan indirin

---

## ⚙️ Bağlantı Ayarları

### Xtream Codes API Bağlantısı

Uygulamayı açtıktan sonra **"Yeni Bağlantı Ekle"** butonuna tıklayın ve aşağıdaki bilgileri girin:

| Alan | Değer | Açıklama |
|------|-------|----------|
| **Bağlantı Adı** | Alfa IPTV | İstediğiniz ismi verebilirsiniz |
| **Sunucu URL** | `http://{server_url}:8080` | Sunucu adresiniz |
| **Kullanıcı Adı** | `{username}` | Size özel kullanıcı adınız |
| **Şifre** | `{password}` | Hesap şifreniz |
| **EPG Kayması** | 0 | Türkiye için 0 bırakın |

### Bağlantı Testi

Bilgileri girdikten sonra **"Bağlantıyı Test Et"** butonuna tıklayın:
- ✅ **Başarılı:** "Bağlantı başarılı" mesajı
- ❌ **Başarısız:** [Sorun giderme](#sorun-giderme) bölümüne bakın

---

## 🎨 Uygulama Özellikleri

### Canlı TV
- **7000+** yerli ve yabancı kanal
- **Kategori filtreleme** sistemi
- **Hızlı arama** özelliği
- **Favori listesi** oluşturma
- **Son izlenenler** geçmişi

### VOD (Film & Dizi)
- **50.000+** içerik
- **IMDB entegrasyonu**
- **Türkçe dublaj/altyazı** seçeneği
- **Kaldığın yerden devam et**
- **İzleme listesi** oluşturma

### EPG (TV Rehberi)
- **7 günlük** program akışı
- **Hatırlatıcı** kurma
- **Program kayıt** özelliği (Pro)
- **Catch-up TV** - Geçmiş yayınları izleme

---

## 🚀 Gelişmiş Özellikler

### Multi-Screen (Çoklu Ekran)
4 kanalı aynı anda izleyin:
1. Ana menü → **Çoklu Ekran**
2. Her pencerede farklı kanal seçin
3. Sesi aktif etmek için pencereye tıklayın

### Ebeveyn Kontrolü
Çocuklarınız için güvenli izleme:
1. **Ayarlar** → **Ebeveyn Kontrolü**
2. 4 haneli PIN belirleyin
3. Yaş sınırı ayarlayın
4. Kategorileri kilitleyin

### Oynatıcı Seçenekleri

| Oynatıcı | Codec Desteği | Hardware Decoding | Altyazı | Tavsiye |
|----------|---------------|-------------------|---------|---------|
| **Dahili Player** | H.264, H.265 | ✅ | ✅ | Önerilen |
| **ExoPlayer** | Tüm formatlar | ✅ | ✅ | Alternatif |
| **VLC Player** | Tüm formatlar | ⚠️ | ✅ | Sorunlu yayınlar için |
| **MX Player** | Tüm formatlar | ✅ | ✅ | Harici kurulum gerekli |

---

## 🎬 Oynatma Ayarları

### Video Kalitesi
Ayarlar → Oynatma → Video Kalitesi:
- **Otomatik** - Bağlantı hızına göre (Önerilen)
- **4K (2160p)** - 25+ Mbps bağlantı
- **Full HD (1080p)** - 10+ Mbps bağlantı  
- **HD (720p)** - 5+ Mbps bağlantı
- **SD (480p)** - 2+ Mbps bağlantı

### Buffer Ayarları
Kesintisiz izleme için:
