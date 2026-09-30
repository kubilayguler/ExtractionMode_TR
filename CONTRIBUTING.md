# Çeviriye Katkıda Bulunma Rehberi (Contributing)

Extraction Mode Türkçe Çeviri projesine katkıda bulunmak istediğiniz için teşekkürler! Projenin kaliteli, tutarlı ve hatasız kalması için lütfen aşağıdaki kurallara dikkat edin.

---

### 📂 Dosya Yapısı ve Çeviri Alanları

Tüm çeviri dosyaları `42/media/lua/shared/Translate/TR/` dizininde yer almaktadır:

- `ContextMenu.json`: Sağ tık bağlam menüleri (Örn: *Tahliye Helikopterine Bin*, *Baskın Hedefi Seç...*).
- `IG_UI.json`: Oyun içi arayüz, sığınak geliştirmeleri, görev açıklamaları, telsiz anonsları ve diyaloglar.
- `ItemName.json`: Modun eklediği özel eşyalar, evraklar ve tıbbi malzemeler.
- `Sandbox.json`: Sandbox oyun modu seçenekleri ve detaylı ayar açıklamaları.
- `Tooltip.json`: Eşya bilgi balonları.
- `UI.json`: Mod seçenekler sekmesi.

---

### 📝 Çeviri İlkeleri & Sözlük

1. **Özel Değişkenler ve Etiketler:**
   - Oyun motorunun dinamik doldurduğu `%1`, `%2`, `%%` gibi değişkenleri değiştirmeyin veya silmeyin.
   - Metin içi biçimlendirmeleri (`<LINE>`, `<RGB:r,g,b>`, `<SIZE:...>`) aynen koruyun.

2. **Oyun Terimleri ve Sözlük:**
   - **Coop:** Olduğu gibi bırakılır (*Kooperatif* olarak çevrilmez).
   - **PvP:** Olduğu gibi bırakılır.
   - **Hideout:** *Sığınak*
   - **Raid:** *Baskın*
   - **Extraction:** *Tahliye*
   - **Flare / Flare Gun:** *İşaret Fişeği / İşaret Fişeği Tabancası*
   - **Delivery Container:** *Teslimat Konteyneri*

3. **Kodlama ve Format:**
   - Dosyalar her zaman **UTF-8 (BOM'suz)** olarak kaydedilmelidir.
   - JSON formatının bozulmadığından emin olun (virgüller ve çift tırnak işaretleri).

---

### 🚀 Pull Request Açma Süreci

1. Repoyu fork'layın ve değişiklikleriniz için anlamlı bir dal (branch) açın.
2. Değişikliğinizi yapıp JSON dosyasını bir JSON doğrulayıcı ile test edin.
3. Commit mesajınızda hangi bölümü düzelttiğinizi kısaca belirtin.
4. Pull Request açarken değişiklik gerekçenizi açıklayın.

Katkılarınız için şimdiden teşekkür ederiz!
