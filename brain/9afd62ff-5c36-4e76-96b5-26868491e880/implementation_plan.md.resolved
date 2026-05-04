# Gezilecek Yerler Sayfası Rehber Tasarımı (Guide Layout)

Mevcut `GezilecekYerler.html` sayfasını kart tabanlı 3D kaydırıcı tasarımından çıkarıp, daha profesyonel ve bilgilendirici bir **Gezi Rehberi (Travel Guide)** formatına dönüştüreceğiz.

## ⚠️ Kullanıcı İncelemesi ve Kararlar

Aşağıdaki sorular tasarımı şekillendirmemiz için önemli:

> [!IMPORTANT]  
> **Arka Plan ve Okunabilirlik:** Şu anki atmosferik karanlık arka plan sabit kalacak, rehber içerikleri ise okunabilirliği artırmak için bu arka planın üzerinde yarı saydam "Bulanık Cam" (Glassmorphism) efektli kutular içinde aşağıya doğru kayacak. Bu sizin için uygun mu?

> [!QUESTION]
> **Yerleşim Düzeni:** Her bir mekan (Peri Bacaları, Kula Evleri vb.) için tasarımı nasıl yapalım?
> **Seçenek A (Zikzak Düzen):** Bir mekanda görsel solda, yazı ve harita sağda; diğer mekanda tam tersi. (Modern ve hareketli durur)
> **Seçenek B (Blog Düzeni):** Mekanın büyük bir görseli en üstte, yazısı ve haritası ise hemen altında tüm genişliğe yayılan bir düzende olsun. (Daha dergi vari bir okuma sunar)
> Lütfen tercih ettiğiniz seçeneği belirtin.

## Önerilen Değişiklikler

Sayfa yapısı tamamen değişeceği için `GezilecekYerler.html` dosyası baştan aşağı güncellenecektir.

### [MODIFY] GezilecekYerler.html

1. **Bağımlılıkların Kaldırılması:**
   - Swiper.js kütüphanesi ve ona ait CSS dosyaları sayfadan kaldırılacak.
   - Açılır pencere (Modal) yapısı ve ona ait JavaScript kodları silinecek.

2. **Yeni Rehber Yapısının Kurulması:**
   - En üste görkemli bir "Kula Gezi Rehberi" başlığı ve kısa bir giriş metni eklenecek.
   - Her mekan (Kuladokya, Kula Evleri, Jeopark, Kız Köprüsü) alt alta listelenen devasa bloklar haline getirilecek.
   - Her mekan bloğu şunları içerecek:
     - Başlık ve Mekan Görseli
     - Detaylı Açıklama Metni
     - Doğrudan sayfa içine gömülü (tıklamadan görünen) Google Haritası
     - İleride video ve ek fotoğraflar koyabileceğiniz "Galeri" alanı

3. **Hızlı Gezinme (TOC - Table of Contents):**
   - Sayfanın uzun olacağı göz önünde bulundurularak, sayfanın bir köşesinde (veya üstünde sabit) "Hızlı Menü" oluşturulacak. Bu menü ile tek tıkla istenilen mekana kaydırma yapılabilecek.

## Doğrulama Planı
- Swiper kodlarının tamamen temizlendiğinden emin olunacak.
- CSS Grid ve Flexbox kullanılarak responsive (mobil uyumlu) yeni rehber dizilimi test edilecek.
- Haritaların sayfa içinde sorunsuz yüklendiği doğrulanacak.
