# KulaPerest Web Sitesi Tasarımı

Kula ilçesini ve zanaatlerini tanıtan, toprak ve tuğla renklerinin hakim olduğu, ana ekranda 3 boyutlu bir slider içeren modern bir açılış sayfası (landing page) tasarlanacaktır.

## Açık Sorular / Kullanıcı İncelemesi Gerekli

> [!WARNING]  
> Mesajınızda **"tamamen yüklediğim videoya uygun bir şekilde olsun"** demişsiniz, ancak sistem üzerinden herhangi bir video veya eklenti bana ulaşmadı. Videonun bir YouTube/Vimeo linki varsa paylaşabilir misiniz? Veya videodaki animasyonların nasıl olduğunu (örneğin kutular nasıl dönüyor, yatay mı dikey mi) kısaca tarif edebilir misiniz?  
> Eğer videoya erişemezsek, modern web standartlarında çok şık duran **3D Coverflow** tarzı bir slider (kutuların ortadakinin büyük, kenardakilerin açılı ve geride durduğu bir yapı) kuracağım.

## Önerilen Uygulama (Plan)

Tasarımı şu an açık olan dosyanız olan `c:\Users\skate\OneDrive\Desktop\Kulaperest.html` içine tek bir sayfa (HTML + CSS + JS bir arada) olarak veya isterseniz düzgün bir klasör yapısı (index.html, style.css, app.js) ile kurabilirim. Hızlı sonuç ve test için tek dosyada derli toplu bir yapı oluşturulması önerilir.

### 1. Renk Paleti ve Tasarım Sistemi
- **Toprak Rengi:** `#A0522D` (Sienna) ve tonları
- **Tuğla Rengi:** `#B22222` (Firebrick) / `#C35831`
- **Koyu Tema / Siyah:** `#121212` / `#1A1A1A`
- **Arka Plan:** Kula evleri / sokakları veya genel görünümünü temsil eden bir fotoğraf. Fotoğrafın üzerine koyu bir overlay (CSS: `rgba(0,0,0, 0.7)`) atılarak menünün ve 3D slider'ın parlaması (öne çıkması) sağlanacak.

### 2. Bileşenler (Components)

#### Navbar (Menü)
- Sol tarafta şık bir font ile **KulaPerest** yazısı.
- Sağ tarafta veya ortada menü linkleri: **Zanaatler**, **Gezilecek Yerler**, **İletişim**.
- Tasarım: Cam efekti (Glassmorphism) veya hafif saydam siyah bir arka plan, tuğla rengi hover (üzerine gelme) efektleri.

#### Hero Bölümü & 3D Slider
- Ekranın tam ortasında 3 boyutlu olarak dönen dikdörtgen kartlar.
- Kartların içerikleri:
  1. **Demircilik**
  2. **Fırıncılık**
  3. **Halı Dokumacılığı**
  4. **Leblebi İmalatı**
- Kartların tasarımı: İçerisinde bu zanaatleri temsil eden yüksek kaliteli yapay zeka üretimi görseller, alt kısımlarında yarı saydam bir alanda zanaatın ismi. 
- Altyapı: `Swiper.js`'in 3D Effect özelliği kullanılacak. 

### 3. Kullanılacak Teknolojiler
- HTML5 & CSS3
- Google Fonts (Modern ve okunaklı fontlar örn. 'Outfit' veya 'Inter')
- Swiper JS (3 Boyutlu Slider animasyonları için)

## Doğrulama Planı
1. Belirtilen `Kulaperest.html` dosyasına kodlar yazılacak.
2. AI araçları (generate_image) kullanılarak zanaatleri ve arka planı temsil edecek şık görseller oluşturulup sayfaya dahil edilecek.
3. Tasarım tarayıcıda açılarak responsive (mobil uyumlu) olup olmadığı, 3D animasyonların akıcılığı ve renklerin estetiği kontrol edilecek.

> [!NOTE]  
> Lütfen planı inceleyip onay veriniz. Özellikle bahsettiğiniz **video** hakkında bilgi verirseniz çok sevinirim. Eğer video yoksa, yukarıdaki plan üzerinden muhteşem bir 3D slider ile siteyi oluşturmaya başlayabilirim.
