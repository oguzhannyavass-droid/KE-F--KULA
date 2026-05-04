# Yeşil İz - Mobil Uygulamaya Dönüştürme Planı

Mevcut web projemizi (Yeşil İz) bir mobil uygulamaya dönüştürmek harika bir fikir! Uygulamanın altyapısı (Vanilla JS + CSS) mobil uyumlu olduğu için bu dönüşüm oldukça pürüzsüz olacaktır.

Ancak ortamınızda (önceki aşamalarda gördüğümüz üzere) şu an için Node.js ve npm geliştirici araçları yüklü değil. Bu durumu göz önüne alarak önümüzde 3 farklı yol bulunuyor.

## User Review Required

> [!IMPORTANT]
> Lütfen mobil uygulamaya dönüşüm için aşağıdaki 3 seçenekten hangisiyle ilerlemek istediğinizi belirtin. Ortamınızda Node.js yüklü olmadığı için en hızlı, ücretsiz ve sorunsuz yöntem **Seçenek 1 (PWA)** olacaktır. Gerçek bir APK dosyası (Play Store için) istiyorsanız Seçenek 2'yi seçip bazı programları kurmanız gerekecektir.

## Seçenekler ve Açık Sorular

> [!WARNING]
> **Hangi yöntemle ilerleyelim? Lütfen birini seçin:**
> 
> **Seçenek 1: Progressive Web App (PWA) - [Hızlı ve Önerilen Yöntem]**
> Hiçbir ek geliştirici programı (Node.js, Android Studio vb.) kurmanıza gerek kalmaz. Mevcut kodlara `manifest.json` ve `service-worker` ekleyerek uygulamanın telefon tarayıcılarından (iOS Safari ve Android Chrome) "Ana Ekrana Ekle / Uygulama Olarak Yükle" butonuyla indirilmesini sağlarız. Çevrimdışı çalışabilir ve telefonda tıpkı normal bir uygulama gibi ikonlu, tam ekran açılır.
> 
> **Seçenek 2: Capacitor JS ile Gerçek Mobil Uygulama (APK / AAB)**
> Web kodlarımızı paketleyerek doğrudan Google Play Store veya App Store'a yüklenebilecek gerçek bir mobil formata çeviririz.
> *Gereksinimler:* Bilgisayarınıza Node.js ve Android Studio kurmanız gerekecektir. Gerekli kurulumları yapmaya hazırsanız bu yolu seçebiliriz.
> 
> **Seçenek 3: React Native / Expo (Sıfırdan Saf Mobil Yazılım)**
> Uygulamayı web teknolojileriyle değil, tamamen saf mobil kodlama diliyle sıfırdan yazarız.
> *Gereksinimler:* Yine Node.js, Android Studio ve çeşitli mobil SDK'leri bilgisayarınıza kurmanız gerekir.

## Proposed Changes (Eğer Seçenek 1 - PWA Seçilirse)

PWA ile ilerlersek, uygulamayı mobilleştirmek için şu değişiklikleri yapacağım:

#### [NEW] `manifest.json`
Uygulamanın adı (Yeşil İz), ikonları, tema renkleri ve telefondaki görünüm ayarlarını (tam ekran, status bar rengi vb.) içeren konfigürasyon dosyasının oluşturulması.

#### [NEW] `service-worker.js`
Uygulamanın çevrimdışı (internetsiz) çalışabilmesi ve hızlı açılması için gerekli dosyaları cihaz hafızasına alan arka plan servisinin yazılması.

#### [MODIFY] `index.html`
PWA bağlantılarının (manifest ve service worker), mobil meta etiketlerinin (`theme-color`, `apple-mobile-web-app-capable`) ve iOS cihazlar için gerekli `apple-touch-icon` tanımlarının eklenmesi.

#### [NEW] İkonların Üretilmesi
Mobil cihazların ana ekranında görünecek "Yeşil İz" uygulama ikonlarının (192x192, 512x512) oluşturulması/eklenmesi.

## Verification Plan
1. Değişiklikler yapıldıktan sonra proje telefondan erişilebilir bir adreste çalıştırılıp (veya yerel ağda) test edilecek.
2. Telefonda "Ana Ekrana Ekle" (Install App) yönlendirmesinin çıktığı ve uygulamanın çevrimdışı da tam ekran açılabildiği doğrulanacak.
